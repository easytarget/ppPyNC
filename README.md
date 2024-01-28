# ppPyNC
PiPico Python Numeric Controller

* Step 1 : Reference hardware
* Step 2 : Code

###

Plan:
* Micropython based controller software for a RP2040 based controller.
* Use PIO for movement
* Use both cores; planner on a seperate core? IF POSSIBLE!
* GRBL compatibility for Gcode
* FluidNC compatibility for settings and init/config.
  * Use a similar 'init file' setup.. etc.
  * GRBL `$` command compatibility for setting
* No Wifi / Web interface for now.. No SD card support.
  * Lets start with a pretty 'dumb' controller that needs to be driven by LaserWeb etc directly via USB

