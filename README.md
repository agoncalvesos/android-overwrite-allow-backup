# android-overwrite-allow-backup

Plugin that uses a hook to change the android:allowBackup in AndroidManifest. 

## Why use this? 
If you want to force the allowBackup to always be false use this plugin, as it'll overwrite that setting (avoiding issues when you have another plugin that for some reason sets that property to true) 
