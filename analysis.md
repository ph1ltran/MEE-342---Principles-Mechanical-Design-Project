# Calculations, spreadsheets, scripts, or summaries of FEA/motion analyses.

## Static Stress and Factor of Safety

The critical part evaluated from the static stress and factor of safety analysis is the holder. Using basic mechanics of materials and assuming that the part does not experience any torsional loads, the combined stress in the long part of the holder was calculated to be about 8 psi       and the combined stress around the edge of the hole was calculated to be about 2.85 psi, which agrees with the solution obtained from ANSYS (see FEA figures for comparison). The max combined stress in the holder, however, is expected to occur in the location where the cross section       of the part is reduced due to the hole’s presence. This value was calculated to be about 1000 psi, which does not agree with the solution from ANSYS which lists the max stress as just 16.911 psi in this area. But since ANSYS’ result is located at a sharp corner, it is concluded that     this value is actually a stress singularity, so the true max combined stress is expected to be around 1000 psi in the holder. Lastly, with structural steel as the selected material, the factor of safety was calculated to be FS = 36250/1000 = 36.25.

![Statics Image 1](https://github.com/user-attachments/assets/2db4e79e-fd5b-45b9-9e4d-32726ef0037d)
![Statics Image 2](https://github.com/user-attachments/assets/9799b4f6-2c38-4511-a83b-7ab8bd5c31a7)

## Finite Element Analysis (FEA)

