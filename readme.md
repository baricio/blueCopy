# blue copy

> example bluetooth ionic

# config environment 

npm install -g cordova ionic

### error linux permission on install (optional)

sudo chown -R username /usr/lib/node_modules

## Install Android SDK

[Download Android Studio](https://developer.android.com/studio/index.html)

[Steps to config Android Studio](https://developer.android.com/studio/install.html)

[Update and install the lasted stable sdk](https://developer.android.com/studio/intro/update.html)

## Create environment Variables

access `nano ~/.bashrc`

add variables

```
export ANDROID_HOME=$HOME/Android/Sdk
export PATH="${PATH}:${ANDROID_HOME}tools/:${ANDROID_HOME}platform-tools/"
```

## excute to android with hot-reload

```
ionic cordova run android -lc
```

### Error You have not accepted the license agreements of the following SDK components

execute command

```
$ANDROID_HOME/tools/bin/sdkmanager --licenses
```
Acept all licenses