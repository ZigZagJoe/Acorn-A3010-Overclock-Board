# Acorn A3010 Overclock board for early ARM250 machines

Intended for the early machines without an oscillator socket, this enables switching between three speeds: 
Original (clock output is Hi-Z), oscillator on this add in board, or an off-board oscillator such as the 72mhz on the motherboard.

A buffer is used to allow the switch to be located remotely regardless of wire length, and also to minimize loading on the logicboard oscillator (if used). The switch connector is intended for an ON-OFF-ON (or ON-ON-ON) switch.

position 1 (ON) is Hi-Z output (pins 1-2 connected)
position 2 (OFF) or switch disconnected will use onboard oscillator
position 3 (ON) is off-board oscillator (pins 2-3 connected)

The included bracket design clips onto the ventillation slots on the bottom of the case. Unfortunately, it was designed for a specific switch out of my junk box: switch body 16mm L x 7mm W x 7.5mm H, actuator 3mm L x 2.4mm W x 4.2mm H

This is licensed under a
Creative Commons Attribution-NonCommercial 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <https://creativecommons.org/licenses/by-nc/4.0/>.