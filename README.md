# In this fork

![Modified UI](/doc/screen.png?raw=true "Modified UI")

# TimeLapse
A time lapse app for Sony Alpha cameras using the [OpenMemories: Framework](https://github.com/ma1co/OpenMemories-Framework).

I have only a a6300 to test it, if you have another camera I would be happy to receive bug reports.

## Installation ##
Use [Sony-PMCA-RE](https://github.com/ma1co/Sony-PMCA-RE) or install through [sony-pmca.appspot.com](https://sony-pmca.appspot.com/apps).

Thanks to [ma1co](https://github.com/ma1co) for creating this amazing framework and [obs1dium](https://github.com/obs1dium), I used FocusBracket as a code base.

## Usage ##
The app is easy to use. It doesn't have any controls for shutter speed, aperture, ISO, picture quality etc. Adjust all this settings before starting the app, it will use them. If you don't want the camera to focus before each shot, set the camera to manual mode.

Then start the app set the shoot interval and the amount of pictures it should take. Below the seek bars you can see how long it will take to shoot all the photos and how long the video will be. The fps setting only changes the calculation of the video length, the app doesn't produce a video.

Finally click the start button and wait.

You can stop by clicking the MENU button on the camera.

The silent shutter option is functionless on cameras without silent shutter mode.

## Known Issues ##

If the app crashes the camera, please try the following camera settings. They were reported to work with the RX100 M4.
 - The silent shutter needs to be disabled or unchecked in the app, on some cameras
 - The app will not run if you are set or self time or continous shooting - Only Single shoot will work.
