# CameraXApp21
CameraXApp following Android tutorial (available at 
https://developer.android.com/codelabs/camerax-getting-started?authuser=1#0) and using 
Android Studio Dolphin (2021.3.1.17).

## Android Studio
The tutorial says it will work with Android Studio Arctic Fox 2020.3.1 or above:  unfortunately this isn't the case. 
With Android Studio Arctic Fox there are problems related to XML 3 syntax. 
With Jellyfish many more problems linked to an updated build system. 
With some trial and error I found that Dolphin supports XML 3 syntax and raises just a few errors that are easy to fix. 

## Changes
Project settings: 
> minSdk 24
> compileSdk 33

Withous these changes I was getting many erros and warning when building the project. 

MainActivity.kt: 
> import com.example.cameraxapp21.databinding.ActivityMainBinding 
 
Thi fix is simply due to the fact that I used a different project name from the tutorial. 
