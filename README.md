# ELRS-8285-1280-PWM-ESC
A 2.4 GHz ELRS resceiver with 4 PWM outputs and a 1S, 5A ESC

- 2.4 GHz ExpressLRS receiver, ESP8285 based, with WiFi antenna
- 4 Servo PWM outputs
- on-board ESC
 - Up to 5.5 V input voltage (1S LiPo or HV-LiPo)
 - BLHeli_S I_H_40 (I didn't test if deadtime can be reduced - it probably can)
 - Handled 5 A for over a minute on the bench without damage: bench power supply set to 4.5 V, Mamba 1408 4000KV, HQProp DP 4x3x3. There was a cover over the ESC to reduce airflow from the prop.
- Voltage divider to measure battery voltage (not yet supported by ExpressLRS, 20211230)
- Testpads to flash ESC firmware through the EFM8's UART - can also be used with an external flight controller and serial passthrough to configure the ESC and re-flash it
- ExpressLRS can be flashed through the servo header

TBD: Link to RCGroups thread
