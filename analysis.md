# Calculations, spreadsheets, scripts, or summaries of FEA/motion analyses.

## Static Stress and Factor of Safety

The critical part evaluated from the static stress and factor of safety analysis is the holder. Using basic mechanics of materials and assuming that the part does not experience any torsional loads, the combined stress in the long part of the holder was calculated to be about 8 psi       and the combined stress around the edge of the hole was calculated to be about 2.85 psi, which agrees with the solution obtained from ANSYS (see FEA figures for comparison). The max combined stress in the holder, however, is expected to occur in the location where the cross section       of the part is reduced due to the hole’s presence. This value was calculated to be about 1000 psi, which does not agree with the solution from ANSYS which lists the max stress as just 16.911 psi in this area. But since ANSYS’ result is located at a sharp corner, it is concluded that     this value is actually a stress singularity, so the true max combined stress is expected to be around 1000 psi in the holder. Lastly, with structural steel as the selected material, the factor of safety was calculated to be FS = 36250/1000 = 36.25.

![Statics Image 1](https://github.com/user-attachments/assets/2db4e79e-fd5b-45b9-9e4d-32726ef0037d)
![Statics Image 2](https://github.com/user-attachments/assets/9799b4f6-2c38-4511-a83b-7ab8bd5c31a7)

## Fatigue Assessment

By using the ‘fatigue tool’ in ANSYS for fully-reversed loading and analyzing the Goodman line under Mean Stress Theory, the mean stress of the adjustable stand was estimated to be (1 + (-1))/2) = 0 psi and the alternating stress was estimated to be |(1 - (-1))/2)| = 1 psi. 

![FEA Fatigue Safety Factor](https://github.com/user-attachments/assets/7eb0257c-480b-41ff-8b86-95c5f709648a)
![FEA Fatigue Tool](https://github.com/user-attachments/assets/bff0dffb-00ca-4ab0-a6b2-24a751066240)

## Finite Element Analysis (FEA)
### Video
https://github.com/user-attachments/assets/684e30f0-5ba8-4716-a56b-c2a44ff6e8ca

### Images
![FEA Geometry](https://github.com/user-attachments/assets/f2630c57-be3f-46e4-b401-6da40cf61219)
![FEA Side Profile](https://github.com/user-attachments/assets/afd37903-fb24-4587-a8b0-c20029118bf8)
![FEA Equivalent Stress](https://github.com/user-attachments/assets/92f3a034-cc90-41f5-8f39-b05546c6d58b)
![FEA Shear Stress](https://github.com/user-attachments/assets/31b2de84-d0bb-4011-b9e2-cccf13145396)
![FEA Total Deformation](https://github.com/user-attachments/assets/6c0f54d6-5c82-4b08-9f7d-9fe6f4401d2c)
