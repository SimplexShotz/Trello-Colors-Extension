# Trello-Colors-Extension || ***FORK WIP***
*This fork migrates the extension to Manifest V3 in compliance with the Manifest V3 Transition Timeline.*

[See blog on developer.chrome.com for more info.](https://developer.chrome.com/blog/mv2-transition/)

## To install this extension, follow these steps:

1. Download this repository by clicking on the green button with a down arrow labeled "Code", then selecting "Download ZIP".
2. Unzip the downloaded file.
3. Head on over to "chrome://extensions".
4. Enable Developer Mode by toggling the switch in the top right corner of the extensions page.
5. Click the "LOAD UNPACKED" button in the top left corner of the extensions page, and select the unzipped folder that you downloaded in step 1.
6. Head on over to Trello, and you're all set!

## How to use the extension:

1. Head on over to [Trello](https://www.trello.com).
2. Go to create a new label for one of your cards (but don't create it yet!). You can also go to edit a pre-existing label.
3. Name the label starting with the hex color, followed by a colon, followed by the label name. For a red label named "Example", you would enter the following: **#FF0000:Example**
4. Select any color (this color will be overwritten by the extension).
5. Click "Create" or "Save".
6. You're done! The label should automatically change to the color that you set. It will stay that color, even after a page reload!

## A quick note:

To anyone not using the extension, the name will show up exactly how you entered it (with the color code in the title), and it will not have the custom color. Unfortunately, there's really no other way to store the color, aside from in the label's name, so there's not much I can do about it. Just have them install the extension too, if you really need to.
