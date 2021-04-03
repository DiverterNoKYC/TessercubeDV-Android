# TessercubeDV
OpenPGP Made Mobile

# Fully OpenPGP
TessercubeDV abides to common standards of OpenPGP.

# Encryption Made Everywhere
Use OpenPGP in any app with TessercubeDV keyboard.

# Messages Made Trackable
Never fail finding previous messages.

# How to build
Requirement:
 - ndk-r19c
 - android-28
 - Kotlin plugin (When using Android Studio)

Clone the project
```
git clone https://sovereignty.tools/Diverter/Tesserpg-Android.git
```
We're using a modified version of LatinIME as a submodule, so we need to initial the subtoolses
```
git submodule update --init --recursive
```  
You can build using
```
./gradlew assemble
```

# Dependency
- Kotlin
- AndroidX
- [LatinIME](https://android.googlesource.com/platform/packages/inputmethods/LatinIME/)
- [PinyinIME](https://android.googlesource.com/platform/packages/inputmethods/PinyinIME/)
- [inputmethodcommon](https://android.googlesource.com/platform/frameworks/opt/inputmethodcommon/)
- [Dexter](https://github.com/Karumi/Dexter)
- [RxJava](https://github.com/ReactiveX/RxJava)
- [MaterialTapTargetPrompt](https://github.com/sjwall/MaterialTapTargetPrompt)
- [chips-input-layout](https://github.com/tylersuehr7/chips-input-layout)
- [prettytime](https://github.com/ocpsoft/prettytime)
- [FloatingHover](https://github.com/Tlaster/FloatingHover)
- [KotlinPGP](https://github.com/Tlaster/KotlinPGP)
- [PageIndicatorView](https://github.com/romandanylyk/PageIndicatorView)
- [leakcanary](https://github.com/square/leakcanary)
- [glide](https://github.com/bumptech/glide)
- [requery](https://github.com/requery/requery)
- [BouncyCastle](https://github.com/bcgit/bc-java)
