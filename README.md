# DetectiveApp
Detective tool to record voice and click pictures. Developed using ionic cordova. Developed as an asignment of Internet Technologies. 

<b>Objective:</b> Use Camera and voice recorder in the app.
<p>
<b>1. Setting up your development environment for Ionic projects</b> <br>
Please refer the following link to do the initial setup of Ionic framework.
https://ionicframework.com/docs/intro/installation/ <br>
Packages to be installed:<br>
i. Node.js: https://nodejs.org/en/<br>
ii. NPM(Node Package Manager): It get installed with Node.js<br>
iii. After installing i & ii check the installation with npm --version and node --version. If installed correctly, 
install Ionic CLI and Cordova using the command <br> <b>sudo npm install -g ionic cordova</b><br>
iv. For building an app we need Java and android SDK.<br>
  Java Download(JDK 1.8): http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html. <br>Please download 1.8 version only<br>
v. Download Android Studio from https://developer.android.com/studio/<br> 
  If gradle doesn't get installed with Android studio, download it from https://gradle.org/install/.<br>
vi. For Ubuntu, after installing all the above softwares. Update the path in ~/.bashrc file.<br>
add these lines at end of the file. Please make sure to change the path as per your installation folder<br>  
<Pre>export JAVA_HOME="/opt/java/jdk1.8.0_181"
export ANDROID_HOME="/home/swapnil/Android/Sdk"
export PATH={$PATH}:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools:$ANDROID_HOME/build-tools
export GRADLE_HOME="/opt/android-studio/gradle/gradle-4.4/bin"
export PATH=${PATH}:$GRADLE_HOME
  </Pre>
</p>
<p>
Now you are ready to do the app development.
</p>
<br><br>
<b>2. Writing the Code </b>
<br>
<br>
<b>3. Building and testing the app </b><br>
  There are several ways to test the app, we see how to build and test the app on our own android phone.<br>
  Two ways to do the same: 
  <ol>
  <li> Build the apk on system and then copy it to the phone, install and test.<br> 
  <ul>
    <li> Build the apk: <b>ionic cordova build android </b><br> Apk is generatec at this location ../platforms/android/app/build/outputs/apk/debug</li>
    <li> Copy the apk to phone through usb or mail or anything.</li>
    <li> Install the apk and test the funcionality of the app.</li>
   </ul>
  </li>
  <br>  
  <li> Using the USB debugging from Developer options on phone. 
  <ul>
    <li>Activate the developer options in phone.<a href="https://developer.android.com/studio/debug/dev-options">Check</a></li>
    <li>Turn on USB Debugging in developer options from settings.</li>
    <li>Run cmd on system:  <b>ionic cordova run android --device</b></li>
    <li>The above command will install the app on the phone. Now test it.</li> 
    
   </ul>
   </li>
  </ol> 
  
