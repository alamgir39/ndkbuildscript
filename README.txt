//go to jni folder where Android.mk and Application.mk located, then follow the command

export PATH=/home/alamgir/android-ndk-r14b:$PATH	// To export or set the path

export NDK_PROJECT_PATH=.   				// To mention current directory  

ndk-build NDK_APPLICATION_MK=./Application.mk 		// To build the native c/c++ code


ndk-build NDK_APPLICATION_MK=./Application.mk clean     //To clean the build




