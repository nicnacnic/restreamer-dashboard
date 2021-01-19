# Restreamer-Dashboard
A visual dashboard to control OBS from another location.

## About
restreamer-dashboard is a custom UI built on Node-Red to control many functions of OBS, without actually connecting to the host's computer. This is aimed at speedrunning marathons, therefore most of the functions one might use are included, such as scene-switching, audio management and more. Unlike Teamviewer, the never has access to the host's computer, and this can even be ran off a webserver!

### Features
- 25 pre-built scenes, with an additional 5 customizable ones
- 6 pre-built audio sources, with an additional 3 customizable ones
- Full audio management, including individual volume sliders and mute controls
- Fully functional preview and program, powered by [OBS.Ninja](https://obs.ninja/)
- Auto Record: Record whenever you're not in an intermission
- Full monitoring tab with all OBS stats and Twitch feed
- Password-protected controls including start/stop streaming and recording
- NodeCG integration including timer and run control
- Support for HTTPS and password authentication

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
To switch a scene, it's as simple as selecting the layout, entering the runner's Twitch name, and pressing the transition button. With NodeCG integration, controlling the timer and run information is a breeze. 

There are 25 pre-built layouts available, plus 5 customizable buttons in the scene panel for those unusual game layouts. Same goes for audio, with 6 pre-built audio controls, plus 3 additional customizable audio controls if you ever need to add an audio source.

For a full installation and user guide, please visit the [wiki](https://github.com/nicnacnic/Restreamer-Dashboard/wiki).

## Suggestions And Support
The dashboard is still being developed, so if you come across any bugs or have any suggestions, please let me know by checking the list of [known bugs](https://github.com/nicnacnic/Restreamer-Dashboard/wiki), and creating an issue in the [issue tracker](https://github.com/nicnacnic/Restreamer-Dashboard/issues) if it isn't listed.

If you're having issues installing or using the dashboard, I can be reached through my Discord server. Be aware that I'm usually busy with multiple marathons and other projects so I might not be able to help you right away.

## Special Thanks
TokkoTomcat and Disdonn, for original testing and bug-finding.

UWS-CIA, for lending me his time and helping me fix issues with obs-websocket authentication.

Kuno Demetries, for letting me test this dashboard on his marathon, and putting up with the many tech issues I'm probably going to cause.

The Midwest Speedfest crew, for helping out with my NodeCG issues and for overall being such cool people :D
