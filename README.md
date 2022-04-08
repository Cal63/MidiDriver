# MidiDriver
MIDI synthesizer for android (soundfont2 is supported)

ⓘ This is a fork of [KyoSherlock/MidiDriver](https://github.com/KyoSherlock/MidiDriver) with the following changes:

- Gradle and dependencies have been updated
- [`javax.sound.midi`](https://github.com/kshoji/javax.sound.midi-for-Android) is no longer directly copied into this project but is instead added as a dependency
- Migrated from `android.support` to `androidx`
- This library has been published to this Git repository; to use it:

  1. In `build.gradle` in your Android project, add this to the `repositories` section, e.g.

     ```
     allprojects {
         repositories {
             ...
             maven { url 'https://github.com/bmaupin/MidiDriver/raw/master/repo' }
         }
     }
     ```

  1. In `app/build.gradle` in your Android project, add this library as a dependency, e.g.

     ```
     dependencies {
       ...
       implementation 'cn.sherlock:sherlockmidi:1.0'
     ```

  1. Use this library in your project; see the `sample` directory for an example

# About MidiDriver
  1) Just a synthesizer for playing MIDI note on Android. You can use it with USB/Bluetooth-MIDI library together to create your MIDI application.

  2) soundfont2 file is supported.
  
# Thanks
  javax.sound.midi

  https://github.com/kshoji/javax.sound.midi-for-Android

  https://github.com/kshoji

# Changelog

### Version: 1.0

  * Initial Build

# License

    Copyright 2015, KyoSherlock
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
       http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
