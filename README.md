# iOS-10-adaptation


更新中...
#####一、权限
在调用相机或相册时需要加入权限申请描述，在 info.plist文件中加入
`NSCameraUsageDescription`和`NSPhotoLibraryUsageDescription`

![Info.plist — Edited Xcode, Yesterday at 12.14.47 P](http://7xpsn4.com1.z0.glb.clouddn.com/2016-09-11-Info.plist — Edited Xcode, Yesterday at 12.14.47 PM.png)

--
#####二、关闭疯狂的Log
在 Scheme 设置里加入OS_ACTIVITY_MODE ，设置为 disable  
操作步骤：
`Product->Scheme->Edit Scheme-> Run -> Arguments`

![Xcode Xcode, Today at 11.49.55 P](http://7xpsn4.com1.z0.glb.clouddn.com/2016-09-15-Xcode Xcode, Today at 11.49.55 PM.png)

#####三、开启注释
打开终端，运行如下命令，然后重启Xcode：
``` sudo /usr/libexec/xpccachectl```




