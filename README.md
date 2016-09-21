
1-前言
================
引用地址：
-- HTTP: https://github.com/han1202012/NDKHelloworld.git 
-- SSH : git@github.com:han1202012/NDKHelloworld.git
作用：NDK 开发JNI的流程，生成SO库 

2-实验目的：
==============
	Android NDK方式编译生成so动态库
3-开发工具：
==============
	Notepad++
	android-ndk-r8b
4-工程目录：
==============
		NDKexample1
		│  README.md
		│
		└─jni
			 Android.mk
			 hello.c
5-编译与运行结果：
============
	4.1 ndk-build
		NDKexample1\jni>ndk-build
		"Compile thumb : hello <= hello.c
		SharedLibrary  : libhello.so
		Install        : libhello.so => libs/armeabi/libhello.so
	4.2 libhello.so
