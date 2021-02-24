# DGL 114 - Process Portfolio
## By Taiwo Adekanmbi

### Week 1 Activities
**Activity 0101**:
1. **Good app- TV Time**

    **The good**

 - Its search engine is good, not great but adds a lot of niche shows.
 <img src="Image/TV search.jpg" width=500>

- Its interface is appealing and convenient with visual display of the shows I added.
 <img src="Image/TV Watchlist.jpg" width=500>
 
- It recently added a movie list into it’s app without making a different app for movies which is convenient.  
  <img src="Image/TV Washlist1.jpg" width=500>
 
    **The bad**

- It would be nice to category my shows or movies based on genres or any headings I wanted, instead of watching, have not started, up to date, finished, stopped.

    <img src="Image/TV Genre.jpg" width=500>

2. **Difficult app-Prime Video**

    **Demerit**
- Even when you subscribe there is still ads.
- You can not select a different rotation for prime video.

 <img src="Image/Amazon Video.jpg" width=700>

- When you want to change the episode to a random episode, it is not added to the video settings, so you must go back to the beginning of the interface to do so. It only allows you to go to the immediate next episode.

<img src="Image/Amazon Setting.jpg" width=700>
 
 **Benefit**
- It gives you information and pics of the actors of each scene.
<img src="Image/Amazon Cast.jpg" width=700>
 
- It also provides a behind the scenes interview with trivia directly on the video interface.
The videos can be background play
<img src="Image/Amazon Pop.jpg" width=500>


**Activity 0102**:

- **Usable elements**
1.	Context and text should be legible and readable
2.	Generally, core content should be available without internet or with low internet connection 
3.	Screen content and transition should load quickly.
4.	Multi step task should be displayed in modal view.
5.	App should be design with the fully understanding of user in mind through research and observation.
6.	Navigation and key content should be designed for thumbs
7.	Put the key content at the foreground and the main navigation controls should be placed a more appropriate position on the device without blocking the content
8.	Make sure the touch target area is large enough to compensate for the different finger size of individuals.
9.	Display only what matters to the user while provides them with tools to do whatever they need on the app
10.	App should work well on a multiple of platform

- **Intuitive elements**
1.	Create an interface that focuses on necessary elements. Be precise and simple with your elements not scarce.
2.	Make a functional and accessible font and colour.
3.	Follow an established design specification to make the app easier to use
4.	Focus on a smooth navigation and make it touch focused by designing the interface to be big enough for users to tap
5.	Distinguish between the tappable and non-elements either by color or shape. E.g. a tappable link could be blue, while the body of content could remain black.
6.	Discovering new UI function with different icons to instinctively understand their meaning later on.
7.	Provide a short walk through and coach marks of new functions to new users or non tech savvy individual. 


**Activity 0201**:

Amino app

**Make a list of all features in your chosen app**
- android.hardware.camera
- android.hardware.location
- android.hardware.screen.portrait
- android.hardware.wifi
- android.software.backup
- android.hardware.microphone
- android.hardware.telephony

**For permissions you can check you app permission settings (whether iOS or Android) typically in the Apps** 
- Files and media
- Camera
- Contacts
- Location
- Microphone
- Telephone


**Activity 0202**:
View elements (i.e. everything you can see on screen)
- editing text widget
- view text with images
- display images
- checkboxes
- search widget
- toast bar

Model elements (i.e. all data relevant to that screen) 
- Save show, search engine

Controller elements (i.e. all the possible interactions on that screen that may modify the Model or View).
- Click, Search

**Activity 0302**:
- onClick() – When I touch the items, it moves to another layout that displays the items information, selling price, buy and cart buttons, comments
- onLongClick() – I touches and holds item to see a small menu 
- onCreateContextMenu() - This is called when a Context Menu is being built (as the result of a sustained "long click").

**Activity 0303**:

***Responsive layout grid***

- Grid consists of columns, gutters and margins. Columns, which is measured in percentage, used to position content. Gutters, which is measured by fixed values, are the space between each column. It is for dividing content. Margins are space between the content and both the left and the right edge of the screen.
- Gutter can be smaller between the columns of a layout to create an association or connection between the items/ images or larger enforce individuality between the items. Too large a gutter can prevent harmony.
- Margins can be small to provide more space for the content or large to limit the width of the content. 
- Horizontal grid can used for touch UIs that scroll horizontally and use the same elements but are horizontal.
- A breakpoint is the range of predetermined screen sizes that have specific layout requirement. Breakpoint range determines the number of columns, and recommended margins and gutters, for each display size. Which could be between 4-columns, 8-columns and 12-columns grid.
- Grids can be fluid or fixed. The UI regions, such as app bars, navigation, content areas, can be permanent, persistent or temporary. Whiteframes are structured layouts provide a framework of how the grid layout should be displayed.


**Activity 0401**:
***Implicit intents*** 
PhotoScan – Take a picture and return a scanned image  by using the ACTION_IMAGE_CAPTURE
Send an email by using the ACTION_SENDTO

**Activity 0402**:
***Summarize the differences between the use of top and bottom app bars***
- Bottom app bars are used only for mobile devices, has access to a bottom navigation drawer/ menu (not navigation bar i.e. back to home screen navigation), is not used for screens with one or no actions, generally has floating action button (FAB). The FAB can be overlapping or inset on the bottom app bar. The layout and actions of a bottom app bar can be changed to suit each screen. Menus from the bottom app bar rises from the bottom to a higher level than the bar. Bottom app bar can be overshadowed by the keyboards.  Toasts are animated vertically above a bottom app bar to avoid obstructions.

- Top app bar can transform to contextual action bar to provide contextual actions to selected items. Top app bar can be regular, prominent for longer titles or placing images, dense for desktop only, and prominent dense in height. When the screen size changes, the top bar resizes with it and the action moves in or out of the overflow menu based on the size.


**Activity 0501**:

Touch Geatures: 
* Swipe up the video is enter full screen mode. 
* Swipe down to exit full screen mode and minimize videos
* Swipe right/swipe left for skipping between videos
* Double-taps for skipping through videos
* Tap to play video
* Swipe left to remove video from history on library
* Scroll videos

Touch event:
* ACTION_DOWN
* ACTION_MOVE

**Activity 0502**:
* A dialog is a type of modal window that is at the forefront of the app content that removes ability to use its function by providing important information or asking for questions. It should be used sparingly because it is interruptive. There are 4 types: Alert dialog, Simple dialog, Confirmation dialog and Full-Screen dialog. Alert dialogs interrupt users with urgent information or action. Simple dialog shows items that requires selection. Confirmation dialog give the user the chance to make a final choice before accepting it with both confirmation and cancel button. Fulll screen dialog takes the whole screen and other dialog can appear on it only.
* With different platforms like ios and android, dialog is displayed differently at times. Dialogs are presented with a container to place the information, scrim to make the content a less focus point by covering it and express its inaccessibility, title as a brief and clear statement, supporting text and buttons. Dialog should only be scrollable when the title and buttons a pinned to their position.
* It can be dismissed with a cancel button, keyboard escape key, tapping the scrim, android back button and voiceover. Dialog enters and exit the screen through fade transition pattern. Buttons can have a confirming action placed on the right side of the screen, dismissive action paced on the left side, acknowledgement action. Dialog should have a maximum of 2 actions.

