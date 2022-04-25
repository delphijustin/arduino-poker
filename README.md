# arduino-poker
Arduino TV Video Poker requires TVOut library. See https://www.arduino.cc/reference/en/libraries/tvout/ for more information.
For information on wiring the composite video to the arduino see tvout_pinout.png file.

Pinout
Lights
A1,A2,A3,A4,A5 Hold/Cancel Lights
13 Bet and cashout button light
A0 Draw and deal button light

Coin acceptor on pin 1

Buttons(all button are wired to ground since they are configured with INPUT_PULLUP Mode)
pin 8 bet one
pin 10 deal draw button
pin 11 bet max button
pin 12 cashout button
Pins 2-6 Hold/cancel buttons

It has five different video poker games
* Jacks or better
* aces and eights
* Joker poker
* double bonus poker
* double double bonus poker
