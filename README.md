# ARUsabilityMetricsEnvironment

# Setup Environment
## Requirements
* Unity - Editor Version 2020.3.38f1
* Microsoft Visual Studio 2022
* HoloLens 2 Device
* Mixed Reality Tookkit Version 2.8.2.0

## Steps
### Unity
### HoloLens 2
Follow this link
* How to build AR Application to HoloLens 2 - [LINK](https://arvrjourney.com/how-to-build-your-ar-application-to-your-hololens-2-ca0640a01246)
     
<OR> 
 
1. Open the solution with Microsoft Visual Studio 2022
* Set the Solution Configuration to Release
* Set the Solution Platform to ARM64
* Set the Machine Name for Debugging.
    * From the Visual Studio menu; Project -> Properties
    * Under Configuration Properties, click Debugging
    * Under Debugger to launch, choose Remote Machine
    * In the section below, edit the Machine Name to the IP Address of the HoloLens 2

# Running Tests
* Task 2
     <a href="http://www.youtube.com/watch?feature=player_embedded&v=mOAlquvPvFo" target="_blank">
          <img src="http://img.youtube.com/vi/mOAlquvPvFo/0.jpg" alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" />
     </a>
    * Binary
        * [link](bit.ly/3V4ftrG)
        * [instructions](https://docs.microsoft.com/en-us/hololens/app-deploy-app-installer#installation-method)

    * When the Application runs, the HoloLens 2 view is being recorded as a video, locally and the user interactions are being recorded to Cognitive3D.
## Cognitive3D
* Open the [Dashboard](https://app.cognitive3d.com/organizations), Login needed.
* Click on the `National Institute of Standards and Technology` Organization.
* Click on the `AR Usability Environment` Project.
* One the left side of the window, under `Project`, click `Scenes`
* Click the scene `ARBaselineEnvironmetScene`.
* Under the sessions, you will see all of the recorded Sessions.
    * Cool little thing to note, that if you currently have a session running, you can click `View in SceneExplorer` to see the lastest recording, even if it isn't showing up on the list yet.

# Running Application
* Task 2
    * When the application starts up, you are presented with two cubes, which you are able to grab with your index finger and thumb to move around.
## Unity

You can test holographic object behavior with the Unity in-editor input simulation features.

To run the simulation, Press the play button.

* *Change the view in the scene:*
    * To move the camera forward/left/back/right, press the W/A/S/D keys.
    * To move the camera vertically, press the Q and E keys.
    * To rotate the camera, press the right mouse button and then drag.

* *Simulate hand input:*
    * To enable the simulated right hand, press and hold the space bar. To remove the hand, release the space bar.
    * To enable the left simulated hand, press and hold the left shift key. To remove the hand, release the key.
    * To move either hand around the scene, move the mouse.
    * To move the hand forward or backward, rotate the mouse scroll wheel.
    * To simulate the pinch gesture, click the left mouse button.
    * To rotate the hand, press and hold down the space bar + CTRL key (right hand) or left shift key + CTRL key (left hand) and then move the mouse.

* *Persistent hands*
    * To enable a hand and keep it onscreen without continuing to hold down a key, press T (left hand) or Y (right hand). 
    * To remove the hands, press those keys again.

## HoloLens 2
*The Visual Studio project is located at: `HoloLens2Project/ARBaselineEnv.sln`* 

When running the application, the HoloLens 2 view is being recorded. The video can be found by opening the File Explorer in the Windows Device Portal. (System -> File explorer) 

The Windows Device Portal is opened while navigating to the webaddress of the HoloLense 2, while it is activated. 

The video is located in: `User Folders\LocalAppData\AugmentedRealityBaselineEnvironment*\LocalState\ARBaselineEnv_*.mp4`, where the asterisk represents a generated string, which changes every install. 

