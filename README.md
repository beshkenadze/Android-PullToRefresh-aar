Hockey Android SDK AAR library
========================

Hockey Android SDK library built with gradle in aar format for usage with android gradle build system. 

How to use
=======================
Before you can get aar you should checkout [Android-PullToRefresh](https://github.com/chrisbanes/Android-PullToRefresh) submodule. Overall build process including build is straightforward:
```bash
  $ git submodule update --init
  ...
  $ ./gradlew build
  ...
```

When build is finished aar file will be located in `build/libs`.

Maven artifact in local repo
======================

```bash
  $ ./gradlew build uploadArchives
```
