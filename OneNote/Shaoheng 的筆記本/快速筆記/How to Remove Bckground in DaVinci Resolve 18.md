剪輯自: [https://edits101.com/remove-background-in-davinci-resolve-18/](https://edits101.com/remove-background-in-davinci-resolve-18/)

![How to remove background in DaVinci Resolve 18](Exported%20image%2020241106113933-0.jpeg)

Facing the challenge of removing a background from a video clip? This could be for various reasons, such as replacing the background with a different image or video, isolating a subject for compositing, or just to make your video look more professional.  
In this guide, we will show you how to **remove the background from a video consisting of a black or white background, green screen and solid colours in DaVinci Resolve 18**, using its advanced features and tools.

## How to Remove Black or White Background Davinci Resolve 18

In this tutorial, you will learn how to remove the background consisting of the black or white of the clip using **Luma Keyer**. Just have to add it and adjust the sliders accordingly to hide the black or white background.

### Step 01: Setting up the document

Initially, you need to **open a clip or project**,

- Open the **DaVinci Resolve 18** application.
- **Right-click** on the Media Pool section.
- Choose the option **Import Media** as displayed below.
- Alternatively, use the keyboard shortcut Ctrl/Cmd+I to open the media.

![Timelines Create New Timeline Using Selected Bin... Create New Multicam Clip Using Selected Bin... New Fusion Composition New Bin Import Bin... Import Media... Import Media from XML... Import Subtitle... Remove All Clips in Bin... Relink Clips for Bin... Auto Sync Audio 1-4 Ctrl+l ](Exported%20image%2020241106113934-1.png)

Go to the location where your media is stored, select the video clips as necessary and click on **Open**.

### Step 02: Edit page > Set the Timeline

**To go to the Edit page,**

- Go to the bottom of the canvas.
- Click on the ‘Edit page’ icon.

![Exported image](Exported%20image%2020241106113935-2.png)

Next, you should be on the Edit page to change the background of the clip having a white or black background.  
**Click and drag the video to the timeline** and adjust it as required.  
Then, click on the clip within the timeline and make sure it is selected.

### Step 03: Fusion page > Add the Luma Keyer node

**Go to the Fusion page**,

- Go to the bottom of the canvas.
- Click on the ‘Fusion page’ icon.

![1880 4) DaVinci Resolve 18 130.0 .1 ](Exported%20image%2020241106113937-3.png)

Once you are on the Fusion page, you will notice that the ‘MediaIn’ and the ‘MediaOut’ nodes are connected.  
Follow the below steps to **set the nodes**:

- Select the ‘MediaIn’ node displayed on the timeline
- Press ‘Shift+Spacebar’. This opens a list of tools you can choose from.
- Click and select the Luma Keyer (LKy).

![Media 1190 Media Out DaVinci Resolve 18 Clips Ed•ted Metadata Clip 1230M6Ä Audio Settings o Luma Keyer (LXy) Keyer T Cube LUT cube L UT Cube I LCC) Magic (M OEM) [Man) Mask Paint Material Merge Co-vtrol ( Mat) Media In out Med i a > Ga Space 0.0 '590ME ](Exported%20image%2020241106113941-4.jpeg)

- Click on ‘Add’.
- The Luma Keyer will be added to the nodes.

![Exported image](Exported%20image%2020241106113943-5.jpeg)

**If the Luma Keyer option isn’t added to the nodes automatically, you can do this manually:**

- Connect the ‘MediaIn output’ with the ‘Luma Keyer input’.
- Then, connect the ‘Luma Keyer output’ to the ‘MediaOut input’.

### Step 04: Adjust the Luma Keyer settings

To **change the settings of the Luma keyer** first make sure that it is selected. Then,

- Go to the ‘Inspector’.
- Find the controls of the LumaKeyer.
- Adjust the ‘luminance’ and ‘contrast’ slider as per your requirement to remove the black or white background on the clip.

![Keyfra mes Inspector Metadata Tools LumaKeyer1 Channel Alter Blur Clipping Mode Contract Expand Gamma > Solid Matte > Garbage Matte Controls Settings Luminance Fast Gaussian None Domain Inspector High Frame Post Multiply Image ](Exported%20image%2020241106113944-6.jpeg)

## How to remove background in daVinci resolve 18 with green screen

To remove a green screen in DaVinci Resolve 18, we will use the brush of the Open FX Overlay.

### Step 01: Setting up the document

Initially, you need to **open a clip or project**,

- Open the **DaVinci Resolve 18** application.
- **Right-click** on the Media Pool section.
- Choose the option **Import Media** as displayed below.
- Alternatively, use the keyboard shortcut Ctrl/Cmd+I to open the media.

![Timelines Create New Timeline Using Selected Bin... Create New Multicam Clip Using Selected Bin... New Fusion Composition New Bin Import Bin... Import Media... Import Media from XML... Import Subtitle... Remove All Clips in Bin... Relink Clips for Bin... Auto Sync Audio 1-4 Ctrl+l ](Exported%20image%2020241106113946-7.png)

Go to the **location** where the media is placed on your computer or PC. **Choose the media** and click Open to display it on the DaVinci Resolve 18 application.

![0 EIE q) J eos uodxa L-Bq anotuaH ](Exported%20image%2020241106113947-8.jpeg)

### Step 02: Choose the 3D Keyer

Now, you need to remove the green screen background from the clip.  
Go to the ‘Effects Library’.  
Next, **choose the 3D Keyer option**:

- Choose the ‘Resolve FX Key’ option.
- Click the ‘3D Keyer’.
- Next, click and drag the ‘3D Keyer’ and place it over the green screen clip in the timeline.

![DaVinci Resolve - Remove bg-l OaVinci Resolve File Edit Trim Timeline Clip Mark Transitions Favorites View Playback Search Fusion Effects Media Pool Video Audio Sync Bin Generators Color Fairlight Remov jÉit Resolve FX Generate Color Generator Grid Resolve EX Key 3D Keyer HSL Keyer Resolve EX Light Aperture Diffraction Halation Color palette Alpha Matte Shrink and Grow Glow Lens A are ](Exported%20image%2020241106113949-9.jpeg)

### Step 03: Remove the green screen

**To pick the Open FX Overlay option**,

- Click on the green screen clip with the 3D Keyer.
- Go to the Viewer and choose the ‘Open FX Overlay’ option as displayed below.

![Media Pool Smart Bins rd5 v Toolbox Video Audio Transit'... Generators v open FX Eff«ts Resolve EX Key 2. 30 Remove bg-l Transform Crop Dynamic Zoom Open PX Overlay Fusion Overlay Annotations Metadata 7.16:oc 4,) Video t DaVinci Resolve 18 ](Exported%20image%2020241106113950-10.jpeg)

Next, go to the Inspector and click on the Effects button which includes three tools.  
Click n the first tool which is named **Pick**.

![ound Library Timeline - producti Remove bg-l Edited Mixer Timeline 1 Video 3D Keyer Stro ke Behaviour Options Metadata p4 open EX hvert Delete Stroke Reset YUV Inspector Luma Color Space Soft Despill usage Options Key Adjustments Matte Finesse Garbage Matte v Output Flat Tight e.) ](Exported%20image%2020241106113955-11.jpeg)

Then, click on the green screen in the Viewer. As soon as you click, you would notice that the green screen disappears.

### Step 04: Resize the Content on the clip

If you want to **resize the subject after removing the green screen**:

- Go to the Viewer and click on the ‘Open FX’ option to reveal the drop-down menu.
- Next, choose ‘Transform’.
- Adjust the size of the subject using the control handles.

![> Key Adjustments > Matte Finesse Garbage Matte v Output Transform Crop Dyn a mic Zoom Open FX Overlay Fusion Overlay Annotations u. Video 1 ](Exported%20image%2020241106113956-12.jpeg)

## How to Remove a solid Colored Background Using DaVinci Resolve

In this tutorial, we will teach you to remove a **solid colored background**. To do this, we will use the Color Picker tool.

### Step 01: Setting up the document

Initially, you need to **open a clip or project**,

- Open the **DaVinci Resolve 18** application.
- **Right-click** on the media pool section.
- Choose the option **Import Media** as displayed below.
- Alternatively, use the keyboard shortcut Ctrl/Cmd+I to open the media.

![Timelines Create New Timeline Using Selected Bin... Create New Multicam Clip Using Selected Bin... New Fusion Composition New Bin Import Bin... Import Media... Import Media from XML... Import Subtitle... Remove All Clips in Bin... Relink Clips for Bin... Auto Sync Audio 1-4 Ctrl+l ](Exported%20image%2020241106113957-13.png)

Drive to the **location** where the media is placed on your computer or PC. **Choose the media** and click Open to display it on the DaVinci Resolve 18 application.

### Step 02: Edit page > Set the Timeline

**To go to the Edit page,**

- Go to the bottom of the screen.
- Click on the ‘Edit page’ icon.

![Exported image](Exported%20image%2020241106113959-14.png)

Click and drag the video to the timeline and set the timeline as preferred.

### Step 03: Color page > Add Alpha Output

**Go to the Color page**,

- Go to the bottom of the canvas.
- Click on the ‘Color page’ icon.

![Edit Soft Clip Keyfra mes Master a > Corrector 1 a > Sizing 100 100 High 50.0 ](Exported%20image%2020241106114000-15.png)

Next, go to the Node Editor.  
**In the Node Editor**,

- Right-click on the node section.
- Click the option ‘Add Alpha Output’ to add to the nodes.

![Remove bg-2 cups v Timeline I Clip 30 01 -a: NodU Éff«t5 Clip v • Reset Grades and Ctrl*Home Add Node Add Add Alpha Output Zoom Out to Window Onginal Size Togge Display Mode Cleanup Node Graph 4,) H.264 High L5.2 Tracker - Window Il pan Tilt zoom Interactive Mode DaVinci Resolve 18 Rotate Frame 1 023 896 Cloud Tracker v ](Exported%20image%2020241106114001-16.jpeg)

- The blue point indicating the Alpha Channel will be added to the Node Editor.
- Simply, join it with the blue output of the clip.

![@ Effects Clips Nodes Clip Lightbox ](Exported%20image%2020241106114003-17.jpeg)

### Step 04: How to use the Color Picker and remove the background

Go to the Centre Palettes and,

- Choose the **‘Qualifier**‘ Palette.
- Click on the ‘Color Picker’ (first icon).
- Go to the Viewer and click on the background colour you want to remove.
- Once you click on it, the colour is selected by the Color picker and stored on it.
- Click on ‘Invert’ (last icon) to invert the colour selection.

![Qualifier - HSL Hue center 50.0 Saturation Low 0.0 Luminance Low 0.0 Width 100.0 100.0 Soft L. Soft 0.0 0.0 Sym H. Soft O 50.0 0.0 Matte Finesse Clean Black Clean White Black Clip White Clip Blur Radius In/Out Ratio Scopes 1023 512 100-0 100.0 L.soft 0.0 H.soft 0.0 DaVinci Resolve 18 ](Exported%20image%2020241106114008-18.jpeg)

That’s it! Now you would notice that the solid colored background has been removed. To refill the colours or edit them further, you can use various effects. That’s it for removing solid colored background in DaVinci Resolve 18.

![Hue center 16.8 Saturation Low 0.0 Luminance o Width High High 54.6 3.1 soft 3.2 L. soft 0.0 Sym H.soft 0.0 H.soft 2.6 Matte Finesse Pre-Filter Clean alack Clean White Black Clip White Clip Blur Radius In/Out Ratio 1 oco 774 L. soft 2.6 ](Exported%20image%2020241106114010-19.jpeg)

## Cut out objects or persons from the background in DaVinci Resolve 18

In this section, you will learn how to cut out an object or a person from the background. The basic steps we will learn include masking, tracking and finally exporting the clips.

### Step 01: Importing Media

Initially, you need to **open a clip or project**,

- Open the **DaVinci Resolve 18** application.
- **Right-click** on the Media Pool section.
- Choose the option **Import Media** as displayed below.
- Alternatively, use the keyboard shortcut Ctrl/Cmd+I to open the media.

![Timelines Create New Timeline Using Selected Bin... Create New Multicam Clip Using Selected Bin... New Fusion Composition New Bin Import Bin... Import Media... Import Media from XML... Import Subtitle... Remove All Clips in Bin... Relink Clips for Bin... Auto Sync Audio 1-4 Ctrl+l ](Exported%20image%2020241106114012-20.png)

Go to the **location** where the media is placed on your computer or PC. **Choose the media** and click Open to display it on the DaVinci Resolve 18 application.

### Step 02: Masking

Start by selecting the clip you want to mask from the timeline before proceeding. Next, go to the Color page.  
**To go to the Color page,**

- Go to the bottom of the screen.
- Click on the ‘Color page’ icon.

![Edit Soft Clip Keyfra mes Master a > Corrector 1 a > Sizing 100 100 High 50.0 ](Exported%20image%2020241106114013-21.png)

The colour window offers multiple options in the colour tab. To remove the background from the clip, we use **Magic Mask**. Note that the Magic mask option is available only in the DaVinci Resolve 18 **studio version**.  
Once you go to the Color page, click on the Magic Mask icon to display its editing features of it.  
Under the timeline, you can pick the clip you wish to apply the masking to and use it to remove the background.  
If you go to the top right corner of that window, you will notice **two options** indicated as follows:

- **Object mask**: Used to mask objects in the clip. But, works well for people also.
- **Person mask**: Used to mask persons in the clip.

Now, choose the subject you want to mask and change the type of quality to ‘better’ to work faster. Then, choose the **Color Picker Add icon** (Color picker with a plus icon). This allows you to select the regions you want to apply the mask to.  
To apply the masking, click and drag on the regions of the subject to help the tool identify the person in the clip. It helps to automatically detect the person and cut it out from the clip.  
If you want to see the mask that is applied, toggle the visibility option to look through it.

### Step 03: Tracking

In this section, you will **track** the mask you created from the above steps. The tracking helps to identify the subject detected throughout the clip.  
Click on the **track forward button** and let the mask track in a forward direction. Next, click on the **track backward button** and lets the mask track in the backward direction.

![Tracker - Window 11 01 Interactive Mode pan Tilt Zoom Rotate 01 3D Clip Frame 01 0.00 Info Clip File Name pexels-e start TIC Duration Version Source Res 0.00 Cloud Tracker v ](Exported%20image%2020241106114015-22.jpeg)

While you are tracking, if the tracking doesn’t end up as expected, you can pause the clip in that specific frame. Then, choose the plus or minus Qualifier tool to add or remove a section from the mask.  
For example, to remove a section from masking, click on the Qualifier Subtract tool and click and drag from the preview window to remove it. Then, track the clip again.

### Step 04: Exporting

In order set the clip apart and export it for other purposes, you need to add the **Alpha output**.  
To add Alpha output,

- Right-click on the **Nodes Editor**.
- Choose the option ‘Add Alpha output’.

Now, connect the blue node of the Alpha output to the blue output of the clip.  
Now that you have set apart the subject and background of the image, you can add another background, title, or do anything as per your requirement.

## Conclusion

In conclusion, **removing the background** from a video clip is an essential skill for any video editor, and DaVinci Resolve 18 provides a powerful set of tools and features to accomplish this task with ease.  
By following the step-by-step guide outlined in this article, you can remove the background from your videos, **isolate your subjects**, and create stunning composites that will take your videos to the next level.

## Author Rating

[Practice](https://edits101.com/video-editing-ratings/)  
[Scalability](https://edits101.com/video-editing-ratings/)  
[Difficulty](https://edits101.com/video-editing-ratings/)  
[Functionality](https://edits101.com/video-editing-ratings/)

### Overall Rating

**3.625**

### Summary

In summary, there are various ways to remove backgrounds of black, white, green or solid colors in DaVin ci Resolve 18. Depending on your requirements, follow this tutorial and start removing backgrounds from your clips in no time!  
[Check out how the rating system works](https://edits101.com/remove-background-in-davinci-resolve-18/)

### Useful Links

[Learn more](https://www.reddit.com/r/davinciresolve/comments/kqujbr/how_to_remove_a_background_on_a_subject/)  
[Learn more](https://forum.blackmagicdesign.com/viewtopic.php?f=21&t=148807)  
[Learn more](https://www.reddit.com/r/davinciresolve/comments/tinh1m/need_help_cutting_away_a_background_without_a/)  
[Learn more](https://www.reddit.com/r/davinciresolve/comments/ootbbz/da_vinci_resolve_removing_background_and_adding/)