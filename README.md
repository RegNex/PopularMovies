# PopularMovies App
<img align="center" src="https://github.com/RegNex/PopularMovies/blob/master/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png"/>
PopularMovies App is an application that displays movies using themoviedb.org api. This is udacity Android developer nanodegree popularMovies stage 1

## Screenshots
<img align="left" src="https://github.com/RegNex/PopularMovies/blob/master/ScreenShots/1.png" width="200" height="400"/>
<img src="https://github.com/RegNex/PopularMovies/blob/master/ScreenShots/2.png" width="200" height="400"/>

## Getting Started

To clone this project,

open your terminal or cmd

```
cd folder/to/clone-into/
```

```
git clone https://github.com/RegNex/PopularMovies.git
```

Then 
locate the project on your system and open with android studio

add your api key from themoviedb.org to ```gradle.properties```
```
API_KEY="YOUR_API_KEY_HERE"
```
Then Open the application app:build.gradle and within the defaultConfig add a reference to your API_KEY
```
   defaultConfig {
        applicationId "co.etornam.popularmovies"
        minSdkVersion 19
        targetSdkVersion 27
        versionCode 1
        versionName "1.0"
        testInstrumentationRunner "androidx.test.runner.AndroidJUnitRunner"

        // Please ensure you have a valid API KEY for themoviedb.org to use this app
        // A valid key will need to be entered
        buildConfigField("String", "API_KEY", API_KEY)
    }
```    

## Prerequisites

What things you need to install the software and how to install them

```
* Android Studio
* Java JDK 8+
* Android SDK
```


## How to contribute
Contributing to PopularMovies App is pretty straight forward! Fork the project, clone your fork and start coding!


## Features:

- sort movies
- view movie detail
- UI optimized for phone and tablet

## Download APK
You can find the apk of this project in

```
PopularMovies\app\release\app-release.apk
```

## To set up an emulator
* Select Run > Run 'app'
* Click 'Create New Emulator'
* Select the device you would like to emulate (Recommended: pixel xl2)
* Select the API level you would like to run - click 'Download' if not available (Recommended: Marshmallow - ABI: x86)
* Select configuration settings for emulator
* Click 'Finish' and allow Emulator to run

## To Run on an Android OS Device
* Connect the device to the computer through its USB port
* Make sure USB debugging is enabled (this may pop up in a window when you connect the device or it may need to be checked in the phone's settings)
* Select Run > Run 'app'
* Select the device (If it does not show, USB debugging is probably not enabled)
* Click 'OK'

## Built With

* [Android Studio](https://developer.android.com/studio/install) - How to install Android Studio
* [The Movie Db](https://www.themoviedb.org/) - Getting started with The Movie DB


## Author

* **Sunu Bright Etornam** 


## License

Copywrite 2018 Sunu Bright Etornam

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
