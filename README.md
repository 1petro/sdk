# NDK-toolcain
ndk compiler for android working nativly on 
android terminal 

# usage
[Build] 
```PATH="sdk/binutils-compact#2.23#1/bin:${PATH}" LD_LIBRARY_PATH=sdk/binutils-compact#2.23#1/lib:sdk/libcloog#0.18.0#1/lib:sdk/libgmp#5.0.5#1/lib:sdk/libisl#0.1.11#1/lib:sdk/libmpc#1.0.1#1/lib:sdk/libmpfr#3.1.1#1/lib sdk/gcc#4.8#2/bin/gcc-4.8 -c -g -DIDE=CppDroid -fPIE -Isdk/libstdc++-compact-dev#4.8#1/arm-linux-androideabi/include/c++/4.8 -Isdk/libstdc++compact-dev#4.8#1/arm-linux-androideabi/include/c++/4.8/arm-linux-androideabi -Isdk/ndk-sysroot-16#r9c#1/arm-linux-androideabi/include -Isdk/gcc#4.8#2/lib/gcc/arm-linux-androideabi/4.8/include```

[Link]
```PATH="sdk/binutils-compact#2.23#1/bin:${PATH}" LD_LIBRARY_PATH=sdk/binutils-compact#2.23#1/lib:sdk/libcloog#0.18.0#1/lib:sdk/libgmp#5.0.5#1/lib:sdk/libisl#0.1.11#1/lib:sdk/libmpc#1.0.1#1/lib:sdk/libmpfr#3.1.1#1/lib sdk/gcc#4.8#2/bin/gcc-4.8 -DIDE=CppDroid -fPIE -pie -Isdk/libstdc++-compact-dev#4.8#1/arm-linux-androideabi/include/c++/4.8 -Isdk/libstdc++compact-dev#4.8#1/arm-linux-androideabi/include/c++/4.8/arm-linux-androideabi -Isdk/ndk-sysroot-16#r9c#1/arm-linux-androideabi/include -Isdk/gcc#4.8#2/lib/gcc/arm-linux-androideabi/4.8/include --sysroot=sdk/ndk-sysroot-16#r9c#1/arm-linux-androideabi```

# Credits

Thanks to cppdroid team
http://www.cppdroid.info
