# Creating a new project

The following steps will take you quickly through the process of creating a new Baselight ‘job’ and then a new scene within the job, ready to import footage and apply grades.

At this point, having launched the application, you should see the Job Manager window on the screen \(it opens automatically when the application starts up\). If you have closed the window, you can open it again by pressing WIN+J on the keyboard or by selecting Job Manager from the Views menu at the top of the main UI monitor. It should look something like the picture below.

Job Manager – actions button

Now follow these steps to create a new job:

Baselight v5 User Guide \(Linux\) - Page 11

Quick Start Importing footage Browsing and adding media using FLUX Manage

1. 1  Click on the actions button at the top of the ‘Job’ column \(the second column\) in the Job Manager.
2. 2  Select ‘New Job’.
3. 3  Enter a name for the job and press Enter. Note that in Baselight, a ‘job’ contains all the grading work you do on a single project. Note that the newly created job will appear in the Job column with its name highlighted, indicating that it is currently selected.
4. 4  Now click on the actions button at the top of the ‘Scenes’ column \(the next column along\) and select ‘New Scene’. Enter a name for the scene. In Baselight, a scene is equivalent to a single timeline – it does not imply a scene in a script for example.
5. 5  Click the Scene Template button and select FilmLight Template from the drop-down list.
6. 6  Click on the Working Format button and choose HD 1920x1080.
7. 7  Set the Working Frame Rate to match the frame rate of your intended deliverables – this would normally match the frame rate of your source material.
8. 8  Save the settings for the new scene and close the window by clicking on the Ok button.

   At this point a pop-up box may appear asking you to choose a format for the ‘Per-Job’ gallery for your new job. Galleries are used to save and recall grades – see the Galleries & Cuts View chapter for details. Simply click on the Ok button to close the box and continue.

 A new scene will now have been added to the job you created – details of the scene are displayed in the Scene Information section at the bottom of the Job Manager. Note that both the job and scene are automatically stored in the database when they are created.

9 You can now close the Job Manager window by clicking on its ‘X’ button at the top right- hand corner, or by pressing WIN+J on the keyboard.

Importing footage

Now that you have created a new, empty scene, the next step is to import the footage into the scene. Baselight can read a very wide range of media file formats including movie files and image sequences. Single image frames can also be imported if required \(most still image formats are supported\).

There are two different methods for adding media to a scene:  
  Manually browsing through source volumes and selecting the material to add.  
  Using an EDL to ‘conform’ a scene which was edited on another system such as an editing workstation.

In this chapter we will use the first method to find, select and add media to the timeline – full details of the EDL conform process can be found in the Conform & Consolidate chapter.

Browsing and adding media using FLUX Manage

Baselight v5 User Guide \(Linux\) - Page 12

Quick Start Importing footage Browsing and adding media using FLUX Manage

The following example assumes that you already have the tutorial footage on your local media RAID, if not, you will need to copy the media over first. If your system does not have any local media storage, or you would prefer to work with media stored on a remote or external volume, then this is also possible \(see the note boxes in this section\). The following steps use FLUX Manage, Baselight’s built-in media management tool:

1 Open FLUX Manage by selecting it from the Views menu at the top of the screen, or by pressing WIN+B on the keyboard.

 The FLUX Manage window will open showing a ‘Browser 1’ tab – similar to the picture below. For a more detailed description of this window please see the FLUX Manage chapter.

Volume selector Browser area

Current path button Bookmark button Information area

Grid and List View Thumbnail grid buttons.

Selected shot\(s\) Input format Preview buttons Append button

FLUX Manage

Baselight v5

User Guide \(Linux\) - Page 13

Quick Start Importing footage Browsing and adding media using FLUX Manage

1. 2  Click on the volume selector button to view a drop-down list of all the storage volumes which your Baselight system can access. If your system has local RAID storage this will appear as a volume pre-fixed with the machine name, for example ‘bl01234-images’.

   If your footage is on remote storage such as a SAN or NAS, then the shared volume will also appear in the drop-down list as long as the system has been configured correctly. Note also, that any portable drives plugged into the Baselight system will also appear in this list – please see the Media & Metadata chapter for full details.

2. 3  Select the volume containing the tutorial footage by clicking on it in the list.

 The contents of the volume will be listed in the left-hand column, similar to the example

above.

4 Click on the ‘tutorials’ folder and then on the ‘quick-start’ folder.

 A list of the media files contained in the folder will appear in the main part of the browser window and thumbnails or details will appear in the lower part of the window \(depending on the setting of the grid and list view buttons\).

If you have downloaded the tutorial footage and want to copy it onto the local Baselight storage you can use the copy tool built into FLUX Manage – instructions are included on page 15. Note that this is the preferred way to copy media onto the internal storage as the FLUX Manage tools have been optimised for copying large media files and sequences efficiently while avoiding fragmentation of the file system.

5 Click on the Grid view button \(see page 151\) to display thumbnails for the media files and then click on one of the thumbnails.

 The outline of the thumbnail will turn yellow to indicate that it is selected and metadata and other details will appear in the metadata area in the FLUX Manage window. Multiple shots can be selected by holding down CTRL and clicking on additional shots to add them to the selection. Note that when multiple shots are selected, summary details will be shown in the metadata area.

6 Click on the first thumbnail to select it, then hold down the SHIFT key and click on the last thumbnail.

 This will add all the shots to the selection.  
 Baselight provides several other methods for selecting and de-selecting a group or

range of shots – please see the FLUX Manage chapter for details.

Baselight v5 User Guide \(Linux\) - Page 14

Quick Start Importing footage Using FLUX Manage to copy footage

1. 7  Click on the List view button and then click on the Filename column heading to sort the list of shots into ascending filename order – the sort order is indicated by a downwards pointing arrowhead to the right of the column heading.
2. 8  Finally, click on the Insert Shots At Cursor button at the bottom right-hand corner of the FLUX Manage window.

 The selected shots will be added to the scene and will appear in the Timeline.  
 9 The FLUX Manage window can now be closed by clicking on its ‘X’ button. You can also

toggle the window open and closed using the WIN+B keyboard shortcut. Using FLUX Manage to copy footage

As mentioned above, FLUX Manage provides tools to copy media between different folders and volumes. If your footage is on a portable drive or a networked storage volume, you can copy it to the local storage on your Baselight system by following the steps below.

1. 1  If you have already added media to your scene from a portable or remote volume you should remove it first to avoid confusion. This can be done now simply by pressing CTRL+Z on the keyboard to undo the last action \(which was to add the media to the scene\).
2. 2  Open FLUX Manage again and select the media you want to copy \(the shots may still be selected from the previous steps\).
3. 3  Click on the ‘Two panes’ button at the top right corner of the FLUX Manage window:  
    Two panes

   button

   FLUX Manage – Two panes button

 A second browser section will open on the right side of the FLUX Manage window with a ‘Browser 2’ tab selected.

4 Click on the volume selector button on the right-hand side under the Browser 2 tab and select the internal storage – this will normally be listed as something like ‘bl0123-images’ or ‘Local filesystem’, but the actual volume name will depend on the system configuration.

Baselight v5 User Guide \(Linux\) - Page 15

Quick Start Playing back the scene Using FLUX Manage to copy footage

1. 5  Browse to the directory into which you want to copy the footage – if necessary you can create a new directory by clicking on the Create folder button:

   Create folder button

   FLUX Manage – Create folder button

2. 6  To copy the shots you selected on the left-hand side, simply click-and-drag them across to the appropriate directory on the right.A green outline will appear indicating the destination into which the files will be copied.
3. 7  As soon as you release the mouse button, or lift up the tablet pen, a ‘Copy Options’ dialogue box will appear. For the purposes of this exercise you can simply click on the Ok button, but for an explanation of the options available please refer to Copying Media in the FLUX Manage chapter.

 The copy process will be added to the Baselight system’s media processing queue and will appear in the Operation History section of the FLUX Manage window along with a bar showing its progress.

1. 8  Once the copy process has completed you can switch back to the single pane FLUX Manage view by clicking on the button on the left of the two panes button.
2. 9  Now that the media files are on the local storage you need to select the local storage volume in the ‘Browser 1’ tab and browse to their location.
3. 10  Follow the steps on page 14 to select the tutorial footage from its new location on the local image storage and then add it to the scene.

Playing back the scene

Before continuing, please switch to the ‘Simple’ Workspace by selecting it from the Views menu at the top of the screen or by pressing WIN+2 on the keyboard.

Baselight v5 User Guide \(Linux\) - Page 16

Quick Start Playing back the scene Navigation controls

To start playing back the shots in your scene simply press the Space bar on the keyboard or, if you have a control panel connected, press the play button \(note that Baselight CONFORM and Baselight ASSIST do not support hardware control panels\). Pressing Space or the play button again will stop playback.

By default, Baselight automatically sets the colour space for each shot when it is imported. If a shot appears very washed out or has too much contrast then this is most likely because it has been tagged with the wrong input colour space. You can easily change the input colour space of shots after they have been imported – please see the section on modifying sequence operator parameters on page 115 and also the chapter on Colour Space Management.

Navigation controls

You can jump from one shot to the next by pressing X on the keyboard; pressing Z will jump back to the previous shot. When playback is stopped, the left and right arrow keys on the keyboard will step forwards and backwards through the shot by single frames. Pressing CTRL+Home will take you right back to the first frame in the scene and CTRL+End will jump to the very end of the scene.

Several other keyboard shortcuts are available to navigate through the scene as well as for many other functions within Baselight – details can be found in the Keyboard Shortcuts document under the Help menu at the top of the Baselight user interface screen.

A set of on-screen navigation controls are also provided in the Play Controls view:

On-screen Play Controls

Play options button

If you cannot see the on-screen play controls within your UI screen workspace, switch to the ‘Simple’ Workspace under the Views menu at the top of the screen.

Enabling the counter overlay

While playing back your shots, it is often useful to be able to view information related to the footage. Baselight provides an overlay which displays certain metadata within the image display. To enable the overlay function, press K on the keyboard or enable the Show Counters button in the Cursors view. Note that if the cursors view is not currently visible, it can be opened as a window by selecting it from the Views menu.

Baselight v5 User Guide \(Linux\) - Page 17

Quick Start Playing back the scene Navigating using the mouse

 A set of default counters including the shot timecode and tape ID will be displayed. Other metadata can be added to the overlay using the options in the cursors view – see the section on cursors \(page 276\) for details.

Navigating using the mouse

The mouse \(or tablet pen\) can be used to quickly jump to a specific shot or to drag through shots to locate a specific frame:

1. 1  Open the Shots view from the Views menu at the top of the screen or using the WIN+H keyboard shortcut. Note that if the current UI workspace already includes the Shots view it will be briefly outlined with a yellow glow to show you where it is.
2. 2  Switch the Shots view to display a thumbnail grid by clicking on the button at the top.
3. 3  To jump directly to a shot, simply click on its thumbnail in the Shots view – the main image display will switch to showing the selected shot. Note that you can do this without stopping playback; Baselight will continue to play back from the shot you clicked on.
4. 4  To drag through the frames of a shot, move the mouse pointer towards the top edge of its thumbnail until you see a yellow scrub bar appear:

   Scrub bar

   Thumbnail scrub bar

   Click and drag to the left and right to scrub through the shot – the frames will appear on the main image display.

5. 5  To drag through the entire scene, click on the top of the cursor and drag it along the timeline:

Timeline cursor

Timeline cursor scrubbing

The Cuts View can also be used to navigate through the shots in a scene – this and other functions of the Cuts View are covered in the Galleries & Cuts View chapter.

Baselight v5 User Guide \(Linux\) - Page 18

Quick Start Applying basic grades Zooming and panning with the mouse

Zooming and panning with the mouse

The mouse \(or tablet pen\) can be used to zoom the image or timeline: position the pointer over the image display or timeline, press and hold both the CTRL key on the keyboard and the middle mouse button \(or lower side-switch on the pen\) and then drag to the left or right.

 The image or timeline will zoom out or in respectively. Note that if you are zooming the timeline, it will zoom horizontally with left/right movements of the mouse and vertically with up/down movements.

To pan the image display or timeline, the mouse or pen action is the same as zooming, except you only hold down the middle mouse button \(or lower pen side-switch\) while dragging – you do not hold the CTRL key.

To reset the image display zoom and pan, press F12 on the keyboard; to reset the horizontal zoom of the timeline, press F7 \(the timeline will zoom to fit the entire scene\); to reset the vertical zoom of the timeline, press SHIFT+F7.

For more details about zooming and panning the display, please refer to the UI & Workspaces chapter.

