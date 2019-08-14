# simple_lcr_pattern-mode

This describes the use of lightcrafter in pattern mode with no further adjustments needed for many applications.

In pattern mode, Lcr does not apply image processing, therefore it displays grey values 0 to 255 with a linear increase (no gamma function, eliminating any need for linearisation).

**IMPORTANT**:
- Only works with *full-field stimuli*! (Image will get distorted without further adjustments)
- Only works for *greyscale* stimuli!

Use Lcr GUI to set it up for transforming the standard video stream through HDMI port into patterns with only few clicks.

1. set operating mode to *pattern sequence*
..go to the pattern sequence tab (blue rectangle)
2. set sequence settings to *video port*
3. set timings of pattern exposure and period to your frame duration (16667 µs for 60 Hz)
4. select *white* as pattern setting
5. set *bit depth* to 8 bit
6. select *G0 to G7*
7. click *add pattern to sequence*; the pattern will appear in the pattern sequence window
8. click *send*
![alt text][img1]
..in the pattern sequence start/stop/pause tab
9. click *validate sequence*
10. check that you get *green light* for sequence validated
11. click *play*
.. from now on your Lcr should run in pattern mode with no obvious change to the output.
![alt text][img2]

[img1]: ../lcr_settings_a.png "step 1"
[img2]: ../lcr_settings_b.png "step 2"
