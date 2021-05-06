# OMNIBUS-CNC-Controller (WORK IN PROGRESS)
CNC Control Project (GRBL and ESTLCAM based). Please dont' sell the boards published here without my consent.

## OMNIBUS ESTLCAM Controller</br>
<img src="https://raw.githubusercontent.com/skaman82/OMNIBUS-CNC-Controller/main/Images/OMNIBUS%20EstlCam%20board%20v3_t.png"/></br>
• 8 inputs for sensors and buttons (IN6 is usable if you remoove the LED "L" from the Nano)</br>
• All inputs are isolated with optocouplers</br>
• Inputs 1-3 have selectable voltage (5/12v) so you can connect inductive proximity sensors directly</br>
• VFD outputs (Spindle ON/OFF and RPM control)</br>
• 5V PWM output</br>
• 3 Outputs for relays - the outputs have selectable voltage (5/12v) - OUT3 is automatically enabled on spindle ON</br>
• Feed/Speed override connectors (JST XH 3P)</br>
• Header for bluetooth serial module (HC-05)</br>
• Screw-Terminals for easy connection</br>
• Connector for the DRV-Shield</br>
</br>
## OMNIBUS GRBL 1.1 Controller - also ESTLCAM compatible</br>
<img src="https://raw.githubusercontent.com/skaman82/OMNIBUS-CNC-Controller/main/Images/OMNIBUS%20GRBL%20board%20v2_t.png"/></br>
• Limit-Inputs XYZ have selectable voltage (5/12v) so you can connect inductive proximity sensors directly</br>
• ABORT/HOLD/RESUME/PROBE inputs</br>
• All inputs are isolated with optocouplers</br>
• VFD outputs (Spindle ON/OFF and RPM control)</br>
• 5V PWM Output</br>
• 2 Outputs for relay (SPINDLE_RELAIS / COOLANT) - the outputs have selectable voltage (5/12v) - SPINDLE RELAY is automatically enabled on spindle ON</br>
• Header for bluetooth serial module (HC-05)</br>
• Header for offline controller</br>
• Screw-Terminals for easy connection</br>
• Connector for the DRV-Shield</br>

NOTE: To use the "SPINDLE RELAY" and "VFD RUN" Outputs, please uncomment "define USE_SPINDLE_DIR_AS_ENABLE_PIN" in the GRBL config.h file.
</br>
## OMNIBUS DRV SHIELD (mounts on top the controll PCB with spacers)</br>
<img src="https://raw.githubusercontent.com/skaman82/OMNIBUS-CNC-Controller/main/Images/OMNIBUS%20Stepper%20board%20v2_t.png"/></br>
• Up to 10A current support (2oz copper PCB required)</br>
• 3-Axis stepper driver support (DRV8825/S109/TMC2100) with stepping config jumpers</br>
• Header for laser module (3p)</br>
• Laser module safety switch - PWM controlled</br>
• Header for an extra 12V 2A BEC to power a laser module (20w max)</br>
• 12V fan header</br>
• 12V Power supply for the OMNIBUS controller (so you don't need an extra 12v PSU for the controll board)</br>
• Screw-Terminals for easy connection</br>

NOTE: If powerting the OMNIBUS Controller with the DRV Shield, use a heatsink on the 12V LDO and provide good airflow - the LDO is getting hot and will
shut down if thermal protection kicks in.
