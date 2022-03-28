
<a id="top" />

<a id="sharepoint-restrictions-and-limitations" />

# SharePoint restrictions and limitations


## Limitations of file names and file types in SharePoint and OneDrive

Restrictions and limitations that apply to files, file names and file types when syncing with OneDrive for home, OneDrive for work or school or SharePoint in Microsoft 365.

| Restrictions | Details |
|---|---|
| Invalid characters           | ``` " * : < > ? / \ | ```|
| Invalid file or folder names | ```.lock, CON, PRN, AUX, NUL, COM1 - COM9, LPT1 - LPT9, vti, desktop.ini, any filename starting with ~$. ```|
| Invalid or blocked file types| The list of blocked files will vary depending on organization's settings.|
| Network or mapped drives     | OneDrive doesn't support symbolic links where the Link and Target are both located in the same library location. |
| Network or mapped drives     | OneDrive doesn't support symbolic links where the Link and Target are both located in the same library location. |
| Elevated privileges          | OneDrive can’t be run with elevated privileges.|
| Shared with Me               | You can't synchronize the Shared with Me view grouping of files from a OneDrive for Business site.|
| Guest accounts               |Synchronizing content using an external or guest user is currently not supported by OneDrive.|
| Authenticated proxies        | Authenticated proxies aren’t supported in OneDrive.|
| OneNote notebooks            | OneNote notebooks have their own sync mechanism outside of OneDrive|




<a id="limitations-of-path-lengths-in-sharepoint-and-onedrive" />

<br/>

## Limitations of path lengths in SharePoint and OneDrive

Different apps and Office versions have different limits, and the combination of limitations may be unique to your setup.

The entire decoded file path, including the file name, **can't contain more than 400 characters** for OneDrive, OneDrive for work or school and SharePoint in Microsoft 365. The limit applies to the **combination of the folder path and file name** after decoding. 

For example:
- If the file URL in SharePoint is https://www.contoso.com/sites/marketing/documents/Shared%20Documents/Promotion/Some%20File.xlsx, the limit applies to “sites/marketing/documents/Shared Documents/Promotion/Some File.xlsx.”
- Likewise, if the file URL in OneDrive is https://contoso-my.sharepoint.com/personal/meganb_contoso%20_com/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fmeganb%5Fcontoso%5Fcom%2FDocuments%2FContracts%2FVendor%20Quotations/Some%20File.xlsx, the limit applies to “personal/meganb_contoso_com/Documents/Contracts/Vendor Quotations/Some File.xlsx.”

In addition to the above, if files are synced to a PC or Mac, the following limitations apply:
- Each segment of the path (a segment is a file name or folder name like “Promotion” or “Some File.xlsx” in the examples above) can't be more than 255 characters due to operating system limitations.
- The length of the OneDrive root folder (e.g. C:\users\meganb\OneDrive - Contoso) + the relative path of the file (up to 400 chars) cannot be more than 520 characters.
- The organization name can be updated in the M365 admin center but that will not propagate to existing Sync relationships (only newly established ones). For existing Sync relationships to have the new organization name, users need to unlink and relink their account.

<br/>



<br>

<a id="limitations-of-file-upload-and-download-sizes-in-sharepoint-and-onedrive" />

<br/>

## Limitations of file upload and download sizes in SharePoint and OneDrive

Restrictions and limitations for file upload and download sizes.


| Maximum | Upload | Download |
| --- | :---: | :---:| 
| Sync | 250GB | 250GB |
| Individual files | 250GB | 250GB | 
| Files within a zip | 20GB | 20GB| 

> **Note:** On 3 March 2021 the maximum file upload size was updated to 250 GB. 


<br>



**SharePoint Server versions limit**

SharePoint Server versions only support up to 260 characters for file and path lengths

<br/>

**Older Office version have a lower limit**

| Application | Limit |
| :---: | --- |
| Word 2002       | The total length of both the path and the file name, including the file name extension, exceeds 255 characters.|
| PowerPoint 2002 | The total length of both the path and the file name, including the file name extension, exceeds 256 characters.|
| Access 2002     | The total length of both the path and the file name, including the file name extension, exceeds 249 characters.|
| Excel 2002      | The total length of both the path and the file name, including the file name extension, exceeds 218 characters.|
| Outlook 2002    | The total length of both the path and the file name, including the file name extension, exceeds 255 characters.|

> **Note:** This limitation includes three characters that represent the drive, the characters in the folder names, the backslash character between folders, and the characters in the file name. 


<br>

<a id="file-upload-and-download-sizes-in-sharepoint-and-onedrive" />

<br/>

## Sharing limitations on SharePoint and OneDrive 

There is a limit of 50,000 items (updated on 12 April 2021) that can be shared within a folder and any sub-folders.

To overcome this restriction, move some items into another folder that is not within the original folder, or choose individual files to share.

You may receive the following error message **You can’t share this item because too many items have already been shared in this library** when trying to share more thant 50,000 items.


You can't synchronize the Shared with me view grouping of files from a OneDrive for work or school site.

You may receive the following error message **Delivery has failed to these recipients or groups error when sharing**  when trying to share to an address that is not associated with a Microsoft account.



<br>

<a id="switch-between-classic-and-modern-lists-and-libraries" />

<br/>

**Switch between classic and modern lists and libraries**

To switch between classic and modern views of lists and libraries
1. In the modern experience for a list or document library, select Settings Settings icon ![Settings icon](https://www.rramoscabral.com/training/assets/MSSharePoint/IconSettings.png), and then select List settings or Library settings.
1. In the classic experience, Library Settings or List Settings exists on the ribbon.
1. Towards the end of the list of settings, select Advanced settings and select List experience.
1. Select one of the three options, and to save, select OK.





<br/>


---

<br/>

<div style="font-style: italic; text-align: center;" markdown="1">

Section: SharePoint restrictions and limitations

[<<  SharePoint Exercise - Create SharePoint library](./SharePointExecCreateShareLibrary.md) | [back to top](#top) | [ XXXX  >>](./XXXXX.md)

</div>




