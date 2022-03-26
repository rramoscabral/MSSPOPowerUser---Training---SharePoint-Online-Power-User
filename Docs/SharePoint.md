<a id="top" />

# SharePoint

![Logo](https://www.rramoscabral.com/training/assets/logos/MSSharePoint.png) 


Organizations usually have an Intranet, which is an internal site that contains digital services, documentation, and organization tools for better internal communication. To access externally, an Extranet is used, which provides secure and controlled access to the organization's Intranet. 

One of the tools available to create these sites is through SharePoint. This makes it possible to create, share, organize, and discover information inside and outsidethe company.


<br/>

## SharePoint Online VS SharePoint on-premises VS  SharePoint Hybrid

Organizations can choose to have the SharePoint environment in a variety of ways such as on-premises, online or hybrid.
- SharePoint Online is a hosted solution that you can get by itself or with a Microsoft 365 subscription. 
- SharePoint Server (on-premises) is an on-premises solution.
- SharePoint Hybrid is enables users in SharePoint on-premises to take advantage of SharePoint Online functionality. 



With SharePoint Server hybrid, productivity services in SharePoint in Microsoft 365 can be integrated with on-premises SharePoint Server to provide unified functionality and access to data. For enterprises that want to gradually move their existing on-premises SharePoint Server services to the cloud, SharePoint Server hybrid provides a staged migration path by extending high-impact SharePoint Server workloads to SharePoint in Microsoft 365.

A SharePoint Server hybrid environment enables trusted communications between SharePoint in Microsoft 365 and SharePoint Server. When you have established this trust framework, you can configure integrated functionality between services and features such as Search, Follow, and user profiles.

<br/>

## What is SharePoint Site

Organizations use Microsoft SharePoint to create websites and all you need is a web browser, such as Microsoft Edge, Google Chrome, or Firefox.


![SharePoint Site](https://www.rramoscabral.com/training/assets/MSSharePoint/ModernSite_002.png) 


A SharePoint site it is just reguler website that can have one or more pages to display content from SharePoint components named **SharePoint Web Parts**. 

SharePoint Web Parts can be: 
- Bing maps, adds a map to your page.
- Button, easily adds a button to your page with your own label and link.
- Call to Action, creates a button with a call to action for users.
- Code snippet, easily displays code as text on your page for others to use or learn from.
- Connectors, you can get messages, alerts, and notifications from your favorite external services on a group-connected team site page.
- Countdown timer, displays a count down (or count up) to an event.
- Divider, inserts a line between other web parts to help break up your page and make it easier to read.
- Document Library, displays a document library and customize it with your own title, view, and even size. 
- Embed, displays content on your page from other sites like YouTube videos.
- Events, allows you to add and display upcoming events on your page. 
- File viewer, insert a files on your page. File types you can insert include Excel, Word, PowerPoint, Visio, .PDFs, 3D Models, videos, and more.
- Group calendar, puts a group calendar right on your page so that it is easily visible to your readers.
- Hero, is a great way to bring focus and visual interest to your page. 
- Highlighted content, dynamically displays content based on content type (documents, pages, news, videos, images, etc), filtering, or a search string.
- Image, inserts an image on the page, either from your site, your OneDrive, or your hard drive.
- Image Gallery, shares collections of pictures on a page. 
- Kindle Instant Preview, shares a preview of a Kindle book.
- Link, adds a link to an internal or external page, video, image, or document.
- List, displays a list that you can customize with your own title, view, and even size. 
- List properties, connects to a list web part on the same page and display items from the list based on what a user selects.
- Markdown, adds text to your page and format it using Markdown language.
- Microsoft Forms, can create surveys, quizzes, and polls on a page. 
- My feed, shows a mix of content from across Microsoft 365, based on what's likely to be most relevant to the current user at any given time.
- News, keeps your team in the loop as well as engages them with important or interesting stories.
- Organization chart, show a visual organization chart by choosing a person to build the chart around. 
- Page properties, provides details about your page, such as title, date, content type, and more.
- Planner, adds your team's tasks and assignments on a page using Microsoft Planner.
- PowerApps, is a service that lets you build business apps that run in a browser or on a phone or tablet, with no coding experience required.
- Power BI, easily embeds an interactive Power BI report on your page. The embedded reports are fully secure so you can easily create secure internal portals.
- Quick Chart, adds simple charts to your page. 
- Quick Links, "pins" items to your page for easy access.
- Recent documents, displays documents that have been recently added or edited.
- Saved for later, users can "save" pages, news posts, and documents to view later in SharePoint. 
- Site activity, automatically shows recent activity on your site, such as files uploaded, edits made, lists and libraries created, and so on.
- Sites, showcases sites on a page. 
- Spacer, allows you to control vertical space on your page.
- Stream (classic), displays a video right on your page from your organization's Microsoft Stream (classic) video portal.
- Text, adds paragraphs and tables to your page. Formatting options like styles, bullets, indentations, highlighting, and links are available.
- Twitter, shows tweets that are relevant to you or your audience right on your page.
- Weather, shows the current weather on your page.
- World clock, hows the time in different locations around the world.
- Yammer web part enhances collaboration by embedding Yammer conversations on your page.
- YouTube, easily embeds YouTube videos right on your page.








SharePoint Site Collection, just as the name implies, is a collection of SharePoint Sites. Each site collection contains a single top-level site and subsites below it.





<br/>

## Classic Sites vs Modern Sites


| Classic Sites | Modern Sites |
| --- | --- |
| ![Classic Site](https://www.rramoscabral.com/training/assets/MSSharePoint/ClassicSite.png) | ![Modern Site](https://www.rramoscabral.com/training/assets/MSSharePoint/ModernSite.png) 
| Great for people already working with SharePoint locally or online | Great for people who have never worked with SharePoint Online |
| Uses a classic environment | Uses a modern environment |
| Inlcude all the web parts from SharePoint | Inlcude: <br/> - Libraries<br/> - Pages<br/> - Site Contents | 


There are not many differences between the classic site and the Modern site although the homepage, term definition and libraries are different.

The default SharePoint modern site is currently set but Microsoft 365 administrators are still able to create a SharePoint classic site but the result will be half of the features are in classic site and the rest in modem site. Which means it's kind of a mixture of both and it can be extremely challenging.



<br/>

# Limitations of file names and file types


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


<br>

## SharePoint mobile App

Get your intranet in your pocket with the SharePoint mobile app.  With easy on-the-go access, the SharePoint mobile app helps keep your work moving forward by providing quick access to your team sites, organization portals and resources, and the people you work with. You can see site activities, get quick access to recent and popular files, and view and edit lists on your team sites.

SharePoint mobile App is available on the following platforms:
- [Google Play Store](https://play.google.com/store/apps/details?id=com.microsoft.sharepoint)
- [Apple App Store](https://apps.apple.com/us/app/microsoft-sharepoint/id1091505266)
- [Microsoft Store for Windows 10 Mobile](https://www.microsoft.com/en-us/p/sharepoint/9nblggh510hb?rtc=1&activetab=pivot:overviewtab)


When you launch the SharePoint app, you might be asked to add an account. Adding a SharePoint account to SharePoint for Android follows the same steps as signing in to Microsoft 365. If this is your first time signing in to Microsoft 365, you can read more in Where to sign in to Microsoft 365.

More help for SharePoint for Android or IOS
 - Ask your question in the [SharePoint Android Community](https://answers.microsoft.com/en-us/msoffice/forum/msoffice_sharepoint-mso_amobile) or 
 - Ask your question in the [SharePoint iOS Community](https://answers.microsoft.com/en-us/msoffice/forum/msoffice_sharepoint-mso_imobile)











 
You can download Microsoft SharePoint Online Quick Start Guide [**here**](https://download.microsoft.com/download/C/3/4/C3468197-CE05-4738-A1D4-707B4738723A/SPO%20QS.pdf)




<br/>

---

<br/>

<div style="font-style: italic; text-align: center;" markdown="1">

Section: SharePoint

[<< Microsoft 365 Group](./Microsoft365Group.md) | [back to top](#top)  | [SharePoint >>](./SharePoint.md)

</div>