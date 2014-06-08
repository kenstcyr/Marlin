Marlin
======

This fork of the Marlin firmware starts with Rich Cattell's version with auto-calibration
and expands on the functionality.

The following changes were made:
  - Added G31.  This will perform an automatic tilt adjustment on the bed by probing near
    near the X, Y, and Z towers and adjusting the soft endstops accordingly.