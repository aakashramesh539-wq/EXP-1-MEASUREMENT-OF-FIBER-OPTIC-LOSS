# EXP-1-MEASUREMENT-OF-FIBER-OPTIC-LOSS

# AIM
To measure propagation loss & bending losses for two different wavelengths in plastic fiber provided with the kit.
# EQUIPMENTS REQUIRED
- Link-B Kit with power supply.
- Patch chords.
- 20MHz Dual Channel Oscilloscope.
- 1 MHz Function Generator.
- 1 Meter Fiber Cable.
# PROGRAM
  ```
# Measurement of Fiber Optic Loss

import math

L1 = 1
L2 = 3

V1 = 1.8
V2 = 1.5

loss = 20 * math.log10(V1 / V2) / (L2 - L1)

print("Fiber Optic Loss =", round(loss, 2), "dB/m")

# Bending Loss
input_voltage = 2.0
output_voltage = 0.9

bending_loss = 20 * math.log10(input_voltage / output_voltage)

print("Bending Loss =", round(bending_loss, 2), "dB")
```
# TABULATION
<img width="1153" height="1536" alt="image" src="https://github.com/user-attachments/assets/d6499087-c521-4359-97b3-e72896684505" />

# RESULT
Thus, the propagation loss and bending loss of the optical fibre were studied successfully.
