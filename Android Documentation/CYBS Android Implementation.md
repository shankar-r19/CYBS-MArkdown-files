
# Steps to port CYBS into Andorid


## 1. Running the project on Android 

Android Projects can be run in two ways, either using Unity Remote 5 or building the apk from build settings and installing it onto an andorid devie.

Note: AR is not currently supported using Unity Remote 5 but you can test out MRTK components.

 **To Enable Unity Remote 5**
> Project Settings> Editor >Unity Remote>Device Any Android Device

## 2. Making MRTK compatible to android

1. Select > Mixed Reality -> Toolkit -> Add to scene and configure (Follow the steps and apply recommended settings)
2. Select the MixedRealityToolkit object in the scene hierarchy.</br> 
<p align="center">
<picture>
  <img align="center"  src="https://github.com/shankar-r19/CYBS-MArkdown-files/blob/main/Android%20Documentation/Images/Step%201.png" width= "400" height="200">
</picture>
</p>
3.  In the Inspector Window select Clone the MRTK Profile to enable custom configuration.(only for Camera)
<p align="center">
<picture>
  <img align="center"  src="https://github.com/shankar-r19/CYBS-MArkdown-files/blob/main/Android%20Documentation/Images/pic%202.png" width= "400" height="300">
</picture>
</p>
