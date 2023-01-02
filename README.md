# sms-wrapped

### Requirements

**Requirements:**
* `node 18.12.1`
* `npm 9.2.0`

**Requirements needed for deploying to Android:**
* `Android Studio`
* `Android build tools 30.0.3`
* `Gradle 7.6`
* `Java SDK 11`

The steps to get Android function can be difficult and confusing. A detailed guide can be found [here](https://cordova.apache.org/docs/en/11.x/guide/platforms/android/). After everything is installed, these are the required environment variables:
```
# these are my installation files, might not be the same on your system
ANDROID_SDK_ROOT = C:\Users\{user}\AppData\Local\Android\Sdk
JAVA_HOME = C:\Program Files\Java\jdk-11.0.17

PATH = 
  C:\Program Files\Gradle\gradle-7.6\bin
  C:\Users\{user}\AppData\Local\Android\Sdk
  C:\Users\{user}\AppData\Local\Android\Sdk\emulator
  C:\Users\{user}\AppData\Local\Android\Sdk\platform-tools
  C:\Users\{user}\AppData\Local\Android\Sdk\build-tools
```

### Getting Started

```bash
npm i
```
