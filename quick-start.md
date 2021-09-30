# Quick Start

## Overview

This chapter provides a brief operational overview of Baselight. It is intended as a way to quickly get you up and running, so if you are testing a newly installed system or just eager to get going, then this is a good place to start.

In order to follow the examples, you will need to have access to the ‘Quick Start’ tutorial media files – these will have been copied onto your system if it was shipped with pre-configured internal storage, however they can also be downloaded from the training section of our website. If you are downloading the media, please follow the instructions in this chapter for details of how to copy the tutorial media into the appropriate location onto your system.

As this is just a brief introduction to Baselight we won’t be going into much detail, but all the main workflow steps will be covered in the following topics:


--0-- 
이미지 삽입
--0-- 





## Starting up the system

If your Mac is set up with multiple users, please make sure you are logged in as the correct user before starting the application software as this may affect the access you have to certain files and directories on your system.

* Running the Baselight application

The application is launched from the icon which can be found in the Baselight folder in Applications.

-> While the software is loading, a splash screen will appear giving you the current software build number.

₩₩₩₩ 
Note that if the software licence has not yet been installed or activated you will be presented with a pop-up licence dialogue box. Please refer to Appendix 40 - Software installation & activation for details of installing or updating the application software and activating the licence.
₩₩₩₩ 



Once the application has launched you will see a default workspace displayed in the Baselight user interface and the Job Manager opened as a floating window. If your system includes a grading control panel then it should also have been initialised and you should see appropriate labels on its buttons and screens.

## Creating a new project

The following steps will take you quickly through the process of creating a new Baselight ‘job’ and then a new scene within the job, ready to import footage and apply grades.

At this point, having launched the application, you should see the Job Manager window on the screen \(it opens automatically when the application starts up\). If you have closed the window, you can open it again by

pressing CTRL+J on the keyboard or by selecting Job Manager from the Views menu at the top of the main UI monitor – it should look something like the picture below.


₩₩₩₩₩₩₩₩ 
이미지 삽입
₩₩₩₩₩₩₩₩





Now follow these steps to create a new job:

1. Click on the actions button at the top of the ‘Job’ column \(the second column\) in the Job Manager.
2. Select ‘New Job’.
3. Enter a name for the job and press Enter. Note that in Baselight, a ‘job’ contains all the grading work you do on a single project -> the newly created job will appear in the Job column with its name highlighted, indicating that it is currently selected.
4. Now click on the actions button at the top of the ‘Scenes’ column \(the next column along\) and select ‘New Scene’. Enter a name for the scene. In Baselight, a scene is equivalent to a single timeline – it does not imply a scene in a script for example.
5. Click the Scene Template button and select FilmLight Template from the drop-down list.

₩₩₩₩₩
   Scene Templates provide a way to create a new scene with various parameters and settings already configured. You don’t have to start a new scene using a template but it is a good idea as it leads to consistency between scenes and can save a lot of time setting individual parameters.

₩₩₩₩₩



6. Click on the Working Format button and choose HD 1920x1080.
7. Set the Working Frame Rate to match the frame rate of your primary deliverables – this would normally also match the frame rate of your source material.
8.  Save the settings for the new scene and close the window by clicking on the Ok button.

₩₩₩₩₩₩
      At this point a pop-up box may appear asking you to choose a format for the ‘Per-Job’ gallery for your new job. Galleries are used to save and recall grades – see the Galleries & Cuts View chapter for details. Simply click on the Ok button to close the box and continue.
₩₩₩₩
    -> A new scene will now have been added to the job you created – details of the scene are displayed in the Scene Information section at the bottom of the Job Manager. Note that both the job and scene are automatically stored in the database when they are created.

   9. You can now close the Job Manager window by clicking on its ‘X’ button at the top right- hand corner, or by pressing CTRL+J on the keyboard.







## Importing footage

Now that you have created a new, empty scene, the next step is to import the footage into the scene. Baselight can read a very wide range of media file formats including movie files and image sequences. Single image frames can also be imported if required \(most still image formats are supported\).

There are two different methods for adding media to a scene:  
 *Manually browsing through source volumes and selecting the material to add.  
 *Using an EDL to ‘conform’ a scene which was edited on another system such as an editing workstation.

In this chapter we will use the first method to find, select and add media to the timeline – full details of the EDL conform process can be found in the Conform & Consolidate chapter.

### Browsing and adding media using FLUX Manage



The following example assumes that you already have the tutorial footage on your local media RAID, if not, you will need to copy the media over first. If your system does not have any local media storage, or you would prefer to work with media stored on a remote or external volume, then this is also possible \(see the note boxes in this section\). The following steps use FLUX Manage, Baselight’s built-in media management tool:

1. Open FLUX Manage by selecting it from the Views menu at the top of the screen, or by pressing CTRL+B on the keyboard.

 -> The FLUX Manage window will open showing a ‘Browser 1’ tab – similar to the picture below. For a more detailed description of this window please see the FLUX Manage chapter.

2.  Click on the volume selector button to view a drop-down list of all the storage volumes which your Baselight system can access. If your system has local RAID storage this will appear as a volume pre-fixed with the machine name, for example ‘bl01234-images’.

₩₩₩₩₩
   If your footage is on remote storage such as a SAN or NAS, then the shared volume will also appear in the drop-down list as long as the system has been configured correctly. Note also, that any portable drives plugged into the Baselight system will also appear in this list – please see the Media & Metadata chapter for full details.
₩₩₩₩₩


3.  Select the volume containing the tutorial footage by clicking on it in the list.

-> The contents of the volume will be listed in the left-hand column, similar to the example

above.  
4. Click on the ‘tutorials’ folder and then on the ‘quick-start’ folder.







 -> A list of the media files contained in the folder will appear in the main part of the browser window and thumbnails or details will appear in the lower part of the window \(depending on the setting of the grid and list view buttons\).

₩₩₩₩₩
If you have downloaded the tutorial footage and want to copy it onto the local Baselight storage you can use the copy tool built into FLUX Manage – instructions are included on page 15. Note that this is the preferred way to copy media onto the internal storage as the FLUX Manage tools have been optimised for copying large media files and sequences efficiently while avoiding fragmentation of the file system.
₩₩₩₩₩



5.  Click on the Grid view button \(see page 161\) to display thumbnails for the media files and then click on one of the thumbnails.

-> The outline of the thumbnail will turn yellow to indicate that it is selected and metadata and other details will appear in the metadata area in the FLUX Manage window. Multiple shots can be selected by holding down CMD and clicking on additional shots to add them to the selection. Note that when multiple shots are selected, summary details will be shown in the metadata area.

6 Click on the first thumbnail to select it, then hold down the SHIFT key and click on the last thumbnail.

-> This will add all the shots in between to the selection and outline them all in yellow. 

₩₩₩₩₩
Baselight provides several other methods for selecting and de-selecting a group or range of shots – please see the FLUX Manage chapter for details.
₩₩₩₩

7.  Click on the List view button and then click on the Filename column heading to sort the list of shots into ascending filename order – the sort order is indicated by a downwards pointing arrowhead to the right of the column heading.
8.  Finally, click on the Insert n Sequences At Cursor button at the bottom right-hand corner of the FLUX Manage window.

-> The selected shots will be added to the scene and will appear in the Timeline.  
9. The FLUX Manage window can now be closed by clicking on its ‘X’ button. You can also toggle the window open and closed using the CTRL+B keyboard shortcut.







### Using FLUX Manage to copy footage

As mentioned above, FLUX Manage provides tools to copy media between different folders and volumes. If your footage is on a portable drive or a networked storage volume, you can copy it to the local storage on your Baselight system by following the steps below.

1. If you have already added media to your scene from a portable or remote volume you should remove it first to avoid confusion. This can be done now simply by pressing CMD+Z on the keyboard to undo the last action \(which was to add the media to the scene\).
2. Open FLUX Manage again and select the media you want to copy \(the shots may still be selected from the previous steps\).
3. Click on the ‘Two panes’ button at the top right corner of the FLUX Manage window: 
   -> A second browser section will open on the right side of the FLUX Manage window with a ‘Browser 2’ tab selected.

4.  Click on the volume selector button on the right-hand side under the Browser 2 tab and select the internal storage – this will normally be listed as something like ‘bl0123-images’ or ‘Local filesystem’, but the actual volume name will depend on the system configuration.
5.  Browse to the directory into which you want to copy the footage – if necessary you can create a new directory by clicking on the Create folder button:





6.  To copy the shots you selected on the left-hand side, simply click-and-drag them across to the appropriate directory on the right.A green outline will appear indicating the destination into which the files will be copied.
7.  As soon as you release the mouse button, or lift up the tablet pen, a ‘Copy Options’ dialogue box will appear. For the purposes of this exercise you can simply click on the Ok button, but for an explanation of the options available please refer to Copying Media in the FLUX Manage chapter.

 -> The copy process will be added to the Baselight system’s media processing queue and will appear in the Operation History section of the FLUX Manage window along with a bar showing its progress.

8.  Once the copy process has completed you can switch back to the single pane FLUX Manage view by clicking on the button on the left of the two panes button.
9.  Now that the media files are on the local storage you need to select the local storage volume in the ‘Browser 1’ tab and browse to their location.
10.  Follow the steps on page 14 to select the tutorial footage from its new location on the local image storage and then add it to the scene.





## Playing back the scene

Before continuing, please switch to the ‘Standard’ Workspace by selecting it from the Views menu at the top of the screen or by pressing CTRL+SHIFT+1 on the keyboard.

To start playing back the shots in your scene simply press the Space bar on the keyboard or, if you have a control surface connected, press the play button \(note that Baselight CONFORM and Baselight ASSIST do not support hardware control panels\). Pressing Space or the play button again will stop playback.


`````
By default, Baselight automatically sets the colour space for each shot when it is imported. If a shot appears very washed out or has too much contrast, this is most likely because there was no colour space information in the media file and it has been tagged with the wrong input colour space. You can change the input colour space of shots after they have been imported – please see the section on modifying sequence operator parameters on page 115 and also the chapter on Colour Space Management.
`````




### Navigation controls

You can jump from one shot to the next by pressing X on the keyboard; pressing Z will jump back to the previous shot. When playback is stopped, the left and right arrow keys on the keyboard will step forwards and backwards through the shot by single frames. Pressing CMD+Home will take you right back to the first frame in the scene and CMD+End will jump to the very end of the scene.

Several other keyboard shortcuts are available to navigate through the scene as well as for many other functions within Baselight – details can be found in the Keyboard Shortcuts document under the Help menu at the top of the Baselight user interface screen.









A set of on-screen navigation controls are also provided in the Play Controls view:

On-screen Play Controls

Play options button

If you cannot see the on-screen play controls within your UI screen workspace, switch to the ‘Simple’ Workspace under the Views menu at the top of the screen.

### Enabling the counter overlay

While playing back your shots, it is often useful to be able to view information related to the footage. Baselight provides an overlay which displays certain metadata within the image display. To enable the overlay function, press K on the keyboard or enable the Show Counters button in the Cursors view. Note that if the cursors view is not currently visible, it can be opened as a window by selecting it from the Views menu.

 -> A set of default counters including the shot timecode and tape ID will be displayed. Other metadata can be added to the overlay using the options in the cursors view – see the section on cursors \(page 276\) for details.

### Navigating using the mouse

The mouse \(or tablet pen\) can be used to quickly jump to a specific shot or to drag through shots to locate a specific frame:

1. Open the Shots view from the Views menu at the top of the screen or using the CTRL+H keyboard shortcut. Note that if the current UI workspace already includes the Shots view it will be briefly outlined with a yellow glow to show you where it is.
2. Switch the Shots view to display a thumbnail grid by clicking on the button at the top.
3. To jump directly to a shot, simply click on its thumbnail in the Shots view – the main image display will switch to showing the selected shot. Note that you can do this without stopping playback; Baselight will continue to play back from the shot you clicked on.



4.  To drag through the frames of a shot, move the mouse pointer towards the top edge of its thumbnail until you see a yellow scrub bar appear:

   Scrub bar

   Thumbnail scrub bar

   Click and drag to the left and right to scrub through the shot – the frames will appear on the main image display.

5.  To drag through the entire scene, click on the top of the cursor and drag it along the timeline:

Timeline cursor

Timeline cursor scrubbing

````
The Cuts View can also be used to navigate through the shots in a scene – this and other functions of the Cuts View are covered in the Galleries & Cuts View chapter.
````
### Zooming and panning with the mouse

The mouse \(or tablet pen\) can be used to zoom the image or timeline: position the pointer over the image display or timeline, press and hold both the CMD key on the keyboard and the middle mouse button \(or lower side-switch on the pen\) and then drag to the left or right.

 -> The image or timeline will zoom out or in respectively. Note that if you are zooming the timeline, it will zoom horizontally with left/right movements of the mouse and vertically with up/down movements.

To pan the image display or timeline, the mouse or pen action is the same as zooming, except you only hold down the middle mouse button \(or lower pen side-switch\) while dragging – you do not hold the CMD key.







To reset the image display zoom and pan, press F12 on the keyboard; to reset the horizontal zoom of the timeline, press F7 \(the timeline will zoom to fit the entire scene\); to reset the vertical zoom of the timeline, press SHIFT+F7.

For more details about zooming and panning the display, please refer to the UI & Workspaces chapter.

## Applying basic grades

Now that you have organised all the shots in your scene you are ready to start applying colour grades to your shots. However, before proceeding, there are a couple of things you should check to ensure that the colours you are seeing on your grading display accurately reflect the actual colours you are working with.

### Checking the colour space journey

Baselight uses a fully colour-managed image processing pipeline which means it is important that the correct colour spaces are specified at different points in the system. As has already been mentioned, the input colour space for each media file is set automatically when it is added to a scene. The other colour space settings will have also been set automatically according to the template you used when you created the new scene \(see page 11\). Before starting to grade, you should check they are correct. The simplest way to do this is to open the Colour Space Journey view – select it from the Views menu at the top of the screen or press SHIFT+CTRL+J on the keyboardThe window will open as shown in the example below:

### Colour Space Journey view

A more detailed explanation of the different steps in this ‘journey’ is provided later in this manual and advanced information is also available in the documentation and video tutorials on the FilmLight website; however there are a couple of things you should note:

 -> The Working Colour Space defines the colour space within which the grading controls will operate. In this example it was set automatically by the ‘FilmLight’ scene template. For the purposes of this example there is no need to change this but you may choose to grade in a different colour space if you prefer. It can be changed on the Format & Colour page of the Scene Settings view \(accessed from the Views menu or by pressing CMD+S\).

->  The Viewing Colour Space should be set according to the display you are using to view the images. The setting here was also preset by to the scene template, however it should be changed if necessary, to match the colour space of the display you are using:

1. Open the Cursors view from the Views menu \(this view may already be open within the current workspace in which case it will be briefly outlined with a yellow glow\).
2. Click on the Viewing Colour Space button and choose the correct setting from the pop-up menu – display colour spaces are listed with a monitor icon to the left of their name. Baselight provides colour spaces for all standard displays used in post production. It is worth pointing out that colours will only be totally accurate if the display you are using is accurately calibrated to the colour space you have chosen.
3. Now click on the Cursors view actions button and select ‘use these cursor settings when scenes in the job are opened’ from the pop-up menu. This will ensure that the same viewing colour space will be used for each scene you add to this job. You can later clear this option if required.

-> The final point to note is that when you are working with high dynamic range/wide gamut footage \(i.e. log encoded or RAW media\) Baselight will automatically apply an appropriate Display Rendering Transform \(DRT\) to convert the colour space into the viewing colour space for the image display. Again, this is preset in our example by the scene template but can be changed to a different DRT via a setting in the Format&Colour page of the Scene Settings view.

For the purposes of this exercise, all you need to do is check, and if necessary change the Viewing Colour Space as detailed in steps 1 to 3 above.

### Adding a grading layer

In Baselight, grades and other effects are applied to the source media using layers. There are several ways to add a new layer; the following example will describe a couple of them but please refer to the later sections of this guide for further details.

1. If you are not already viewing the ‘Standard’ Workspace, switch to it by pressing CTRL+SHIFT+1 on the keyboard.
2. Select the shot by CMD-clicking on it in the Cuts view \(you can also use one of the other navigation methods described earlier to select the shot you want to work with\) -> The selected shot will appear in the image display and the cursor will be positioned within the thumbnail in the Cuts view:

Selected shot

Cursor

Currently selected shot in Cuts view

````Note that there may also be a dark blue outline around the thumbnail – this is known as the Dark Blue Square or ‘DBS’. It is used for certain copy-paste operations and will follow the shot containing the cursor if the ‘DBS Lock’ button is enabled. The DBS has no effect when adding new layers so you can ignore it for now.
````


3. Add a new layer by pressing P on the keyboard. You can also add a layer by clicking on the Layer Manager button at the top of the screen and then clicking on the green ‘+’ button:

Layer Manager – add new layer

 -> A new layer will be added to the shot and will appear in the Layer Manager as ‘layer:1’. In the timeline you will notice a new strip has been added below the shot’s input sequence strip.

You will also notice that the parameters view – the main area of the UI screen – is now showing a set of grading controls and to the right of these controls is a column showing different types of grading operator:

Selected grading operator

Grading operators for the current layer

4. The currently selected grade type is highlighted in yellow – note that the initially selected operator for each grading layer is specified as a default in the user preferences. To choose a different one, simply click on it in the grading operators column. However, for this exercise make sure that the ‘Base Grade’ operator is selected.

-> The controls for the Base Grade operator will appear in the parameters view:

Base Grade controls – Dim/Balance/Light tab selected

5.  Make sure that the Dim/Bal/Light tab is selected at the top-left of the grading controls and then try adjusting the following on-screen controls to see what affect they have on the image:

   Balance, Dim and Light – the ‘virtual trackballs’ each have a ring and a ball control. To adjust them, simply click and drag with the mouse \(or tap and drag with a tablet pen\) in the same way you would move a physical control with your fingers. If you release the mouse while dragging on a ball control you will see that it continues to move a little, simulating the inertia of a physical ball.

6.  Now select the Dark/Balance/Bright tabThe main grading controls will change to Dark, Balance and Bright. Try adjusting these to see what affect they have on the image.





-> You will notice that the Balance control provides an overall adjustment to the exposure and colour balance of the image and that the Dark, Dim, Light and Bright controls have an affect which is restricted to different ‘lightness’ bands across the tone range of the image.

  To reset any of the controls, simply click on the corresponding button in the UI.

->  Note that you can also undo any changes you make by pressing CMD+Z on the keyboard and

  redo them again by pressing SHIFT+CMD+Z.

7. Finally, try adjusting the Flare, Contrast and Saturation values in the lower section:

Base Grade controls – lower section

Note that these are not mapped onto on-screen controls by default, however they can be adjusted interactively by clicking in the numeric field and then, while still holding down the mouse button \(or holding down the pen tip\), drag around the field with a circular motion – as if you were rotating an on-screen rotary control. The values will increase when you make clockwise rotations and decrease with anti-clockwise rotations. Note that the field background turns dark blue whilst this ‘gestural’ control mode is active:

Click-and-hold in a numeric field, then drag the pointer in a circular motion to simulate an on-screen rotary control.

Gestural control operation









 -> As you adjust the Flare control you will notice that the black ‘cut-off’ point of the image varies. The Contrast control changes the overall contrast or ‘gain’ of the image and the Saturation control varies the overall ‘amount’ of colour, as you might expect.

An indication of the combined effect of these controls is provided by the waveform display in the lower half of the Base Grade parameters \(see the example on the previous page\). You are encouraged to try adjusting all the controls in the Base Grade on a range of different images to fully appreciate what affect they have. Full details can also be found in the Base Grade section in the Basic Grading chapter ??? as well as video tutorials on the FilmLight website.

### Adding more layers

If you are just applying a basic colour adjustment to a shot then a single grade may be all that is needed. However, for more complex adjustments you will need to use multiple grading operators. You will have noticed that there are additional grading operators in the column to the right of the grading controls. These provide other types of grading tool. It is possible to add another operator within the same layer, however Baselight supports an unlimited number of layers per shot so unless you need to use multiple operators in the same layer, it is recommended to add a new layer for each additional grading operator you want to use.


There are several reasons why you may want to use of multiple operators in the same layer. These will be discussed later in this manual


The purpose of this guide is to give you a quick introduction to Baselight rather than to give a detailed explanation of the different grading tools. However, please feel free to experiment with the different grading controls and also the other types of grading operator.


If your system includes a grading control panel then of course you can use the trackballs, knobs and buttons to adjust the corresponding parameters of the different grading operators. Please consult the relevant control panel user guide for details.



8.  To reset the current grade, press CMD+Delete on the keyboard or right-click on the grading operator in the operators column and select Reset Operator Entry from the pop-up menu All the parameters for the current operator will revert to their initial values. You will also notice that the operator name will return to a white colour \(it turns blue when the operator is affecting the output\).
9.  Operators can also be temporarily bypassed, so they do not affect the output, by clicking on the bypass button below the operators column or by pressing CMD+SHIFT+F11 on the keyboardBypassed operators appear with hatching over them in the operators column and ‘B’ in the button turns red. Note that this is a toggle function.





### Viewing and selecting the layers

You will have noticed that the image on your grading display shows the combined effect of the layers or layer that you have added. Layers are applied to the image in the order they were added – i.e. Layer 1 \(containing the Base Grade\) is applied to the input and then Layer 2 \(containing the Film Grade\) is applied to the output of Layer 1 and so on. If you double-click on the shot’s thumbnail in the Cuts view, a pop-up Layer view will appear showing you the effect of each layer \(note that the Layer view can also be opened as a separate window by selecting it from the Views menu\).

Ungraded input image

Base Grade added

Film Grade added

Video Grade added

Selected layer

Layer view showing source and three grade layers


Note that in Baselight, layers are always applied from the top down, unlike many popular editing applications which apply layers from the bottom up.


As well as providing a useful visual reference for each layer, the Layer View provides a way to quickly go back and adjust any of the gradesSimply click on the thumbnail in the Layer view and the selected grading controls for that layer will be loaded back into the parameters view.

For example, click on layer 1 A yellow glowing outline will appear around the selected layer’s thumbnail in the Layer view \(the selected layer ‘strip’ in the timeline will also be highlighted with a yellow glow\), however you will notice that the output on the main image display still shows the final output with all the layers applied. This is because the viewing mode is set to display the final output by default. Follow the steps below to view the output of the selected layer:







1. Find the Cursors view within the current workspace – hint: if you can’t see where it is, select Cursors from the Views menu at the top of the screen A yellow glowing outline will appear briefly around the view in the UI.
2. Click on the add options button at the left-hand side of the Cursors view and add the Rendering option from the pop-up menu \(this option is initially hidden\)  A new Rendering mode button will appear in the Cursors view:

Add options button

Cursor rendering mode button

Current layer

Cursors view – layer output viewing mode

3. Click on the Rendering button and choose Layer Output from the pop-up menu.

 The main image display will now show the output of the current layer.

4.  To return to viewing the final output again, select To Row Cursor from the cursor Rendering button.
5.  If you want to bypass the whole layer, which will temporarily remove the effect of all the operators in the layer, click on the toggle button at the top of the screen \(above the grading operators column\) or press CMD+F11 on the keyboardBypassed layers appear with hatching over them in the Layer view. The layer strip in the timeline is also hatched when it is bypassed.
6.  If you want to completely remove a layer, select it in the Layer view or select its strip in the timeline, and then press SHIFT+P on the keyboard.

## Working with mixed resolutions

Before continuing, we will look briefly at the way Baselight converts between different resolutions and aspect ratios using ‘formats’. For further information about formats and format mappings please refer to the Formats chapter.

If you have been following the examples in this quick start guide you may have noticed that the ‘Working Format’ which was defined when the scene was originally created \(see page 12\) and also the ‘Viewing Format’ in the Cursors view \(see page 27\) are both set to ‘HD 1920x1080’.

The Working Format defines the resolution \(and aspect ratio\) at which the images will be processed internally within the scene. It is effectively specifying the format of the timeline. The Viewing Format defines the





resolution \(and aspect ratio\) at which you are currently viewing the images from the cursor. The Viewing Format would typically match the Working Format, but it doesn’t have to. For example, you may have a project which will be delivered at both full HD \(1920x1080\) and also as a lower resolution version at 1280x720. In this case you would set the Working Format to 1920x1080 and also the Viewing Format while doing the main grading work. However, at any point you may want to check what the 720p version would look like – you can do this by switching the Viewing Format temporarily over to 1280x720 \(using the setting in the Cursors view\).

### Format mappings

Baselight uses ‘formats’ to define ‘mappings’ between media which has different resolutions and/or aspect ratios. When each shot is added to the scene, it is tagged with an ‘Input Format’ which defines its horizontal and vertical resolution and also its pixel aspect ratio. This information is derived from the media file, although note that some file formats do not provide pixel aspect ratio information so this may need to be added manually if the pixels are not square.

When a shot is played back, a geometric transform is applied which converts or ‘maps’ it into the Working Format of the scene. By default, the image is scaled evenly so that it fits the width of the scene’s working format:

Input Format \(2.39:1\) - 4K ‘scope’ Working Format \(1.78:1\) - HD 1920x1080

Mapping between Input and Working Format

As can be seen from the example above, if the aspect ratio of the input image is wider than the working format, then it will appear ‘letterboxed’ in the image display. On the other hand, if the input image has a





narrower aspect ratio than the working format, then the top and bottom of the image will be outside the visible area of the image display:

Input Format \(4:3\)

Working Format \(1.78:1\)

Input ‘taller’ than Working Format

In many cases this default mapping will be adequate as the DOP will have framed the shot with the final aspect ratio in mind. However, there may be situations where you want to adjust the vertical shift of the mapping to see more of the hidden ‘head’ or ‘foot’-room of the image.

Format mappings are also applied when you render to an Output Format which has a different resolution or aspect ratio to the working format, or if you select a cursor Viewing Format which is different to the working format. Again, the same ‘default’ mapping \(fit width\) will be used unless you have specified a custom mapping between the working format and the output \(or viewing\) format.

Baselight will apply these default mappings automatically unless a specific mapping has been defined between two ‘named’ formats. Full details can be found in the Formats chapter later in the guide.

## Secondary grading

When working through the examples in the section on adding a grading layer, you will have noticed that the adjustments you made to the grading controls affected the whole image. An overall grade in Baselight is known as a primary grade. In many cases however, you will want to affect only certain parts of an image – just the highlights for example, or perhaps just the blue hues of a sky. You may have scenes where you need to restrict the grade to just a shape within an image, for example to darken the corner of a room.

In this section we will take a brief look at some of the tools available to do selective or secondary grading. 

### Hue Shift

The first example of selective grading uses the Hue Shift operator to adjust the colours in an image separately from one another:


1. Add a new layer to the current shot by pressing P on the keyboard and then select the Hue Shift operator in the operators column.
2. Click on the Hue/Saturation page  The controls will appear as shown below:

Hue Shift operator – Hue/Saturation page selected

3. Drag the cyan slider in the ‘Saturation’ section on the right-hand side up and downThe saturation of the cyan hues in the image will be reduced but all other colours will remain the same.
4. Select the Hue/Value tab and drag the cyan slider up and downThe ‘value’ or lightness of the cyan hues will vary.
5. On both pages there are Hue vs. Hue controls. Try adjusting one of them to see the affect that is has on the imageYou will find that it changes the hues of only a certain range of hues in the image and has no effect on hues outside this range.
6. Note that there is also a Global pageThis provides Hue, Saturation and Value controls which affect the whole image \(these are not ‘selective’ grading operators\):

   Hue Shift operator – Global controls

This is just one example of a grading operator which affects only a certain range of colours in an image. Baselight provides several other grade types such as HSL curves and Six Vector which can also be used for selective grading – these are covered in the Basic Grading chapter.





### Inside/Outside grading using a matte

The previous section looked at a grading operator which inherently changes certain ranges of colour in the image while not affecting other colours. Another way to restrict the affect of a grade to certain ranges of hue or lightness is by creating a matte and then using that matte to isolate the affect of the grade to a certain area of the image. For example, using a chroma keyer we could create a matte from just the cyan hues in an image. In turn, that matte could be used to restrict where a grade is applied to desaturate the image. The following steps will take you through an example of this process:

1. Add a layer to one of the tutorial shots.
2. Press H on the keyboardThis will add an HSV or ‘Hue Angle’ keyer to the matte operators for the layer. In the parameters view you will see the controls for the keyer and you will also notice that to its right are two columns of Matte Operators with the HueAngle keyer selected in the first column:

Qualifier controls

Preset Colour Greyscale ranges wheel ramp

Hue Angle keyer controls

Matte tool button

3. Move the mouse cursor over to the image display \(press CMD+Esc if working with a separate image display\) and click-and-drag across a small range of colours in the image The range of colours selected will set up the Hue, Saturation and Value qualifier controls. You will also see these indicated as a range in the colour wheel and on the greyscale ramp.





 4. View the key matte you have just created by pressing O on the keyboardThe matte will appear in the image display as a monochrome image. White areas are those included by the qualifier settings; black areas fall outside the Hue, Saturation and Value qualifier ranges.


Baselight provides several different methods for showing and overlaying the matte for a layer. You can cycle through these by pressing SHIFT+O on the keyboard – for now, select the monochrome matte viewing mode.



Note that you can also preview the matte for a layer by double-clicking on the Cuts view thumbnail to bring up the Layer view – the matte is shown in the thumbnail to the right.

In the example below, an area of the sky was selected, creating a matte from the cyan/blue hues:

Source image

Matte created from hues in sky

HueAngle keyer example

To zoom the image display so you can see more detail, hold down CMD on the keyboard and then click-and-drag to the right using the middle mouse button; dragging left with the middle mouse button zooms out. Dragging with the middle mouse button but without holding down CMD on the keyboard will pan the image display. To return to full screen mode press F12 on the keyboard. Note that panning and zooming the image display using the middle mouse button has no effect on the final rendered images – it is only affecting the viewing display.

5. Now try adjusting the sliders in the Hue, Saturation and Value qualifier sections to refine the matte. Note that you can also make adjustments to the Hue, Saturation and Value ranges by clicking and dragging within the colour wheel and the greyscale ramp.

 Pressing SHIFT+O will cycle through the ‘overlay’ and ‘invert overlay’ matte viewing modes – these can help to see exactly which areas of the image the matte covers.







6. Once you have finished adjusting the matte, press G on the keyboard to return back to the grading operators for the layer.

 The controls for the selected grading operator will appear in the parameters view in place of the matte controls. Note that pressing G again will toggle back to the matte controls.

Clicking the ‘Mona Lisa’ buttons above the operator columns will switch between the grading and matte operators for the current layer. Note that hardware control panels also provide buttons to directly select grading and matte operators.

You will notice that the second column of grading operators has become available \(previously it was dimmed and unavailable\) because this layer now includes a matte. The left column of operators will now only affect the parts of the image which lie inside the matte \(i.e. where the matte is white\) and grading operators in the right column will affect the area outside the matte \(the black areas of the matte\).

7.  Select a grade type in the inside column – the Base Grade for example – and adjust its controlsNote that the grade is only applied to the areas which are qualified by the HueAngle keyer, in our example the inside grade would be restricted to the sky only.
8.  Now click an operator in the outside column and adjust its controls.This time only the areas not qualified by the key will be affected. Note that you can use different operators on the inside and outside of a matte allowing a complex look to be created within just a single layer.

   In this example we isolated parts of the image with the HueAngle keyer, which uses an HSV qualifier to generate a matte. Baselight provides two other types of keyer and can also work with an external image matte, either read from an embedded channel within the input media file or from a separate input image layer. For full details of keyers and external mattes please refer to the Keyers and Mattes chapters later in this manual.

### Grading through a shape

The previous steps took you through the process of creating a matte using a key. This is useful if you want to restrict the grade to areas depending on the content of the image. However, it is also possible to define areas in a matte using geometric shapes:

1. For this example, make sure you create a new layer on one of your shots before you start \(press P on the keyboard\). Then press SA matte will be added to the new layer as in the





previous exercise, but this time the Shape operator will be selected, and the shape controls will appear in the parameters view:

New Shape Quickshape New Shape Shape operator mode drop-down button

Shape controls

2. Click on the Quickshape buttonA list of preset shapes will appear as shown above. For this example we will choose vignette – click on it in the list to add a shape to the matte.







 An overlay will appear on the image display showing the outline of an ellipse as a dashed yellow/blue line contained within a dim red rectangle. You will notice that there is also a blue rectangle enclosing the entire shape and various control points and handles:

Bézier curve outline

Bézier curve control point

Shape control point

Bézier curve bounding box

Shape control handles

Shape bounding box

Shape overlay showing curve and shape controls

Geometric shapes in Baselight are composed of one or more closed Bézier curves. If you add a preset ‘quickshape’ such as an ellipse or a rectangle, it will be created as a Bézier curve. The control points which define the curve can be adjusted using Bézier handles and points can also be added or removed from a curve. A red bounding box containing the curve can be used to scale and rotate the entire curve. An outer blue bounding box contains all the curves within the shape and can be used to transform the entire shape. Full details of creating and editing shapes are covered in the Shapes chapter on page 507.

3.  Press G on the keyboard to return to the grading operators and then select an operator in the ‘Outside’ \(right-hand\) column of operators – for this exercise we’ll choose the Film Grade.
4.  Reduce the Exposure controlThe outside of the ellipse will darken, giving a typical vignette effect.
5.  You will notice that the vignette effect has a soft edge; this is because the ellipse includes feathering. Press O on the keyboard to view the matte \(if necessary, press SHIFT+O a few times to cycle through the matte viewing modes\).

6.  Press G again to toggle back to the matte operators and then adjust the Feather Radius slider in the shape controls to see the effect it has on the shape matteYou will notice that the feathering is always ‘outward’ from the curve outline.

   By enabling the Custom Inner/Outer Curves mode toggle button, inwards feathering is possible, as well as variable feathering at different points around the curve.

7.  Reduce the feathering to around 10 so you can see the edge of the shape and then click on one of the Bézier control points of the ellipseA pair of Bézier handles will appear indicating that the point is now selected for editing. Try dragging on the point and also on the ends of its handles to see the effect it has on the curve.

Bézier curve outline

Selected control point

Bézier curve handles

Bézier curve showing control point handles

8.  Click on the curve between two existing pointsA new point will be added with its handles set so that there is no change to the shape of the curve. You can now adjust this new point.
9.  If you would like to return to the original vignette, simply press CMD+Z a few times to undo all the changes you made to the shape.

This is just a very brief overview of using a shape operator to create a matte. In addition to using Quickshapes, shapes can also be created starting with a ‘primitive’ ellipse or rectangle, or by drawing points using the freehand option. The transparency of individual shapes and also the way multiple shapes combine together within the matte can be adjusted. Full details of shapes can be found in the Shapes chapter and also in video tutorials on our website.







## Working with audio

You may need to add sound to a Baselight scene for a couple of different reasons. Firstly, if you are working on a scene which has been edited and conformed then a sound track may be available which can be added to the scene to play back as a preview. The second reason is adding sound to the source shots in your scene.

In this quick start guide we will briefly cover both scenarios – please see the Working with Audio chapter for more details.

### Scene audio

To add audio which will play back throughout the scene:

1. Open Scene Settings from the Views menu at the top of the screen and select the

   Scene Audio page by clicking on the tab.

2. Click on the Type button and choose File or Movie  Additional options will appear.
3. Click on the file browser button at the right-hand end of the Filename field and browse to find the audio file you want to play back with the scene. Select the file by clicking on it and then click on the Ok buttonThe path to the selected audio file will now appear in the Filename field.

   Note that Baselight currently only supports playback of uncompressed audio file formats such as WAV and AIFF. You can also use a movie containing an audio track.

4. If there is a time offset between the start of the audio and the first shot in the scene, you can compensate for this by entering a number of frames or seconds into the Offset field \(switch between frames and seconds by clicking on the ‘S’ or ‘F’ button\). Note that a negative offset will start the sound playing by that amount of time after the beginning of the scene.
5. The Ratio button allows for the audio to be sped up or slowed down by a small amount if it was recorded using a different ‘time base’ to the scene’s playback frame rate. For example, if the audio was recorded with a timebase \(i.e. timecode frame rate\) of 23.976fps but the scene has a working frame rate of 24fps, you should set this to 1000:1001. Note that as the audio will be running at a different rate to when it was recorded, the pitch will be shifted slightly.
6. The last two options provide adjustment of the audio level and the playback channels.

### Shot audio

Audio can also be added to each shot in the scene. If a shot was imported as a movie file which contained an audio track then the audio will already have been added to the shot by default. However, it is also possible to manually add audio to a shot:

1. Select the Standard workspace and select the input layer for the shot \(you can do this by selecting the top layer in the Layer Manager\).

2. Click on Audio in the layer 0 operators column:

Shot audio

Layer manager button

Audio selector

Input layer \(Layer 0\) ‘operators’

-> The audio settings for the current shot will appear in the parameters area. If there is currently no audio, the audio Type drop-down button will be set to No Audio.

3. Toaddaudiototheshot,clickontheTypebuttonandchooseFileorMovieAdditional options will appear. The next steps are the same as for adding audio to the whole scene – see steps 3 to 6 on page 37.

 Once the audio file has been added to the shot it will play back for the duration of the shot. Note however that if you have added audio to the whole scene, this will override any audio which exists for individual shots.

There are other options for per-shot audio which can be used to help automatically find and synchronise audio to one or more shots. These features are covered in detail in the Working with Audio chapter of this user guide.





## Rendering and export

Once you have finished grading and reviewing your scene, the final step is to export it. However, before continuing you should make sure that the scene is saved. The quickest way to save the scene is to press CMD+S on the keyboard. You can also select Save from the Scene menu at the top of the screen.

Baselight automatically saves every change you make into the database so the scene is effectively being continually saved as you go along. This is useful in the case of sudden power loss or a system crash. However, when you actively save the scene, this ensures that the latest changes are fully written to the database and also creates a ‘last saved’ time stamp.

### Rendering movies and sequences

Media files can be rendered either as movies or frame sequences. In both cases you can either render the entire scene as a single movie or frame sequence, or you can render a movie \(or sequence\) per shot. In the latter case there are several options on how to name each separate movie or frame sequence.

To render the entire scene as a single movie or frame sequence:  
 1. Open the Render view from the Views menu or press CTRL+R on the keyboard.

 The Render view will appear as shown on page 40 – it contains a lot of information. If necessary drag on the edges of the view to resize it.

At the very top of the Render view you select the frames you want to render by clicking on the Frames To Render button. By default this is set to All Frames which will render every frame in the scene from the first frame of the first shot to the last frame of the last shot. To select a different range of frames or multiple frame ranges click on the button and then select the required frame range\(s\) from the drop-down options. You can also type in the required frame range\(s\) by typing them in to the field to the right of the button.

Below the frame range setting you will see a row of tabs – these tabs provide two functions: clicking on a tab will select a render settings page containing all the settings for a specific type of deliverable; enabling the white toggle button in a tab will activate that deliverable for rendering. Note that multiple deliverable tabs can be enabled in which case multiple deliverables will be rendered at the same time. Please see the Rendering & Deliverables chapter for further details.

2. If you have been following this guide from the start, then the deliverable tabs in the render view will have been automatically preset from the ‘FilmLight’ template used to create the





scene. Click on the ‘QT for Approval’ tab to select its settings and also click to enable its white toggle button. Make sure that the buttons in all other tabs are turned off:

Render frame  
 range selector Deliverable tabs

Render view with first deliverable tab selected and enabled

3. If you want to change the name on the tab, double click on it and then type in the new name It is useful to use a name which describes the ‘purpose’ of the deliverable, for example you may want to label it “Full Scene Review”.

   The rest of the steps go through the process of checking and changing the render settings. As this is just a quick overview many of the options will be skipped, please refer to the Rendering & Deliverables chapter for full details.

4. Select the type of output media by clicking on the appropriate Output button. Note that you can choose to render to a movie format such as QuickTime or MXF, or a frame sequence \(DPX or EXR for example\). Audio can also be rendered with the deliverable.

   For this exercise choose Movies Video+Audio.

5. Next, click on the File Type button and choose QuickTimeTM Movie from the drop-down list.
6. Once you have chosen the file type you can then choose the type of encoding to use for the movie by clicking on the Codec button in the Video settings and selecting from the drop- down list.

   Note that the STUDENT version of Baselight only supports a limited range of output options.

 Leave the rest of the Video and Audio settings set as they are for now and move down to the Render section. There are several settings in this section – we will just look at a couple in this exercise:

7. The first setting is the Render Format. This setting may initially be hidden – to make the option visible it needs to be added by clicking on the add options button and then selecting Render Format from the list of available settings.

Settings which are currently set to their default value are normally hidden from ‘options’ menus to simplify the user interface. If you want to reveal all the settings which are set to their default values, select Add All from the add options list \(click on the button\). To re-hide a setting which is set to its default value, hover the mouse pointer over the setting nameWhen a red line appears through the text, click on the text to hide the setting. There is also a Remove All option in the add options list. Note that settings which are not at their default value will always be visible.

8.  By default, the Render Format will be set to match the Working Format – in this case HD 1920x1080. If you want to render to a different resolution you can choose the appropriate format from the drop down list by clicking on the Render Format button. Note that this list will only include the built-in ‘factory’ formats and custom formats which have already been defined and made available to the scene. Please refer to the Formats chapter for further details.
9.  The second option to add is the Render Colour Space. Again, the default setting for this is to match the Working Colour Space. However, you should always check this and change it to match the required colour space of your deliverable. For example, if you are rendering a movie to be played back on a standard HD monitor then you would choose the Rec.1886:2.4 Gamma/Rec.709 setting.

   Note that in this example the Render Colour Space setting will probably already be visible as the setting will have been set to Rec.1886:2.4 Gamma/Rec.709 by the scene template. This is not the default value as it does not match the example scene’s Working colour space.

The final steps are to select the output directory and the file name of the rendered movie. Baselight provides a powerful template system which can incorporate system variables to automatically create directory paths and file names according to various criteria. However, in this example we will manually specify the output path, destination directory and file name:







10. Make sure that the Directory and File Name settings sections are visible – if necessary click on the Show output template button:

Show output Resolution directory template Output directory browser toggle button

Render directory and file name settings

11.  Click on the directory browser button and navigate to the destination volume and directory into which you want to save the rendered movie file.
12.  Enter the file name for the movie \(without the file extension\) into the text field to the right of the Input Filename button. Note that this field may already contain a preset name or file name template consisting of one or more ‘%’ codes. In this case, simply triple-click in the field, or click and then drag over the existing text to replace it. The drop-down button to the right of this field allows you to choose an appropriate file extension for the chosen type of output.

 The First File field will now show you the full directory path and file name of the output deliverable. Note that it will probably include a ‘1920x1080’ directory before the file name. This ‘resolution’ directory indicates the resolution of the media file\(s\) it contains and can be very useful for certain types of workflow. If you don’t want Baselight to automatically generate the resolution directory, turn off the /Resolution toggle button at the right-hand end of the Directory settings.

There are several other options in the render settings which we have not covered but these can be left as they are not used for the purposes of this exercise.

13.  You will notice that there are two buttons at the bottom of the Render view: Verify Render and Submit Render. Click on the Verify Render buttonBaselight will scan through the source material to check that the required frames are available. Once the scan is complete you should see a message saying that the frames should render correctly.
14.  Finally, click on the Submit Render button at the bottom right corner of the Render view. When prompted, enter a title for the render operation \(or accept the default title\) and click on Submit.





->   The render will be submitted to the render queue and the Queue Monitor window will automatically open.

  If you are working in a networked environment with multiple Baselight systems you will be able to choose which machine you want to submit the render to, including the local machine. If the local machine is running Baselight CONFORM software, you will only be able to submit renders to another Baselight system on the cloud network as local rendering is not supported on Baselight CONFORM.

->   The Queue Monitor will show the progress of rendering operations on the selected machine. To see more information about an operation, select it in the list – details will appear in the log area at the bottom of the Queue monitor view.

  Current rendering Rendering operation progress

Render Monitor showing rendering operation in progress

 Once the rendering operation is complete you will be able to check the rendered movie using the Preview and Play buttons in FLUX Manage \(see page 161\).

In this example we created a single movie from all the shots in the scene. In many workflows, such as VFX or dailies grading, you would typically want to render a separate output movie \(or frame sequence\) for each input shot. Please refer to Chapter 35 – Rendering & Deliverables for full details.





## Quitting Baselight

Now that you have completed the basic steps in an end-to-end workflow you can save your project and quit out of the application.

To do this you can simply click the Baselight drop-down in the top left of the UI and select Exit. This will close the software. You can also use the keyboard shortcut CMD+Q.

Exit Baselight option drop-down

An additional dialogue window will open upon clicking this option if you have any unsaved changes to give you a chance to save before the software closes. You can choose to Save and exit, Discard the changes made since the last save and exit or to Cancel the software shutdown and go back to the UI.

Unsaved changes dialogue window







  


