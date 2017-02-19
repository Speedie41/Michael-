Drc-sim-client uses the Beam interactive API to allow control of a Wii U using Beam controls.

With a working client and server run the client with a [Beam API](https://dev.beam.pro/tutorials/interactive.html) key.

See [[Arguments#beam-api]].

Beam App share code: `yea9b3jb` \(There is no documentation on Beam about this share code.\)

# Beam Setup

See [Beam dev](https://dev.beam.pro/tutorials/interactive.html) to get an API key.

Once the app is on Beam's lab, the control buttons can be created. The button IDs are hard-coded into the client. Having the wrong IDs will result in unexpected behavior.

The buttons and joystick should have all (2) the options enabled in the analysis section.

\#0 Touchpad

\#1-\#4 A,B,L,R

\#5 Screen (Not implemented but the IDs will be off by 1 if it's not added)

\#6-\#13 -,+,X,Y,UP,DOWN,LEFT,RIGHT

