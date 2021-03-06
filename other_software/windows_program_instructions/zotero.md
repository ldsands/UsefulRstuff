# Zotero Windows Setup

Zotero is a reference manager for Windows, MacOS and Linux.

Note: These instructions should work for Mac too.

I have also created a tutorial on how to use some aspects of Zotero that can be accessed [here](https://ldsands.github.io/Slides/main_slides/one_offs/2020_09_Levi_Sands_Ref_Man_Zotero.html#/).

## Links and Account Information

To complete the instructions to install Zotero and setup the WebDAV file syncing, you will have to follow the instructions listed below:

1. Download Zotero from [the Zotero website](https://www.zotero.org/download/)
1. Create a Zotero account [here](https://www.zotero.org/user/register/)
1. Create a pCloud account [here](https://www.pcloud.com/)
    - Alternatives to pCloud can be found [here](https://www.zotero.org/support/kb/webdav_services)

## Setup WebDAV Syncing Instructions

1. Download and install Zotero
1. Select the edit menu and then select preferences
1. Select the sync tab
1. Sign into into your Zotero account
1. In the file syncing section, select WebDAV in the dropdown menu
1. Make sure https is selected
1. In the text box add webdav.pcloud.com:443
1. Enter your pCloud username and password
1. Press OK at the bottom of the settings dialogue box
1. Click on the Green sync arrow in the upper right hand part of the Zotero window
    - Note for Windows: Syncing will fail on the first try that is normal (probably a bug) to fix this do the following:
        1. Select the edit menu and then the sync tab
        1. Reenter your pCloud password
        1. Press OK at the bottom of the dialogue box
        1. Click again on the green sync arrow
        1. Zotero should now sync correctly

## Default Zotero Preferences I Change

- Don't download website snapshots to save a lot space
    1. Under edit, then preferences select the general tab
    1. In the "file handling" section uncheck the "automatically take snapshots when creating items from web pages"
- Don't share the child notes, links and tags with shared libraries
    1. Under edit, then preferences select the general tab
    1. In the "Groups" section uncheck the "child notes", "tags" and "child links" options
- Change the default citation style to ASA 6th edition
    1. Under edit, then preferences select the cite tab
    1. In the styles section find the "American Sociological Association 6th Edition"
    1. If this option is missing you can download the CSL file from [here](https://github.com/citation-style-language/styles/blob/master/american-sociological-association.csl)
- Sometimes I like to see all of the citations within a folder and all subfolders, the show items from subcollections setting allows for this.
    - Under View select "Show Items from Subcollections"

## Main Screen Columns

- I prefer to have the columns organized in the following order:
    - Creator
    - Year
    - Attachments
    - Title
    - Extra

## Zotero plug-ins

- [for getting google scholar counts in Zotero](https://github.com/beloglazov/zotero-scholar-citations/tree/master/builds)
