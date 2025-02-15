# Analog CMOS Amplifier Circuit 🎛️⚡

This project showcases the design and analysis of an **Analog CMOS Amplifier**, developed as part of the **EE140** course at **UC Berkeley**. The amplifier is optimized for **high gain, wide bandwidth, and low power consumption**, making it ideal for precision analog signal processing.

## Features
- 📈 **High Gain**: Voltage gain **> 2000 V/V**
- ⚡ **Wide Bandwidth**: Unity-gain frequency **> 400 MHz**
- 🔋 **Low Power Consumption**: ~1.9 mW with a 1.2V supply
- ⏱ **Fast Settling Time**: < 4.9 ns for a 5 pF load
- 🔍 **High CMRR & PSRR**: >124 dB and 74 dB respectively

## Design Overview
- **Two-Stage CMOS Amplifier**: Differential input + Common-source output stage
- **Self-Biased Cascode Configuration**: Enhances output resistance and gain
- **Minimal Passive Components**: Uses only two resistors (7 kΩ, 228 Ω)

## How It Works
1. **Differential Pair Input**: Provides initial voltage amplification.
2. **Gain Stage Enhancement**: Improves overall voltage gain.
3. **Output Buffer**: Ensures stable signal delivery to the load.
4. **Frequency Compensation**: Optimizes stability for high-speed applications.

## Documentation
For a detailed explanation, simulations, and results, check the full report:

📄 [Project EE140 Report](https://github.com/Dao1213/Analog-CMOS-Amplifier-Circuit/blob/main/Project%20EE140%20report-Dao.pdf)

