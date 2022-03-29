<a id="top" />

<a id="sharepoint" />

# SharePoint Library

A library is a location on a site where you can upload, create, update, and collaborate on files with team members. 

Each library displays a list of files and key information about the files, such as who was the last person to modify a file. Most sites include a library when you create the site. For example, a team site has a Documents library where you can organize and share your documents.

![Document Library Upload Invoices](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryUploadInvoices.png)

As you need more libraries, you can choose from several ready-to-use library apps and add those to your site. You can also customize libraries in several ways. For example, you can control how documents are viewed, managed, and created. or track versions of files, including how many and which type of version. You can even create custom views, forms, and workflows to help you manage your projects and business processes.


There are several ways to organize files in a library. You can add columns, define views, and create folders. Each approach has its own advantages, and you can combine each approach together to fit the unique needs of your library and your team.


<br/>

<a id="types-of-libraries" />

<br/>

## Types of libraries
Some libraries are created for you when you create a new site, such as the Documents library in a team site. You can customize these libraries for your purposes, or you can create your own additional libraries. Each type of library has a specific purpose and some have a different set of behaviors and features.

> **Important:** You may have fewer or more libraries available on your site, depending on the version of SharePoint that your site is based on, the plan of Microsoft 365 your organization subscribes to, or whether certain features are enabled on your site.

<br/>

| Library type | Description |
| :---: | --- |
| Asset library | To share and manage digital media assets, such as image, audio and video files, use an asset library. An asset library makes it easier for users to discover and reuse digital media files that others have already created, such as logos and corporate images. An asset library also provides content types with properties and views for managing and browsing media assets, such as thumbnails and metadata keywords. For example, you may want to manage and store branded images and reusable content fragments from applications so they are available throughout your enterprise and consistently used.|
| Dashboards library | Contains Web Part pages, Web Part pages with Status Lists, and PerformancePoint deployed dashboards. |
| Data Connections library | To simplify the maintenance and management of data connections, use a data connection library. A data connection library is a centralized place to store Office Data Connection (ODC) files. Each of these files (.odc) contains information about how to locate, log on, query, and access an external data source. Centralizing ODC files in a data connection library also makes it possible to share, manage, and search data connection files from within a SharePoint site, and helps ensure that business data and reports, especially spreadsheets, maintain a consistent set of values and formula results as "one version of the truth".|
| Document library | For many file types, including documents and spreadsheets, use a document library. You can store other kinds of files in a document library, although some file types are blocked for security reasons. When you work with programs that are not blocked, you can create those files from the library. For example, your marketing team may have its own document library for planning materials, news releases, and publications.|
| Form library | If you need to manage a group of XML-based business forms, use a form library. For example, your organization may want to use a form library for expense reports. Setting up a form library requires an XML editor or XML form design program, such as Microsoft InfoPath. The form that people fill out is just an .xml file that contains the data (and only the data) that was entered into the form, such as the expense date and the amount. Everything else that makes up the expense report is provided by the form template. After people fill out forms, you can merge the form data or export it for analysis.|
| Picture library | To share a collection of digital pictures or graphics, use a picture library. Although pictures can be stored in other types of SharePoint libraries, picture libraries have several advantages. For example, from a picture library you can view pictures in a slide show, download pictures to your computer, and edit pictures with compatible graphics programs, such as Microsoft Paint. Consider creating a picture library if you want to store pictures of team events or product launches. You can also link to pictures in your library from elsewhere on your site, such as from wikis, and blogs.|
| Record library | To keep a central repository for storing and managing your organization's records or important business documents, use a record library. For example, your organization may need to adhere to compliance regulations which require an organized process for managing pertinent documents. A Records Center site can contain a number of record libraries for storing different types of records. For each library you can set policies that determine what records to store, how to route and manage the documents, and how long these records must be retained.|
| Report library | To simplify the creation, management and delivery of web pages, documents and key performance indicators (KPI) of metrics and goals, use a report library. The report library is a central place where you can create and save reports, such as Excel workbooks, and dashboard pages. When you publish an Excel workbook to a reports library, it is single-click enabled to open in browser view, which is a convenient way to see the workbook without adding it to a Web Parts page.|
| Process Diagram Library (Metric and US Units) | To store and share diagram process documents, such as those created with Microsoft Visio, use a Process Diagram Library. The Metric and US Units libraries are tailored to their respective measurements.|
| Wiki Page Library | To create a collection of connected wiki pages, use a wiki page library. A wiki enables multiple people to gather information in a format that is easy to create and modify. You can also add wiki pages that contain pictures, tables, hyperlinks, and internal links, to your library. For example, if your team creates a wiki site for a project, the site can store tips and tricks in a series of pages that connect to each other.|



<br/>

<a id="columns" />

<br/>

## Columns

By default, libraries track the name of a file, as well as information about the status of a file, such as whether it is checked in. But, you can specify additional columns that help your group to categorize and track files, such as a campaign name or a project number, or other information that's important to your team. You have several options for the type of column that you create, including a single line of text, a drop-down list of options, a number that is calculated from other columns, or even the name and picture of a person on your site.

Columns provide column headers that make it easy for people to sort and filter documents. When you display files in a library, you can temporarily sort or filter the files by pointing to the name of a column, and then clicking the down arrow beside the name. This is helpful if you need to see the files in a certain way, but you have to repeat the steps the next time you view the library.


<br/>

**Create column**

You can add most types of columns, columns types, site column or add existing column to library.

To add a column:
1. Navigate to the list or library you want to create a column in.
1. To the right of the last column name at the top of the list or library, select **+ Add column** or **+**.

    ![Document Library Add Column](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryAddColumn.png)


    > **Note:** Does your SharePoint screen look different than the examples here? If so, select the Classic tab earlier in this article. You'll find alternate instructions there that'll match your experience better if your administrator set the classic experience on the list or document library, or if you're using an earlier version of SharePoint Server. 

1. In the dropdown, select the type of column you want.

    - Adding a column will not show all data types to view more data type select **More...**.

        | Data type | Description |
        | --- | --- | 
        | Single line of text | Used to collect and display small amounts of unformatted text in a single line (255 characters). |
        | Multiple | Used to collect and display formatted text or lengthy text and numbers on more than one line, such as a description of an item (63,999 characters).|
        | Location | Add rich location data from Bing Maps or your organization directory. |
        | Number | Used to store numerical values that aren't monetary values.|
        | Yes/No | Used to store true/false or yes/no information, such as whether someone will attend an event.|
        | Person or Group | Used to provide a searchable list of people and groups from which people can choose when they add or edit an item. |
        | Date and time | Used to store calendar dates, or both dates and times. |
        | Choice | Used to let people choose from a list of options that you provide. |
        | Hyperlink | Used to store a hyperlink to a Web page, graphic, or other resource. |
        | Currency | Used to store monetary values.|
        | Image | Use to add a single image file from your device to an item in a list or a library.|
        | Managed Metadata | Use this column type to enable site users to select values from a specific term set of managed terms and apply these values to their content. |

1. In the Create a column panel, in the Name field, enter a title or column heading.

1. Enter any other required information. The number of fields will vary with column type you choose. The above example is for a 'number' field.

1. Select Save.


<br/>

**Change a column**

You can modify the columns in lists and libraries by edit the select column. You can use the details pane or properties.

  ![Document Library Edit Column](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryEditColumn.png)


You can change the order of how columns are displayed
    - Select the heading of the column that you want to move, then drag and drop it to the appropriate location.  
    - Or you can select the down arrow Chevron icon to expand details. at the top of any column, then select Column Settings > Move Left or Move Right.

<br/>

**Change value**

Depending on the type of data a column can change the value in all documents or manually in each document.

<br/>

**Delete a column**

When you no longer need a column in a list or library, you can delete it. Or you can delete a site column from SharePoint. 

1. Go to the list or library that you want to delete a column from.
1. Or from a SharePoint site, select **Settings**, **Site Contents**, and then select the name of your list or library.
1. Select the column header for the column that you want to delete, and from the menu, select **Column settings** > **Edit**.
1. At the bottom of the Edit Column pane, select **Delete**.
1. To delete the column and the data in the column permanently, select **Delete**.




<br/>

<a id="views" />

<br/>

## Views

Will users often want to see: all the documents related to a specific project, all documents that belong to a particular department, or group the documents by the month they are due? If you expect to view the files in a certain way frequently, you can define a view. You can use this view any time that you work with the library. When you create a view, it is added to the Current Views drop-down list located in the library ribbon.

A library view is a selection of columns on a page that displays items in a library, and often defines a specific sort order, filter, grouping, and custom layout. Libraries can have personal views and public views. Anyone who has been assigned to the Members group on the site (which has the Contribute permission level) can create a personal view to see the files in a certain way or to filter for only the files that they want to see. If you have permission to design a library, you can create a public view that anyone can use when viewing the library. You can also make any public view the default view, so that people automatically see that view of the library.

If members of your group view the libraries on a mobile device, you can even create mobile views that provide limits, such as number of items displayed in a view, that are optimal for the bandwidth and limitations of the devices.


<br/>



**Create a view**

1. In the command bar of your list, select View options Lists **View Options** ![View Options Icon](https://www.rramoscabral.com/training/assets/MSSharePoint/ViewAllItems.png).

    - If View options Lists View Options isn't visible, make sure you're not editing the list or you haven't selected one or more items. Also, you may not have permission. In that case, contact the Microsoft 365 admin or the site or list owners.

1. Select Create new view.

    - **Important:** If you don't see **Create new view**, it means that the latest updates haven't reached you yet.

1. Under **View name**, enter a name for your view.
1. Under **Show as**, select **List** or **Calendar** for the type of view you want to create.
1. If you select calendar view, enter a start date and end date on the calendar.
1.  To change how the title of items appear on the calendar, select More options and then select from the **Title of items on calendar** list.
1. When you're finished, select Create.

<br/>

**change a view**

You can make some changes directly in your list view. To do this, click the column name. You can change the order of items, filter them, group them, add columns, and change other column settings. When you are finished, click View options and then click Save view as. Save the view with its current name, or enter a new name to create a new view.

<br/>


**Delete a view**

1. In the command bar of your list, select View options Lists **View Options** ![View Options Icon](https://www.rramoscabral.com/training/assets/MSSharePoint/ViewAllItems.png).

1. Select the name of the view that you want to delete.
1. Select View options again, and then select **Edit current view**.
1. On the Edit View page, select **Delete** and then select **OK**.


<br/>

<a id="alerts" />

<br/>



## Alerts

To stay updated when your Microsoft SharePoint documents or items on your site change, create alerts. You can set up an alert for a list, library, folder, file, or list item. For example, you can set up an alert for a specific folder in a library, without receiving alerts when changes occur in the rest of the library.


**Get alerts on item changes in SharePoint**

You can get an alert whenever a file, link, or folder is changed in a SharePoint document library. Depending on the item (file, folder, link), you may see different options when you set an alert.

1. Go to the list or library.
1. Select the file, link, or folder for which you want to get an alert.
1. From the list of options for the list or library, select the **... (ellipses)**, and then select **Alert Me**.
1. In the **Alert me when items change** dialog, select and change the options you want. 
1. To save, select OK.

<br/>

**Get alerts on all changes in a document library in SharePoint**

1. Go to the list or library and make sure no items are selected.
1. From the list of options for the list or library, select the **... (ellipses)**, and then select **Alert Me**.
1. In the **Alert me when items change** dialog, change or fill in the options you want.
1. Select OK.

<br/>

**Cancel alerts in SharePoint**

1. To view your alerts from a page on the site, from the list of options for the list or library, select the **... (ellipsis)**, and then select **Manage My Alert**s.
1. Select the alert that you want to delete.
1. Select **Delete Selected Alerts**.
1. To delete, select **OK**.


<br/>

<a id="file-activity-in-a-document-library" />

<br/>

## File activity in a document library

SharePoint keeps track of changes and updates of files in your library. You can see the changes that were made (created, edited, deleted) and when (18 hours ago, yesterday, last week). You can view only activity on individual files and documents, or your whole library. Activity is available for the last 60 days.


<br/>

**See the file activity in a document library**

1. Open the document library
1. Select **Open the details pane** ![Icon Details Pane](https://www.rramoscabral.com/training/assets/MSSharePoint/IconDetailsPane.png)again
1. Scan the **Activity** section to view the latest activities for your **files**
1. To close the details pane, select Open the details pane Information or Open the **details pane** ![Icon Details Pane](https://www.rramoscabral.com/training/assets/MSSharePoint/IconDetailsPane.png)again

---

<br/>

<div style="font-style: italic; text-align: center;" markdown="1">

Section: SharePoint Library

[<<  SharePoint Exercise - Create SharePoint Team Site](./SharePointExecCreateSharePointTeamSite.md) | [back to top](#top) | [Back to Table of Content](./README.md) | [ SharePoint Exercise - Create SharePoint Librarie  >>](./SharePointExecCreateSharePointLibrary.md)

</div>