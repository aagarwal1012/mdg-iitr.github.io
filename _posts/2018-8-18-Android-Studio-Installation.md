---
layout: post
title: Android Studio Installation
tagline: Android Studio Installation.
visible: 1
category: Introduction
tags: [intro]
---

## Why Develop For Android?


With over **1 billion** Android devices already activated, Android represents an incredible opportunity for developers.
Android Studio is a latest and most widely accepted IDE designed by Google itself. If you want to develop apps in android then it is highly recommended to use Android Studio.

----------

## Quick Overview ##
A typical native android application is written using XML for the frontend (the User Interface) and JAVA for the backend.

----------
**JAVA**
All the programming part in android development is done using JAVA. Although it’s a great advantage, if you know a thing or two about programming in Java, but even if you know any object oriented programming language, then it will not be much difficult to relate to the concepts used during development. In short if you know C++ or C then also you are at peace.


----------
**XML**
This is used to build the app’s user interface. All user interface elements in an Android app are built using View and ViewGroup objects. It has drag and drop User Interface


----------
**Running the app**
An android application can run either on your device or in the emulator that comes bundled with the SDK. Since the emulators can be slow, it is always recommended to use an actual device. [This link](http://developer.android.com/intl/zh-cn/training/basics/firstapp/running-app.html) contains the detailed explanation for setting up your device/emulator for testing.


----------

Installation of Android Studio
------------------

JDK and JRE are essential for JAVA to run on your machine.

## Windows Users
(linux users click [here](#linux_users))

### Installing JAVA

Follow [the link](http://www.oracle.com/technetwork/java/javase/downloads/index.html) and click Java Platform (JDK) 8u144 photograph. It redirects to a new page on which select Accept the license and download the version which is best suited with your machine.
After installing the JDK, you need to set the environment variable JAVA_HOME path and for that: 
 
1. For this, right-click on the 'This PC' icon on your desktop and select 'Properties'. On the next screen that appears, go to 'Advanced system settings' item. On the 'System Properties' window that appears, select the 'Environment Variables' button.      
<a href="{{ "images/installation/system_properties.png" | prepend: site.asset_add }}">
    <img src="{{ "images/installation/system_properties.png" | prepend: site.asset_add }}" alt="System Properties">
</a> 

2. The 'Environment Variables' window will appear (see figure below). Click on the 'New...' button.  
<a href="{{ "images/installation/environment_variables.png" | prepend: site.asset_add }}">
    <img src="{{ "images/installation/environment_variables.png" | prepend: site.asset_add }}" alt="Environment Variables">
</a> 

3. The 'New System Variable' window will appear (see the figure below). Enter 'JAVA_HOME' as the variable name andC:\Program Files\Java\jdk1.8.0_144' as the variable value. Then click the 'OK' button.  
<a href="{{ "images/installation/new_system_variable.png" | prepend: site.asset_add }}">
    <img src="{{ "images/installation/new_system_variable.png" | prepend: site.asset_add }}" alt="New System Variable">
</a>

4. Scroll down the 'System variables' window until you see the 'Path' item, then click on it. Then click on the 'Edit...' button. The 'Edit Environment Variable' window will appear. Click on the 'new' button then type the following into the field that gets highlighted:

```
  C:\Program Files\Java\jdk1.8.0_144\bin\
``` 
The completed screen will look something like this:

<a href="{{ "images/installation/edit_path_screeenshot.png" | prepend: site.asset_add }}">
    <img src="{{ "images/installation/edit_path_screeenshot.png" | prepend: site.asset_add }}" alt="Edit Environment Variable">
</a>

For reference, one can visit [this link](http://ridz1ba.blogspot.in/2015/01/how-to-install-oracle-java-and-andoid.html) 

### Installing IDE

• Go to [this link](http://developer.android.com/sdk/index.html) and select “Download Android Studio for Windows”.

• Check the “ I have read and agree with the above terms and conditions” box and Download Android Studio For Windows.

• Install studio after downloading.

• Open the Android Studio. A window similar to the below one would appear.
<center>
    <a href="{{ "images/installation/configure.png" | prepend: site.asset_add }}">
        <img src="{{ "images/installation/configure.png" | prepend: site.asset_add }}" alt="New Project" style="width:80%;">
    </a>
</center>

• Click on configure and choose SDK Manager in drop down menu.   
<center>
    <a href="{{ "images/installation/configure_linux.jpg" | prepend: site.asset_add }}">
        <img src="{{ "images/installation/configure_linux.jpg" | prepend: site.asset_add }}" alt="Configure">
    </a>
</center>

Install following packages
<center>
    <a href="{{ "images/installation/SDKTools.jpg" | prepend: site.asset_add }}">
        <img src="{{ "images/installation/SDKTools.jpg" | prepend: site.asset_add }}" alt="Configure" style="width:100%;">
    </a>
</center>


Head to [recommended](#recommended) section for things you'll need for this lecture  

___
<a name="linux_users"></a>
## Linux Users

### Installing JAVA

There is no need to install Java as latest Android Studio versions already come with JDK bundled with it. [See here](https://stackoverflow.com/a/42182755/7263373) for more information.

### Installing IDE

1. Get your Android Studio from [here](https://developer.android.com/studio/ "Android Studio download page").

2. Click on the Download Android Studio button and accept the terms to get your download started.

3. Extract the file where you want to install Android Studio. Preferred installation location is the user's home directory (~) or the opt directory (/opt).

4. In terminal type:

   ```shell
   cd /{Location where you extracted}/android-studio/bin
   ```
   and then  
   ```shell
   sh studio.sh
   ```

5. A dialog appears like the one below. Select _do not import settings_.
   <a href="{{ "/images/installation/import_settings.png" | prepend: site.asset_add }}">
	   <img src="{{ "/images/installation/import_settings.png" | prepend: site.asset_add }}" alt="New Project" style="width:100%;">
   </a>
   
6. You will now see the Android Studio Setup wizard as shown below.
   <a href="{{ "/images/installation/setup_wizard_start.png" | prepend: site.asset_add }}">
	   <img src="{{ "/images/installation/setup_wizard_start.png" | prepend: site.asset_add }}" alt="New Project" style="width:100%;">
   </a>
   
7. Keep on clicking next until you see a Dialog similar to one below. Click Finish.
   <a href="{{ "/images/installation/setup_wizard_finish.png" | prepend: site.asset_add }}">
	   <img src="{{ "/images/installation/setup_wizard_finish.png" | prepend: site.asset_add }}" alt="New Project" style="width:100%;">
   </a>

8. Wait while Android Studio downloads necessary components. Click Finish.
   <a href="{{ "/images/installation/downloading_components.png" | prepend: site.asset_add }}">
	   <img src="{{ "/images/installation/downloading_components.png" | prepend: site.asset_add }}" alt="New Project" style="width:100%;">
   </a>

9. The Android Studio window shall open. Click the option *Create Desktop Entry* from the *Configure Menu* to create shortcut to android studio in launcher. This avoids the need to open the terminal each time you want to launch the Studio.
   <a href="{{ "/images/installation/desktop_entry.png" | prepend: site.asset_add }}">
	   <img src="{{ "/images/installation/desktop_entry.png" | prepend: site.asset_add }}" alt="New Project" style="width:100%;">
   </a>


<a name="recommended"></a>
## **Recommended**

__Bring your USB cable so that you can test application on your own device!__  

**(For first time users)**  
1. Ensure an interent connection on your machine
2. Start Android Studio
3. Click *Start a new Android Studio Project*
4. On screen *Configure you new project* leave default options and click *Next*
5. Leave default options unchanged and click *Next*.
6. Select *Empty Activity* and click *Next*.
7. Leave default options unchanged and click *Finish*.
8. If Gradle build fails (check the status bar at the bottom) and Android Studio asks to download additional packages, allow it.
9. Keep repeating *step 8* till you get a successful gradle build (status bar will say: Gradle build finished).
10. Keep this project open as you will run this test app on your phone later.

**(Enable USB Debugging in your phone and run)**  
* Follow [this](https://www.embarcadero.com/starthere/xe5/mobdevsetup/android/en/enabling_usb_debugging_on_an_android_device.html "usb debugging") to enable USB debugging in your Android phone.

**(Run the Test app on your phone)**  
1. After following the above two steps, it's time to build and run your first test app (A HelloWorld app, if you will) on your phone.
2. Connect your phone to your PC via the usb cable.
3. Allow USB debugging if asked to in your Android device.
4. Now, open the empty Project we created before in Android Studio.
5. Click *Run 'app'* (<key>Shift</key> + <key>F10</key>) option in the *Run* menu.
6. A dialog should appear allowing you to select your device.
   <a href="{{ "/images/installation/run_app_on_phone.png" | prepend: site.asset_add }}">
	   <img src="{{ "/images/installation/run_app_on_phone.png" | prepend: site.asset_add }}" alt="New Project" style="width:100%;">
   </a>
7. Click *OK* and wait for your first app to run on your own phone.


These steps are necessary for first time user to ensure everything is downloaded when you come to the lecture. 

If you have any trouble setting up your development environment, feel free to [contact us](/chat "MDG chat")!

## **Some Common errors:**
* Unable to access android sdk add-on list:
[First run of Android Studio. Unable to access Android SDK add-on list](http://stackoverflow.com/questions/29878370/android-studio-first-run-error)
	1. Turn off the firewall.
	2. Run Studio again.
	3. Add android files to trusted files in your windows firewall and restart the firewall.
* Your Android SDK is missing, out of date, or is missing templates. You can configure your SDK via Configure -> Project Defaults -> Project Structure -> SDKs: 
    * [Your Android SDK is missing , out of date,or is missing templates](http://stackoverflow.com/questions/26796724/your-android-sdk-is-missing-out-of-date-or-is-missing-templates)
* Unable to locate adb within SDK:   
    * [ADB error on Android SDK. Using Linux Ubuntu 64 bit 12.10](http://stackoverflow.com/questions/14421171/adb-error-on-android-sdk-using-linux-ubuntu-64-bit-12-10) - StackOverflow  
    * [Error:Unable to locate adb within SDK in Android Studio](http://stackoverflow.com/questions/27301960/unable-to-locate-adb-within-sdk) - StackOverflow  

## **Links to kick start with developing Android apps**
[thenewboston](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBsvRxJJOzG4r4k_zLKrnxl) : Youtube channel to get you started.

**Some basic links to grasp a bit of more knowledge:**  
- [What is difference between JDK and JRE](http://stackoverflow.com/questions/1906445/what-is-the-difference-between-jdk-and-jre) - StackOverflow  
- [What does Java home environment variables do?](http://stackoverflow.com/questions/5102022/what-does-the-java-home-environment-variable-do) - StackOverflow  

For any queries feel free to ask down in comments or [chat with us](/chat) !
