# LIVE SNAP 2020 - ANDROID ONLY

## Who made this?
ICE 

## What is this app?
By default when uploading a gallery photo to Snapchat either to a friend or story, it will either send via chat or add a annoying watermark to your story. Chickencam eliminates this, by using Snapchat's developer kit you could completely bypass this.
### Use this to:
* Upload stock camera photos/videos without shitty snapchat quality
* High Quality Advertisments
* Custom GIF/Stickers

## Why this App?
People in the past have created similar apps and charged people hundreds of dollars just to use it. ChickenCam is completely free and open source so it will stop sketchy scammers

## Will I get banned for using this?
It is known that passed Snapchat tweaks would result in a ban, for example Casper, Snaptools, etc. However because this is directly from Snapchat's developer kit there is absolutely no chance of being banned. **Keep in mind there is a risk of someone reporting you for uploading something "nasty" -- be careful of who's on your friend's list.**

## Installation
*Refer to this [video](https://youtu.be/2FkhBCqLKNY) or follow the steps below*
**Before you even begin install Android Studio and your SDK version, download this zip.**
1. Create a account at https://kit.snapchat.com/portal/
  2. Create an app (Click Add button) - Only change name. Don't Disable/Enable anything. Click continue.
  **DO NOT SUBMIT FOR REVIEW AT ANY TIME**
  4. Scroll down to -Development Enviroment- and check android
  5. Copy and paste "com.snapchat.kit.creativesample" in "Add your name" ... Copy client ID after that
  6. Extract the ZIP anywhere, and open the project with android studio
  7. Find and Open androidmanifest and paste your code at android:value="(pastecode)"
  8. Go back to Snapkit and scroll to the bottom, and add your username
  9. Build>Generate Signed Apk>APK> ... Create a keypath> Next> Check V2 Full Signature> Finish
  10. Put apk on phone and install
  
 
  
  ### Snapchat limits the size and length of your video
  Snapchat limits the video size to below 10mb and 10 seconds. We could workaround this by compressing the video in the program Handbrake and splitting the video into 10 second clips.
  
