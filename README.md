# Restreamer-Dashboard
A visual dashboard to control OBS from another location.

## About
Restreamer-Dashboard is a custom UI built on Node-Red to control many fuctions of OBS, without actually connecting to the host's computer. This is aimed at speedrunning marathons, therefore most of the functions one might use are included, such as scene-switching, audio managment and more. Unlike Teamviewer, the restreamer never has access to the host's computer, and this can even be ran off a webserver!

### Features
- 25 pre-built scenes, with an additional 5 customizable ones
- 6 pre-built audio sources, with an additional 3 customizable ones
- Full audio managment, including individial volume sliders and mute controls
- Fully functional preview and program, powered by [OBS.Ninja](https://obs.ninja/)
- Full monitoring tab with all OBS stats and Twitch feed
- Password-protected controls including start/stop streaming and recording
- Support for HTTPS and password authentication
- Full documentation availible on the [wiki](https://github.com/nicnacnic/Restreamer-Dashboard/wiki)

## Requirements
Administrator privileges will be needed to install. Some of these programs use the command line, you should be confortable using Command Prompt or similar.
- [Git For Windows](https://git-scm.com/downloads)
- [Node.JS](https://nodejs.org/en/)
- [Node-Red](https://nodered.org/docs/getting-started/local)
- [OBS-Websocket](https://github.com/Palakis/obs-websocket)

Not required, but _highly_ recommended.
- [NodeCG](https://github.com/nodecg/nodecg)
- [NodeCG Speedcontrol](https://github.com/speedcontrol/nodecg-speedcontrol)
