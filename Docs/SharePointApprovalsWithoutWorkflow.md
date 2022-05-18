<a id="top" />

<a id="sharepoint-approvals-without-workflow" />

# SharePoint Approvals without workflow

SharePoint workflows can help you automate your business processes, making them both more consistent and more efficient. The Approval workflow lets you route documents and other items stored in SharePoint to one or more people for their approval.

In SharePoint Online version and SharePoint 2019 the SharePoint workflows is being replaced by [Microsoft Power Automate](https://powerautomate.microsoft.com).

In SharePoint 2010 workflows have been retired since August 1, 2020 for new tenants and removed from existing tenants on November 1, 2020. If you’re using SharePoint 2010 workflows, we recommend migrating to Power Automate or other supported solutions. For more info, see SharePoint 2010 workflow retirement.

If you want to use Power Automate to create approved workflows you will need Power Platform Dataverse licensing.

But with a SharePoint document library it is possible to define approvals without flows.

And it's all going to be done with existing SharePoint functionality.
- Versioning feature on a document library.
- Content Approval feature on a document library.
- Alerts feature on a document library.


<br/>

<a id="document-version-controls" />

<br/>

## Document version controls

One of the existing SharePoint features that we are going to use is versioning.

Document collaboration, co-authoring, and List updates with human beings is much better with Versioning enabled. People make mistakes, and Versioning provides the safety net.

Versioning creates a historical record of all changes, with the date/time and indication of the user who made the change, on a per-file/list item basis. The end user can view, delete, and restore a version if they have the correct permissions in the library or list.

So the first step is enabling Versioning

<br>

**Enabling Versioning**

In SharePoint Online or On-Premises, versioning is enabled in the List Settings or Library Settings screens by clicking on the 'Versioning settings' link. 

![Library Settings](https://www.rramoscabral.com/training/assets/MSSharePoint/LibrarySettings.png)



An interface is provided to let you control how many versions you'd like to retain. The user must have the Manage Lists permission capability to enable versioning.

<br/>

**Disabling Versioning**

If you can Enable versioning, you can Disable versioning. Disabling versioning doesn't delete the old versions. End users receive no notification of this change.

> **Note:** A Cautionary Tale: As site owner, if you disable Versioning and don't tell your end users, they'll notify you. In person. 

<br/>

**Major Versus Minor Versions**

Libraries can have both Major versions, which are represented with whole numbers (12.0), and Minor versions, which are represented with decimal numbers (12.3). If your library is configured to use Check In/Check Out, each change performed by a user with a checked-out document will create a minor version.

Lists usually only have Major versions.

> **Note:** All versions count against your SharePoint storage usage, as do files in the recycle bins and files preserved due to retention policies.


<br/>

<a id="require-approval-of-items-in-a-list-or-library" />

<br/>


## Require approval of items in a list or library

Lists and libraries often contain sensitive information, such as marketing campaign budgets or human resources initiatives. It can be important to have only “official” versions of items or files viewable by specific users.

You can require the approval of an item or file before the content becomes visible to specific users. By requiring approval, organizations can apply a significant level of quality and security to its sensitive content


1. Navigate to the list that you want to require approval for.
1. Select **Settings** ![Setting icon](https://www.rramoscabral.com/training/assets/MSSharePoint/IconSettings.png), and then **List settings**.
1. In the **General settings** section, select **Versioning settings**.

     ![Versioning settings](https://www.rramoscabral.com/training/assets/MSSharePoint/LibrarySettingsVersioningSettings.png)

1. In the **Content Approval section**, select **Yes** in answer to the **Require content approval for submitted items?** In the Item **Version History section**, specify whether you want to create versions each time an item is edited. You can also choose to limit the number of versions that are retained.

    - Once you enabled Content Approval you also will have a chance to set Major or Minor versioning and Draft Item Security. 

    ![Versioning Settings ContentApproval](https://www.rramoscabral.com/training/assets/MSSharePoint/VersioningSettingsContentApproval.png)


1. In the **Draft Item Security** section, determine which users can see draft items in the list.

    > **Tip:** If you require content approval for a list or library that already contains items, all of the items in the library are marked Approved.

1. You can choose any of the following:
- Users who can read items in the list.
- Only users who can edit items in the list.
- Only users who can approve items in the list, and the item author (It is set for you by default)

1. Select OK.


1. You will see that a column named **Aproval Status**.

    ![Approval Status Column](https://www.rramoscabral.com/training/assets/MSSharePoint/ApprovalStatusColumn.png)


Now any document that is uploaded to the library will have to be approved. Which means documents that are in Pending or Rejected state will only be seen by the uploader, and those are the approvers. Once approved, they will be seen by everyone.




---

<br/>

<div style="font-style: italic; text-align: center;" markdown="1">

Section: SharePoint Approvals without workflow

[<< SharePoint Exercise - Sync SharePoint document library](./SharePointExecCreateSharePointLibrarySync.md) | [back to top](#top) | [Back to Table of Content](./README.md) | [SharePoint Exercise - SharePoint Approvals without workflow>>](./SharePointExecApprovalsWithoutWorkflow.md)

</div>
