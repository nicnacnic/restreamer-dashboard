![](https://github.com/nicnacnic/restreamer-dashboard/blob/main/images/cover.png)

# Restreamer-Dashboard
A visual dashboard to control OBS from another location.

[![Release](https://img.shields.io/github/v/release/nicnacnic/restreamer-dashboard?label=Release)](https://github.com/nicnacnic/restreamer-dashboard/releases)
![Downloads](https://img.shields.io/github/downloads/nicnacnic/restreamer-dashboard/total?label=Downloads)
![License](https://img.shields.io/github/license/nicnacnic/restreamer-dashboard?label=License)
![Twitter](https://img.shields.io/twitter/follow/nicnacnic11?style=social)
[![Discord](https://img.shields.io/badge/-Join%20the%20Discord!-brightgreen?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/A34Qpfe)

## About
restreamer-dashboard is a custom UI built on Node-Red to control many functions of OBS, without actually connecting to the host's computer. This is aimed at speedrunning marathons, therefore most of the functions one might use are included, such as scene-switching, audio management and more. Unlike Teamviewer, the restreamer never has direct access to the host's computer, and this can even be ran off a webserver!

### Features
- 16 pre-built scenes, with an additional 5 customizable ones
- 6 pre-built audio sources, with an additional 3 customizable ones
- Full audio management, including individual volume sliders and mute controls
- Fully functional preview and program, powered by [OBS.Ninja](https://obs.ninja/)
- Auto Record: Record whenever you're not in an intermission
- Full monitoring tab with all OBS stats and Twitch feed
- Password-protected controls including start/stop streaming and recording
- NodeCG integration including timer and run control
- Support for both Twitch and RTMP streams
- Support for HTTPS and password authentication

A detailed explanation of the features can be found on the [wiki](https://github.com/nicnacnic/restreamer-dashboard/wiki/Using-The-Dashboard).

## Requirements
Administrator privileges will be needed to install. Some of these programs use the command line, you should be comfortable using Command Prompt or similar.
- [Git For Windows](https://git-scm.com/downloads)
- [Node.JS](https://nodejs.org/en/)
- [Node-Red](https://nodered.org/docs/getting-started/local)
- [OBS-Websocket](https://github.com/Palakis/obs-websocket)

Not required, but _highly_ recommended.
- [NodeCG](https://github.com/nodecg/nodecg)
- [NodeCG Speedcontrol](https://github.com/speedcontrol/nodecg-speedcontrol)

## Using The Dashboard
The UI makes the dashboard super simple to use! All functions are neatly sorted into different pages, accessible by using the menu on the top-left.
To switch a scene, it's as simple as selecting the layout, entering the runner's Twitch name or stream key, and pressing the transition button. With NodeCG integration, controlling the timer and run information is a breeze. 

There are 16 pre-built layouts available, plus 5 customizable buttons in the scene panel for those unusual game layouts. Same goes for audio, with 6 pre-built audio controls, plus 3 additional customizable audio controls if you ever need to add an audio source.

It also comes with two OBS scene collections that you can use, one for Twitch and one for RTMP, but you are welcome to make your own!

If you end up using restreamer-dashboard during your marathon/event, it would be greatly appreciated if you included the repository name and author in your end credits. Thank you!

For a full installation and user guide, please visit the [wiki](https://github.com/nicnacnic/Restreamer-Dashboard/wiki).

## Marathon Layouts
If you need a pack of marathon layouts to customize, check out my NodeCG bundle! [nicnacnic/speedcontrol-layouts](https://github.com/nicnacnic/speedcontrol-layouts)

## Suggestions And Support
The dashboard is still being developed, so if you come across any bugs or have any suggestions, please let me know by checking the list of [known bugs](https://github.com/nicnacnic/Restreamer-Dashboard/wiki), and creating an issue in the [issue tracker](https://github.com/nicnacnic/Restreamer-Dashboard/issues) if it isn't listed.

If you're having issues installing or using the dashboard, I can be reached through my [Discord](https://discord.gg/A34Qpfe) server. Be aware that I'm usually busy with multiple marathons and other projects so I might not be able to help you right away.

## Special Thanks
TokkoTomcat and Disdonn, for original testing and bug-finding.

UWS-CIA, for lending me his time and helping me fix issues with obs-websocket authentication.

Kuno Demetries, for letting me test this dashboard on his marathon, and putting up with the many tech issues I'm probably going to cause.

The Midwest Speedfest crew, for helping out with my NodeCG issues and for overall being such cool people :D

## License
MIT License

Copyright (c) 2021 nicnacnic

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
