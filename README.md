1-实验目的：
==============
	Android NDK方式编译生成so动态库
2-开发工具：
==============
	Notepad++
	android-ndk-r8b
3-工程目录：
==============
		NDKexample1
		│  README.md
		│
		└─jni
			 Android.mk
			 hello.c
4-编译与运行结果：
============
	4.1 ndk-build
		NDKexample1\jni>ndk-build
		"Compile thumb : hello <= hello.c
		SharedLibrary  : libhello.so
		Install        : libhello.so => libs/armeabi/libhello.so
	4.2 libhello.so
