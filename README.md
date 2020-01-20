# Android Studio集成OpenCV及OpenCV contrib库

                
1. 新建项目后 在Android Studio中下，通过`File->New->Import Module..`导入`OpenCV-android-sdk/sdk/java`
2. 更改OpenCVLibrary下的gradle内的版本信息 与Android项目的gradle版本信息统一(包含`compileSdkVersion` `minSdkVersion` `targetSdkVersion`)
3. 通过`File->Project Structure`在左侧`Modules`内选择`app`, 右侧进入`Dependencies` 点击加号选择`Module dependency`将OpenCVLibrary导入 
4. 复制`OpenCV-android-sdk/sdk/native/libs`内的文件至android项目的`app/src/main`文件夹下

## ojrk!
