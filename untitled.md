# Introduction

Baselight 5.3 User Guide \(Mac\)

Baselight is a digital non-linear grading system that includes powerful conform and finishing features. Its range of input options, resolution independence, native colour space processing and flexible output renderer, enable operation in any film or video format. The FilmLight-designed hardware control surface provides many workflow enhancements, and the extensible plugin architecture supports a range of built-in and third party productivity tools. Baselight systems can also incorporate a large amount of RAID storage, and deliver finished results as either a set of fully rendered media files or as grade and project metadata in a range of interchange formats including the comprehensive ‘BLG’ format \(see page 146\).





Baselight 5.3 User Guide \(Mac\)

Starting the application

The application is launched from the icon, which can be found in /Applications/Baselight.  
 While the software is loading, a splash screen will appear giving you the current software build number.

\]

{% hint style="info" %}
Baselight 5.3 User Guide \(Mac\)

Note that if the software licence has not yet been installed or activated you will be presented with a pop-up licence dialogue box. Please refer to your system Installation Manual for details of installing or updating the application software and the licence.
{% endhint %}

Baselight 5.3 User Guide \(Mac\)

You will also see one of a series of slides during start-up, highlighting recently-added or little-known features in Baselight. If you click on the slide, the launch sequence is paused and you will be able to cycle through the whole series, as well as hiding a specific slide or displaying hidden slides. To recommence the launch sequence, click Continue Startup.



Baselight 5.3 User Guide \(Mac\)

Once the application has launched you will see a default workspace displayed in the Baselight user interface and the Job Manager opened as a floating window. If your system includes a grading control panel then it should also have been initialised and you should see appropriate labels on its buttons and screens.





Baselight 5.3 User Guide \(Mac\)

Baselight software versions

Software releases are numbered according to their version and build number. The major version is the first number before the point and is referred to as simply the software ‘Version’. For example 5.1.10720 and 5.2.10795 are both ‘Version 5’ software releases. The number after the first point is the ‘minor’ version number, so the examples above are 5.1 and 5.2 releases respectively. The final number after the point is the actual build number and uniquely identifies each software build we release.



{% hint style="info" %}
Baselight 5.3 User Guide \(Mac\)

Note that from Version 5 onwards, all minor versions within a major version are compatible with each other in terms of the ability to open scenes saved by a different software build, e.g. Version 5.1 and 5.2 are able to open each other’s scenes. This compatibility extends across all Baselight products including CONFORM and EDITIONS.

Scenes and jobs saved in Version 4 will need to be upgraded before they can be opened in Version 5 - see Opening Scenes from Older Software Versions on page 96.
{% endhint %}

Baselight 5.3 User Guide \(Mac\)

Key features

This version of the Baselight manual includes information about the following new features:

Improved trackers

The Baselight trackers now have a simplified user interface. You can also filter motion data for the smoothest track possible, create planes separately and easily share them between trackers, and use custom naming for trackers and planes.

See Trackers on page 533 for more information.

Partial conform

In Baselight 5.3, you can conform new media against existing shots in the timeline. In this operation, rather than creating new strips on the timeline, Baselight will overwrite the existing Sequence operators with new ones. Use the powerful filtering in Shots View to select the parts of the timeline to conform, and piece together complex conforms by loading a single edit list and then conforming parts separately.

See Partial conform on page 244 for more information.



Baselight 5.3 User Guide \(Mac\)

Lens distortion/correction

Correct – or apply – lens distortion based on analysis of the image or by using presets for common industry lenses. This is useful for preparing plates for VFX, or creative grading effects. You can also use lens distortion/correction in a ‘sandwich’ so that grading operations can be performed on the undistorted image.

See Lens correction and distortion on page 598 for more information.

Consistent spatial operations

Some operators – like shaders, OFX plugins or spatial operations such as Texture and Soften – can behave differently when applied to different image resolutions. If this is the case, you can specify that image processing happens at the working format resolution, rather then the viewing or output resolution.

See Processing Format on page 408 for more information.

Improved looks

Looks now work seamlessly with T-CAM v2 to ensure no restriction on dynamic range. The library of Looks has also been expanded to include even more classics such as ENR.

See Look on page 620 for more information.

Sequence versioning wildcards

Use wildcards when defining the sequence versioning template, so that you can work with versions within date folders. You can set wildcard templates on-the-fly or in Scene Settings View.

See Wildcards on page 255 for more information.

Improved LUT integration

The new LUT operator allows you to set input and output colour spaces for each LUT. You can also apply LUTs embedded in ARRI and RED camera files, and use Media Import Rules so that this happens automatically whenever you add these types of camera file to your timeline.

See LUT Operator on page 621 for more information.

Gamut alarm

The Compress Gamut operator now includes a Gamut Alarm option, which allows you to pin-point exactly which colours are out-of-gamut based on your current settings. When enabled it shows all unmodified colours in grey – only the out-of-gamut pixels maintain their original colour value.

See Compress Gamut on page 616 for more information.



Baselight 5.3 User Guide \(Mac\)

Baselight also includes the following key features:

Comprehensive media file format support

Read and render a wide range of media file formats - for a complete list please refer to the Baselight Codec Support datasheet which can be downloaded from our website.

Extensive metadata

During the import process all metadata is read from the source files and imported into the local database. Powerful tools within Baselight provide quick searching, sorting and modifying of the metadata and selected data can subsequently be rendered into output files or exported for use by other systems.

Automatic colour space management

Regardless of the camera it was captured with, all source material is transformed accurately from its native colour space into a common colour space for grading and deliverables can be rendered into different colour spaces according to the requirements of the workflow. These colour space conversions are all performed automatically, saving a huge amount of time and providing more consistent and accurate results.

Full creative toolset

All shots can have full sophisticated looks applied using the same compact grading interface familiar to users of Baselight Editions for Avid and NUKE. Secondary grading features include a range of keyers and shape tools plus matte processing and auto tracking for speeding up advanced operations.

BLG file support

Baselight provides read and write support for BLG files and the Baselight LensTM feature enabling powerful ‘render-less’ workflows throughout the entire post-production pipeline including on-set, dailies, editorial and visual effects departments.

GPU acceleration

All grading operations and image effects are processed using the available system GPU\(s\), improving overall performance and reducing rendering times.

Built-in Scopes

Baselight includes six different tools to help you adjust and QC your deliverables.

Audio syncing

Separately recorded audio files can be automatically synced to multiple source movies in a single operation; semi-automatic and manual syncing tools are also provided.



Baselight 5.3 User Guide \(Mac\)

Simultaneous deliverables

Multiple deliverables can be generated in one pass using Baselight’s powerful render manager. Renders can also be queued and off-loaded to other networked Daylight and Baselight systems.

Import and export of EDLs

Baselight can import material according to a CMX or ALE list and can also export EDLs in the same format, with embedded ASC CDL grading data.

Works directly with FilmLight on-set systems

Baselight can import look metadata directly from FilmLight’s on-set look management system, Prelight.

For more information about the features in Baselight v5, see the Baselight 5.3 datasheet, available from the FilmLight web site.



Baselight 5.3 User Guide \(Mac\)

Terminology

Like any specialist system, Baselight uses some of its own nomenclature to describe specific objects and functions. To avoid potential confusion, the following is a brief explanation of some key terms used in this manual.

Conform

Cutview

EDL Format

Frame Gallery

GPU Histogram

Image Display

The process of assembling image sequences in the timeline according to a list. Thumbnail representation of the scene. Can be used for navigation and copy-paste

operations.

 Edit Decision List.

The format provides a way for Baselight to store information about a sequence itself-such as the frame rate or pixel aspect ratio-that is not stored within the individual image file.

One of the many still images that compose the complete moving picture.  
 A ‘bin’ to store graded shots. The contents of the gallery are independent of the

scene contents and can be shared with other projects.

 Graphics Processing Unit.

RGB histogram display of the frame currently being viewed in the Image Display, which shows the distribution, in 10-bit code values, for each of the red, green and blue channels for the currently displayed frame.

The monitor or projector used to display the images that you are grading. The Image Display is calibrated and controlled by Truelight to guarantee colour





Baselight 5.3 User Guide \(Mac\)

Terminology

Works directly with FilmLight on-set systems

accuracy. Note that in multiple-view mode, several Image Windows may be shown in the same Image Display.

The window within the Image Display that shows the images that you are currently working on. The Image Window may fill the Image Display or there may be several Image Windows within the Image Display in multiple-view mode.

This is what a project is called in Baselight. The job name is often the name of the film or project currently being graded. Internally, a job is a complete database containing data for all the scenes in a project. The Job Manager is used to create and delete jobs and scenes.

A keyer is designed to isolate colours so that they can then be adjusted or enhanced via the grading plugins.

A frame that is used to indicate the beginning or end of a change to the grading controls.

A layer essentially groups related items to make it easier to work with them on the timeline. A stack can contain multiple layers.

When a sequence is added to the Baselight timeline, it is added in an input layer, which contains information about the sequence. Grades are also inserted in layers by default; a grading layer is called an Inside-Outside layer and contains the grade\(s\) applied to the sequence as well as links to any inputs for those grades, such as a matte created from a shape or key.

A matte masks specific parts of an image to allow a different correction to be applied, perhaps to highlight the detail in someone’s face or soften the colour of an object. A matte can be created using shapes, or by using a keyer to isolate certain colours.

Information that is stored on a per-shot basis when a sequence strip is inserted into the timeline. This information can be pulled from the EDL or from the files themselves.

A lower resolution copy of an image, used to improve Baselight interactivity and playback performance when working with high resolution images; for example, there may be proxies at half and one quarter of the resolution of the master footage. The actual proxy resolutions available for a given format are defined as part of each format.

Part of a Baselight project, contained within a single Timeline. A scene is a collection of shots and does not necessarily have to be a script scene. Each scene may represent a single reel or, for example, a complete commercial or a series of separate effects shots from different scenes within a feature film.





Baselight 5.3 User Guide \(Mac\)

A contiguous series of numbered image files. Image files in a sequence normally have a short name followed by a sequence number. For example, img0001.dpx, img0002.dpx, img0003.dpx would constitute a sequence of three frames.

A ‘raw’ image sequence strip in the Baselight Timeline. This is the top strip in a render stack and points to a sequence \(or part of a sequence\) of frames on disk. Note that the word ‘shot’ does not imply a specific shot within a script or a particular camera setup. It may refer to an event in the EDL.

Each image sequence is represented in the Timeline as a single strip. When an operation such as a film grade is applied to this sequence, it appears as an equal length strip below the image strip. A single image sequence strip can have any number of operations applied to it, and this column of strips in the Timeline is known as a ‘stack’.

The part of Baselight that manages layers, and essentially groups related items to make it easier to work with them on the Timeline.

Time- or frame-based ‘layer’ view of all strips in the current scene.  
 The Baselight User Interface. This includes all of the on-screen controls that

appear on the UI Monitor but not the contents of the Image Display.  The monitor used to display the Baselight UI.







