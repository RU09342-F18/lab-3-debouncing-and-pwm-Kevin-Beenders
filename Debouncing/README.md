# Software Debouncing

In this lab, software debouncing is implemented in an attempt to rectify the problem of mechanical switches triggering multpile rising edges withing microseconds if the inital button press. In the case of the button for the G2553, it was observed that it could bounce and cause four rising edges within 500 microseconds of the initial press. This means that only the first rising edge will be seen as a signal and the others will be ignored, as the state will not be able to change within that amount of time the bouncing occurs in.
