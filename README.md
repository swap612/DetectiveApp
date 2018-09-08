# DetectiveApp
Detective tool to record voice and click pictures. Developed using ionic cordova. Developed as an asignment of Internet Technologies. 

<b>Objective:</b> Use Camera and voice recorder in the app.
<p>
<b>1. Installation Steps</b> <br>
Please refer the following link to do the initial setup of Ionic framework.
https://ionicframework.com/docs/intro/installation/ <br>
Packages to be installed:<br>
i. Node.js: https://nodejs.org/en/<br>
ii. NPM(Node Package Manager): It get installed with Node.js<br>
iii. After installing i & ii check the installation with npm --version and node --version. If installed correctly, 
install Ionic CLI and Cordova using the command <br> <b>npm install -g ionic cordova</b><br>
iv. For building an app we need Java and android SDK.<br>
  Java Download(JDK 1.8): http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html. <br>Please download 1.8 version only<br>
v. Download Android Studio from https://developer.android.com/studio/<br> 
  If gradle doesn't get installed with Android studio, download it from https://gradle.org/install/.<br>
vi. For Ubuntu, after installing all the above softwares. Update the path in ~/.bashrc file.<br>
add these lines at end of the file, Please make sure to change the path as per your installation folder<br>  
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
