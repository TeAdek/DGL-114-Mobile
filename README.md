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


# SECOND HALF

**Activity 0801**: 

***Instagram***

* Shared Preferences -Store preferred themes, notification of what the people you follow post
* App-specific files - Store pictures and videos taken with Instagram camera.
* Shared storage - Store screenshots of Instagram pictures to be shared with other social media app
* Database - Store link visited, average time spent on the Instagram
* Cloud - Store liked posts, picture, video, user profile and saved posts

**Activity 0802**:
* Shared Preferences - Store app settings like preferred theme, preferences, language choice, notification on what you going to do with your list
* Cloud – store list to be accessible to other members of the app
* Database - store list
*Shared Storage - store accompished list/goals to be shared on other apps


**Activity 0901**:

Room persistence library provides an abstraction layer over SQLite and used to write simpler code to interact with a SQLite database. Three major components in Room are Database class, Entity, Data access objects. Database class is an abstract class that extends RoomDatabase and provides DAOs for accessing the SQLite database, annotated with @Database. Room.databaseBuilder() stores the SQLite database in the given filename. allowMainThreadQueries() method allows the Room database methods to be called on the main thread, which greatly simplifies the code. build() method creates and initializes the database.

Data entities are tables in your app database, annotated with @Entity. Annotations for the entity’s field are @PrimaryKey, @NonNull, @ColumnInfo, @ForeignKey. Data access objects (DAO) is methods for selecting, inserting, updating, deleting data in the database, annotated with @Dao. Annotations for Dao are @Query, @Insert, @Update, @Delete.

**Activity 0902**:

Fragment is a modular section of an activity, which is a UI component that you can reuse. It has it’s own layout, lifecycle and input events. To create a fragment, add dependencies on the AndroidX Fragment library in your app’s build.grade file. 
```
dependencies {
    def fragment_version = "1.3.2"

    // Java language implementation
    implementation "androidx.fragment:fragment:$fragment_version"
    // Kotlin
    implementation "androidx.fragment:fragment-ktx:$fragment_version"
}
```
Extend the AndroidX Fragment class with your app’s logic inputed to the method.
```
class ExampleFragment extends Fragment {
    public ExampleFragment() {
        super(R.layout.example_fragment);
    }
}
```
add a fragment to your activity layout's XML, use a FragmentContainerView element
```
<!-- res/layout/example_activity.xml -->
<androidx.fragment.app.FragmentContainerView
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:id="@+id/fragment_container_view"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:name="com.example.ExampleFragment" />
```

**Activity 01002**:

The notification needs to be well-written, appealing, of fewer words and add value to the user. How do I narrow the number of notification I push to audience without encouraging them to turn it off completely. 

According to the survey, receiving between 2 and 5 messages in one week would cause 46% of respondents to disable push notifications. 32% of respondents said they would stop using the app altogether if they received between 6 and 10 messages in a week’s time. It is important to not bombard the user with push messages, so it is vital for an app to determine the threshold that best suits their users.

I want the notification to have the right balance of being engaging, informative, timely, personal, actionable and retain more of my users. It should encourage the user to continue to use the app and remind them that they have it in their phone.


**Activity 01003**:

Notifications provide short, timely, and relevant information about your app when it’s not in use. It shouldn’t be used for cross promotion, unopened app, requesting to rate app, errors that the app can fix itself, worthless information. Android requires the user to be made aware of foreground services which are non dismissible but can be stopped. Notification has header area with app icon, app name, header text (optional), timestamp(optional), expand indictor. Its content area has content title, content text and large icon(optional). When expanded, the notification displays up to three action at the bottom. Notification is added to the notification drawer, indicated in the status bar as an icon, which may come with sound or vibrate and show a peek to grab the user attention. 

The user can tap on the notification to move to the app, see an expanded view, dismiss it if permitted by swiping left or right, control notification by touching and holding a notification or swiping the notification and tapping the settings icon. Multiple notifications can be displayed in summary or group. More information is displayed through expanded view. A notification can provide up to 3 actions when expanded, but should not be what happens when you tap on the notification body.


**Activity 01101**:
Frame-by-frame animation | Tween animation | Property animation
-------------------------|-----------------|--------------------
 a series of images in quick succession is used to give the illusion of movement|a series of transformations (rotation, translation, scaling, etc.) is done on an object over time so the object appears to be rotating, moving, growing or shrinking, etc|a property of an object is changed over a fixed length of time using classes in the android.animation package


**Activity 01103**:

Motion can be used to educate, visual expression, entertain and bring attention to something. It shows how elements relate from hierarchy of parent and child element, position to relationship between similar items. It gives style and personality to a brand through customized transition. It can make a icon and illustrator playful, sophisticated, informative, emphasize on a point. It gives feedback on what the action of a user or system. It educates the user on what to do.


