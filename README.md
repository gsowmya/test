***** Please create a separate workspace for android studio.DO NOT use existing one.

Prerequisite:
1.Download Android Studio:
https://developer.android.com/sdk/index.html
2.Download NDK:
https://developer.android.com/ndk/downloads/index.html

Android Studio Steps:

1.Checkout “Studio-Migration” branch from stash for all the libraries.
2.Open Android Studio and choose “open existing Andriod Studio” project. 
Provide the path till KPFlagshipMain and click open
Ex: ../../../kpflagship/KPFlagshipMain.
4.Set GRADLE_HOME 
Ex:
Set ndk.dir path in local.properties file.

![ScreenShot](/Users/sowmyavuddaraju/Desktop/path.png)


Using Gradle Command Line:

gradle tasks
Shows all tasks runnable from root project.
Move to  ../../../kpflagship/KPFlagshipMain> gradle tasks

gradle  assembleDebug
creates apk file in the following location:
../kpflagship/KPFlagship/build/outputs/apk


References:

http://stackoverflow.com/questions/21109019/android-gradle-replace-package-name-for-a-value-in-manifest
https://github.com/mikepenz/MaterialDrawer/issues/73

http://developer.android.com/guide/topics/ui/themes.html
http://stackoverflow.com/questions/19508649/android-studio-says-cannot-resolve-symbol-but-project-compiles

