# Tach-2-Lock
The *Lock de Tach* board converts a fan’s tachometer signal to a ‘locked rotor’ signal. The locked rotor signal is typically an active-low signal which is triggered when the fan is rotating. If the signal on this line is not 0V, it indicates that the fan is not running. Typical consumer fans such as Noctua’s use a tachometer signal, which pulses to indicate the speed of the fan. This board converts that signal to the active-low locked rotor signal.

## STFU model: DIP switch settings
The DIP switches on the STFU (Shut The Fan Up) model control the max speed of the fan, which has the same effect as the Low Noise Adapter (LNA) and Ultra Low Noise Adapter (ULNA) cables. There are four settings:

### Max fan speed
<img src="https://github.com/BhSimon/t2l/assets/7036461/d9693deb-debc-414a-9e6a-ad9bd1a0a299" width="200">

**Caution!** You *must* be very careful when using settings lower than 100%. You will reduce the cooling capabilities of the switch and this could result in overheating and permanent damage. If you have a PoE switch, but you do not have any PoE devices, then it may be possible to reduce the fan speed safely, but it is not guaranteed.
