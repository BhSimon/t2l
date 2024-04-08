# Tach2Locked
The Shut The Fan Up (STFU) board converts a fan’s tachometer signal to a ‘locked rotor’ signal. The locked rotor signal is typically an active-low signal which is triggered when the fan is rotating. If the signal on this line is pulled high, it indicates that the fan is not running. Typical consumer fans such as Noctua’s use a tachometer which pulses to indicate the speed of the fan. This board converts that signal to the active-low locked rotor signal.

The DIP switches on the Plus model control the max speed of the fan, in the same way as Noctua’s Low Noise Adapter (LNA). There are four settings:

<img src="https://github.com/BhSimon/t2l/assets/7036461/f8fdfabb-38df-4c7e-a513-b46d52522d90" width="200">
