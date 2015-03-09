# Flashlight

add perimission in the manifiest

<uses-permission android:name="android.permission.CAMERA" />
<uses-feature android:name="android.hardware.camera" />

----------------------------------------------------
//Androidmanifiest

<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
package="com.example.ensch.flashlight" >
<uses-permission android:name="android.permission.CAMERA" />
<uses-feature android:name="android.hardware.camera" />
<application
android:allowBackup="true"
android:icon="@mipmap/ic_launcher"
android:label="@string/app_name"
android:theme="@style/AppTheme" >
<activity
android:name=".MainActivity"
android:label="@string/app_name"
android:screenOrientation="portrait">
<intent-filter>
<action android:name="android.intent.action.MAIN" />

<category android:name="android.intent.category.LAUNCHER" />
</intent-filter>
</activity>
</application>

</manifest>

latest commit ed6406edd4
ensch89 ensch89 authored 2 minutes ago
	Flashlight 	Flashlight 	2 minutes ago
	.gitattributes 	:circus_tent: Added .gitattributes & .gitignore files 	7 minutes ago
	.gitignore 	:circus_tent: Added .gitattributes & .gitignore files 	7 minutes ago
