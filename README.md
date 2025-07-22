# FIR Low-Pass Filter Design using Kaiser Window Method

## Authors

- **Rodrigo Freitas Sá Barretto** — Computer Engineering Student  

- **Miguel Feliciano Mota Alves** — Computer Engineering Student  

## Project Description

This project implements a **linear-phase FIR low-pass filter** using the **Kaiser window method**. The filter is designed to meet specific frequency and attenuation specifications and is analyzed under both **infinite and finite precision** conditions. The filter is also implemented in **direct** and **cascade** forms, and frequency transformations are explored for further analysis.

---

## Design Specifications

- **Cutoff frequency**: ω<sub>c</sub> = π/2 (corresponding to -6 dB point)
- **Minimum stopband attenuation**: ≥ 50 dB
- **Transition width**: Δω < 0.1π
- **Window method**: Kaiser window

---

## Implementation Steps

1. **Design FIR filter** using the Kaiser window method based on the specifications.
2. **Implement** the filter in:
   - Direct form
   - Cascade form (e.g., pairwise second-order sections)
3. **Represent coefficients** using:
   - Floating-point (full precision)
   - Reduced decimal precision (gradually decreasing number of digits after the decimal point)
4. **Plot**:
   - Magnitude response in dB
   - Phase response
   - Comparison between infinite and finite precision effects

<!-- --- -->

<!-- ## Frequency Transformations

For the **direct form**, the filter is redesigned using the following **Z-domain transformations**:
1. **Z⁻¹ → −Z⁻¹**
2. **Z⁻¹ → Z⁻²**
3. **Z⁻¹ → −Z⁻²**

For each transformation, the **magnitude (in dB)** and **phase response** are plotted and analyzed.

---

## Outputs

- Frequency response plots (magnitude and phase)
- Sensitivity analysis with respect to **coefficient quantization**
- Transformed versions of the original filter -->

