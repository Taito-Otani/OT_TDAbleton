# OT_TDAbleton
The Simplest way to Ableton Live parameter to Touch Designer via OSC.
Offcial TDAbleton sample is a little complex. This sample is easy to use for me.


## USAGA
1. clone or zip your local

2. open ableton live project
3. set M4L/OT_TDAudioSender on your audio track on ableton live.
4. set M4L/OT_TDMIDISender on your midi track on ableton live.

![setting of ableton live](https://github.com/Taito-Otani/OT_TDAbleton/blob/main/img/img1.png "setting of ableton live")


5. open touch designer project
6. make operator OSCIN chop
7. set host and port(default: host 127.0.0.1, port 19951)

![setting of ableton live](https://github.com/Taito-Otani/OT_TDAbleton/blob/main/img/img2.png "setting of ableton live")

#### message list
/attack 0 - 1
/peak 0.0 - 1.0
/note 0 -  88
