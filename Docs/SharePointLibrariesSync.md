
<a id="top" />

<a id="sync-sharepoint-libraries-to-your-computer" />

# Sync SharePoint Libraries to your computer

If your organization has a Microsoft 365 work or school subscription or uses SharePoint Server 2019 and Teams, you can sync your Microsoft SharePoint and Teams files to a folder on your computer.

This lets you work directly in File Explorer and access files even when you're offline. And when you go back online, any changes made to those files will sync automatically.

<br/>

<a id="sync-sharepoint-and-teams-files-with-your-computer" />

<br/>


## Sync SharePoint and Teams files with your computer

1. On the Microsoft 365 app launcher, select SharePoint or Teams, and then select the site with the files you want to sync.

1. Select Documents or navigate to the subfolder you want to sync.

1. Select Sync. (You only need to do this once on a computer to set up syncing on that computer. After you set up syncing, the files sync automatically.)

    ![SharePoint Document Library Sync](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibrarySync.png)

1. If your browser requests permission to use "Microsoft OneDrive," confirm that this is okay.

    > **Important:** If a screen appears stating "Which library do you want to sync?", your site hasn't been set up to sync with the OneDrive sync app. If you're the IT admin for your organization, see Let users sync SharePoint files with the new OneDrive sync app. If you're not the IT admin, and your screens don't look like the ones in this article, see Sync SharePoint files with the OneDrive sync app (Groove.exe), or contact your IT department.


    The files then sync to a folder on your PC that has the name of your organization (for example, %userprofile%\[organization-name]). This folder is automatically added to the left pane in File Explorer. You can’t select to sync to a different location.

1. To sync the files on another computer, go to that computer, and follow these steps again.

**Change sync settings**

To change the folders that sync for a site, or to stop syncing all files on a site, follow these steps:

1. Select the blue OneDrive cloud icon in the Windows taskbar notification area.

    ![OneDrive SyncClient with blue cloud and white cloud icons](https://www.rramoscabral.com/training/assets/MSOneDrive/WindowsTaskbar.png)
    
    > Image source: Microsoft

    (You may need to select the Show hidden icons arrow The Show hidden icons button. next to the notification area for the **OneDrive** icon to appear. If the icon doesn't appear in the notification area, OneDrive might not be running. Select Start, enter **OneDrive** in the search box, and then select OneDrive in the search results.)

   ![Windows system tray with arrow indicating hidden icons](https://www.rramoscabral.com/training/assets/MSOneDrive/WindowsTaskbarShowHiddenIcons.png)
   
   > Image source: Microsoft


1. Select [OneDrive Help and Settings icon](https://www.rramoscabral.com/training/assets/MSOneDrive/IconSettings.png) **Help & Settings** > **Settings**.

    ![Screenshot of getting to OneDrive Settings](https://www.rramoscabral.com/training/assets/MSOneDrive/IconSettings.png)

    > Image source: Microsoft

1. To see a list of all your syncing sites, select the Account tab.

    ![Screenshot of account settings in the OneDrive sync client.](https://www.rramoscabral.com/training/assets/MSOneDrive/AccountTab.png)

1. To change the folders that you're syncing, select **Choose folders** for that library, and then select the folders that you want to sync. To stop syncing a site, select **Stop sync** next to the site. (Copies of the files remain on your computer. You can delete them if you want.)


<br/>

<a id="add-shortcut-to-onedrive" />

<br/>

## Add shortcut to OneDrive

When someone shares a folder in Microsoft OneDrive, SharePoint, or Teams, you can add a shortcut to the shared folder in your OneDrive to easily find and work with the files. These shortcuts appear in OneDrive on the web, Windows File Explorer, Mac Finder, Teams, and in the OneDrive mobile apps.

An Microsoft Global admin or SharePoint admin can disable ***Add shortcut to OneDrive***.

1. In OneDrive, in the navigation pane, select Shared > Shared with me.

1. Find the folder you want to add, and click the circle in the folder's tile to select it.

1. Select Add shortcut to My files.

    ![SharePoint Document Library add shortcut to OneDrive](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryAddShortcuToOneDrive.png)

    - Or you can right-click the folder, and then select Add shortcut to My files.

    - In a shared library in SharePoint or Microsoft Teams, you can select Add shortcut to My files to add a shortcut to the entire library, or select the specific folder you want to add, and then select Add shortcut to My files. 

<br/>

**Move a shortcut to a shared folder**

You can move a shortcut to a folder just like any other file or folder. 

> **Note:** When moving a shortcut to a folder into a shared folder, the short cut does not change its sharing permissions. People who don't currently have access to the shortcut won't be able to access its content, but can rename or remove the shortcut.


1. Select the shortcut you want to move. To do so, in List view, check the circle that appears to the left of the item when you hover the pointer there. In Tiles or Photo view, check the circle in the upper-right corner of the tile when you hover the pointer there. You can also select multiple items to move them together, as a group.

1. In the top navigation, select **Move to**.

1. In the **Move to** pane, browse to the destination folder and select **Move**.

    - If you want to create a new folder to store the item, select **New folder**.

    - **Tip:** Instead of using the **Move to** button, you can select the shortcut you want to move and drag it into the destination folder.

<br/>

**Find shared folders in your OneDrive**

Shared folders you've added to your OneDrive appear on the OneDrive website in your **My files** view.

On a Windows PC, find the OneDrive folder with the name of your organization after it in Windows Explorer. For example, OneDrive - Contoso. On a Mac computer, use the Finder to locate the OneDrive folder.

> **Notes:** If you have the OneDrive sync app but the shared folder doesn't sync to your computer, you might have selective sync turned on. This isn't common, but to fix it, find the OneDrive cloud icon in the Windows notification area (if you use a Mac, go to the menu bar).

1. Select the OneDrive cloud icon.
1. Select **Help & Settings** > **Settings**.
1. On the **Account** tab, select **Choose folders**, then select the boxes for the folders you want to sync.

<br/>

**Moving shared files and shared folders in your OneDrive**

When you move files between shared folders, they lose their existing permissions and get the permissions from the folder you moved them to. For example, if you move an item to a read-only folder, the item becomes read-only as well. Moving an item from a shared folder to an unshared folder means that item is no longer shared with anyone. If you move items only within a shared folder, there is no change to any of the assigned permissions.

While you can move shared files, you can't move shared folders on OneDrive.com. If you sync OneDrive to your computer, any shared folder you move is copied to the destination location and then removed from your OneDrive. It is still available in your Shared list.

You can rename shared folders that you've added to your OneDrive. The new name you give to the folder is visible only to you, and will appear with that name anywhere you access your OneDrive, including OneDrive.com, the OneDrive app on your computer, or the OneDrive mobile apps. The name change won’t be visible to the shared folder owner, nor anyone else with permissions to the folder.

> **Note:** Renaming or changing any of the folder's contents, however, is visible to others sharing the folder.

<br/>


**Removing or deleting shared files and shared folders from your OneDrive**

Files deleted from a shared folder on OneDrive.com are sent to the recycle bin of only the shared folder’s owner. However, if you sync your OneDrive on a computer, items deleted from a shared folder do appear in the computer’s recycle bin.

> **Note:** Only the owner of a shared folder can restore an item deleted from the folder.

To remove a shared folder on OneDrive.com:

1. In the **My files** view, select the shared folder you want to remove.

1. Select **Remove shortcut**.

    - This only removes the folder from your OneDrive. It's still accessible from your **Shared** list and doesn't affect the owner or anyone else sharing the folder. If you delete the folder instead, it's deleted from everyone's OneDrive and the folder owner would have to restore it.

> **Note:** If you sync OneDrive to one or more computers, removing a shared folder from your OneDrive also removes it from those computers.

If a folder is no longer shared with you, it is removed from your OneDrive. To get back your access to the folder, ask the owner or an editor to share it with you again.



---

<br/>

<div style="font-style: italic; text-align: center;" markdown="1">

Section: Sync SharePoint Libraries to your computer

[<< SharePoint restrictions and limitations](./SharePointRestrictionsLimitations.md) | [back to top](#top) | [Back to Table of Content](./README.md) | [ SharePoint Exercise - Sync SharePoint document library >>](./SharePointExecCreateSharePointLibrarySync.md)

</div>

