# ✒ [libwinmedia](https://github.com/harmonoid/libwinmedia) is sequel to this project.
#### It provides network playback, better format support, control & features.
<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
#### An audio playback library for Flutter Desktop.

Feel free to open issue anytime.


## Installing

Mention in your pubspec.yaml:

```yaml
dependencies:
  ...
  flutter_audio_desktop:
    git:
      url: https://github.com/fermat28/flutter_audio_desktop_fermat.git
      ref: master
```

## Using

```dart
// Create new instance.
var audioPlayer = new AudioPlayer(id: 0)
..stream.listen(
  (Audio audio) {
    // Listen to playback events.
  },
);
// Load audio source
audioPlayer.load(
  new AudioSource.fromFile(
    new File('/home/fermat/music.mp3'),
  ),
);


See [this](https://github.com/fermat28/flutter_audio_desktop/example/lib/main.dart) example for a better overview.

#### Windows

<img src="https://github.com/fermat28/flutter_audio_desktop/blob/assets/windows.png?raw=true" width="500"></img>

#### Linux

<img src="https://github.com/fermat28/flutter_audio_desktop/blob/assets/linux.png?raw=true" width="500"></img>

## Support

Thankyou!


## Progress

|Platform            |Status                                                    |
|--------------------|----------------------------------------------------------|
|Linux               |Working                                                   |
|Microsoft Windows   |Working                                                   |
|MacOS               |[Learn More](https://www.youtube.com/watch?v=dQw4w9WgXcQ) |


## License

I don't want to put any restrictions on how you distribute your Flutter Desktop apps, so this library comes under very permissive software, MIT license.

Since, other libraries like [libvlcpp](https://github.com/videolan/libvlcpp) or [libvlc](https://www.videolan.org/vlc/libvlc.html) come under GPL & LGPL licenses respectively, so there will be many restrictions if I plan to use them.

Thus, this project uses [miniaudio](https://github.com/mackron/miniaudio) and [miniaudio_engine](https://github.com/mackron/miniaudio) from [David Reid](https://github.com/mackron) under MIT license.


## Acknowledgments

- [David Reid](https://github.com/mackron) for his amazing single header libraries [miniaudio](https://github.com/mackron/miniaudio) and [miniaudio_engine](https://github.com/mackron/miniaudio).
- Thanks to [MichealReed](https://github.com/MichealReed) for his support to the project.
