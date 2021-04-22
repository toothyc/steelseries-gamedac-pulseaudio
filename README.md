# steelseries-gamedac-pulseaudio
Enable ChatMix and surround sound on the Steelseries Arctis Pro using PulseAudio profile files. Based off [the work by Witek094](https://github.com/Witek094/steelseries-arctis-pro-wireless-pulseaudio-profile)

## Installation on Fedora 34 with pipewire
Copy 91-pipewire-steelseries-gamedac.rules to /etc/udev/rules.d 

Copy steelseries-gamedac-usb-audio.conf to /usr/share/alsa-card-profile/mixer/profile-sets/

Copy Game-Output-Channel.conf, Chat-Output-Channel.conf to /usr/share/alsa-card-profile/mixer/paths/



**WARNING**: At the moment, you can't use the DAC's "Hi-Res" mode while these profiles are installed (this will be updated when I find a way). To restore original functionality, just delete the files you copied again and replug the DAC
