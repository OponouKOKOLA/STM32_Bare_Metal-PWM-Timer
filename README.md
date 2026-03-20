# STM32 Bare-Metal PWM — Breathing LED

Effet respiration LED via Timer2 PWM sur STM32L152RE
sans couche HAL — configuration directe des registres.

## 🛠️ Matériel
- STM32 Nucleo-L152RE (ARM Cortex-M3)
- LED intégrée PA5 (LD2)
- LED Cablée sur D13

## ⚙️ Configuration Timer
- PSC = 1999 → 1 tick = 1ms
- ARR = 999  → période = 1s
- CCR1 = 0→999 → duty cycle variable

## 🔧 Concepts
- Timer2 Canal 1 — AF1
- PWM Mode 1 via CCMR1
- Effet respiration dans while(1)

  # ## 🎥 Démonstration — Effet Respiration LED

[  https://s2.ezgif.com/tmp/ezgif-296131b0e1acbe3b.gif]



## 📬 Contact
- manuelkokola@gmail.com
- LinkedIn : linkedin.com/in/oponou-emmanuel-kokola-44054b292
