# STM32 Projects

Embedded systems portfolio — firmware and hardware design projects built on the STM32F446RETx (STM32CubeIDE), developed as part of an internship-focused learning roadmap.

---

## Projects

### 🔧 DC Motor Speed Control
**Path:** `DC_MotorSpeed_Control_Project/`

Closed-loop DC motor speed control using PWM and encoder feedback.

- **MCU:** STM32F446RETx
- **Control:** PI controller (proportional-integral) regulating motor RPM against a setpoint
- **Feedback:** Pulse counting via encoder input, RPM computed from pulse timing
- **Peripherals used:** Timer (PWM output), Timer (encoder/pulse capture), ADC, USART2 (debug/monitoring)
- **Key variables:** `measured_rpm`, `setpoint_rpm`, `Kp`, `Ki`, `integral`, `error`

### PCB Design — Motor Driver Board
**Path:** `pcb/`

Custom-designed PCB for the motor driver circuit, built in KiCad and fabrication-ready.

- Schematic and PCB layout (`.kicad_sch`, `.kicad_pcb`)
- Full Gerber export set (copper, mask, paste, silkscreen, edge cuts — both layers)
- 3D rendered board preview included

---

## Tools Used

- STM32CubeIDE
- KiCad (schematic capture + PCB layout)
- GitHub Desktop for version control

## Status

Actively developed as part of an ongoing embedded systems learning roadmap targeting an embedded internship .

---

## Author

Virendra Kumar — EEE student, M.B.M. Jodhpur
