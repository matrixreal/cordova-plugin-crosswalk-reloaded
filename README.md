This is a reloaded version of Crosswalk, with a modified .aar file in order to build a final .aab file that contains ALL architectures. Do not try to upload the APK file, as it will be rejected.

Please, build normally (the apk) and then go to the platforms>android folder and execute:

```
gradlew.bat bundle
```

I will document the whole process and the things I modified in next releases but this is a viable alternative to still use crosswalk in 2019 in android and be able to have the .aab accepted in Google Play Store.