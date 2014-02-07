motion-audio-session
====================


This is an example app to reproduce the error: 

2014-02-06 21:20:21.484 motion-audio-session[10401:303] app_delegate.rb:18:in `buildWindow': uninitialized constant AppDelegate::AVAudioSession (NameError)

https://github.com/ivanacostarubio/motion-audio-session/blob/master/app/app_delegate.rb#L18

AVFoundation is on the Rakefile.
