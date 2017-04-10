Release Android: C:\va\vetassist\platforms\android\build\outputs\apk
Release Android: C:\va\vetassist\platforms\ios\build\outputs\apk
To Create Signed APK Below are  steps : 

Create a file called release-signing.properties and put in  \platforms\android folder

storeFile=C:/va/vetassist/app.keystore
storeType=jks
keyAlias=vetassist
keyPassword=vetassist
storePassword=vetassist

Fire below command to release build :
cordova build android --release