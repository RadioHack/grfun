A Simple FFT Display

Like the title says, this is just about the simplest GnuRadio program there is. It takes samples from an osmocom source and passes them through a throttle to an FFT display.

Tip: If your computer is slow, or has poor floating point performance (such as the Intel Atom), keep the throttle low. Otherwise, experiment with raising the throttle to the full sample rate.

Tested on:

* RTLSDR (FC0013)
* HackRF Jawbreaker
