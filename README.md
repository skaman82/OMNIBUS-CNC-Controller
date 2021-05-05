# OMNIBUS-CNC-Controller (WORK IN PROGRESS)
CNC Control Project (GRBL ans ESTLCAM based)

##OMNIBUS ESTLCAM Controller
• 8 Inputs for Sensors and Buttons (IN6 is usable if you remoove the LED from the Nano)
• All inputs are isolated with optocouplers
• Inputs 1-3 have selectable voltage (5/12v) so you can connect inductive proximity sensors directly
• VFD outputs (Spindle ON/OFF and RPM control)
• 5V PWM Output
• 3 Outputs for Relais - the outputs have selectable voltage (5/12v) - OUT3 is automatically enabled on spindle ON
• Feed/Speed override connectors (JST XH 3P)
• Header for Bluetooth serial module (HC-05)
• Screw-Terminals for easy connection
• Connector for the DRV Shield

##OMNIBUS GRBL 1.1 Controller
• Limit-Inputs XYZ have selectable voltage (5/12v) so you can connect inductive proximity sensors directly
• ABORT/HOLD/RESUME/PROBE inputs
• All inputs are isolated with optocouplers
• VFD outputs (Spindle ON/OFF and RPM control)
• 5V PWM Output
• 2 Outputs for Relais (SPINDLE_RELAIS / COOLANT) - the outputs have selectable voltage (5/12v) - SPINDLE RELAIS is automatically enabled on spindle ON
• Header for Bluetooth serial module (HC-05)
• Header for offline controller
• Screw-Terminals for easy connection
• Connector for the DRV Shield

##OMNIBUS DRV SHIELD (mounts on top the controll PCB with spacers)
• Up to 10A current support (2oz copper PCB required)
• 3-Axis stepper driver support (DRV8825/S109/TMC2100) with stepping config jumpers
• Header for laser module (3p)
• Laser module safety switch - PWM controlled
• Header for an extra 12V 2A BEC to power a laser module (20w max)
• 12V fan header
• 12V Power supply for the OMNIBUS Controller (so you don't need an extra 12v PSU for the controll board)
• Screw-Terminals for easy connection
