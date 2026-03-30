# HANNING WINDOW BASED FIR FILTER DESIGN

# AIM:

To design a Low Pass FIR filter using Hanning (Hann) Window and analyze its response.
# THEORY :

Hanning window is defined as:

w(n)=0.5-0.5cos⁡(2πn/N)

Characteristics:

1)Smooth tapering at ends

2)Reduced spectral leakage

3)Moderate stopband attenuation (~31 dB)

4)Wider main lobe than Hamming

Design Equation:

h(n)=h_d (n)⋅w(n)

# ALGORITHM :
1.	Select N and ωc
2.	Compute ideal response
3.	Generate Hanning window
4.	Multiply and obtain FIR coefficients
5.	Plot response

# MATLAB CODE :
"https://github.com/user-attachments/assets/2de72c2a-46dd-48df-9c28-7173d2b97be7"
# OUTPUT GRAPH :
![WhatsApp Image 2026-03-30 at 5 46 26 PM](https://github.com/user-attachments/assets/2b1e6274-3389-482f-a67e-ac840fe21bbb)
![WhatsApp Image 2026-03-30 at 5 46 49 PM](https://github.com/user-attachments/assets/33da03aa-624a-460f-88e8-bce8da740a25)

# RESULT :
The FIR filter was designed using Hanning window.
