#Simple.cs

####Location: *FuseeExampleProject/Core/Simple.cs*
We used the SimpleExample as a base project


##Changes
* Use sensor data as view orientation (Pan, Tilt and Roll)
* Use Cardboard render mode for stereo rendering
* Reset view on touch
* Rendering can be toggled between stereo and mono rendering with the *_renderStereo* boolean
* GUI can be used per-eye or for the whole-screen
* Field of view should fit the [cardboard viewers fov](http://www.virtualrealitytimes.com/2015/05/24/chart-fov-field-of-view-vr-headsets/)
* Distance between eyes can be changed with the *_eyeDistance* variable
* Use WuggyLand scene instead of Rocket

**Bug:** Width and Height are 0 in Init on Android device
