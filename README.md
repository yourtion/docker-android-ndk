# docker-android-ndk

[![android](http://dockeri.co/image/yourtion/ndk)](https://hub.docker.com/r/yourtion/ndk/)

Docker for android ndk project for GitLab-CI or others.

## Included

* Debian jessie
* Java 8
* Android SDK
* Android Support Libraries
* *Android NDK*

## Download

```shell
docker pull yourtion/ndk
```

## Usage

```shell
sudo docker run -t -i yourtion/ndk:latest /bin/shell
```

## Env

```shell
ENV SDK_HOME /usr/local
ENV ANDROID_HOME ${SDK_HOME}/android-sdk-linux
ENV ANDROID_SDK ${SDK_HOME}/android-sdk-linux
// NDK
ENV ANDROID_NDK_HOME ${SDK_HOME}/android-ndk-${ANDROID_NDK_VERSION}
```
