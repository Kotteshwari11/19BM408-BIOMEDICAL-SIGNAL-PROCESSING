# RECTANGULAR WINDOW BASED FIR FILTER DESIGN
# AIM :
To design a Low Pass FIR filter using Rectangular Window and analyze its magnitude and phase response using MATLAB.
# Theory :
Rectangular Window
The Rectangular window is defined as:
        w(n)=1≤n≤N
Characteristics:
Narrowest main lobe

Highest side lobes

High ripple (Gibbs phenomenon)

Sharp transition width

It simply truncates the ideal impulse response.

Design Equations
Ideal Low Pass Impulse Response:

h_d (n)=(sin⁡ω_c (n-α))/(π(n-α))

Where:

α=N/2

Actual filter:

h(n)=h_d (n)⋅w(n)

# ALGORITHM :
1.	Choose filter order N
2.	Choose cutoff frequency ωc
3.	Generate ideal impulse response
4.	Generate rectangular window
5.	Multiply both
6.	Plot frequency response

# MATLAB CODE :
"https://github.com/user-attachments/assets/1bfb34b5-7a03-46c2-87c9-41eeb853305e" 
# OUTPUT GRAPH :
![WhatsApp Image 2026-03-30 at 5 44 55 PM](https://github.com/user-attachments/assets/20060d23-a91c-404c-8a41-5d78f2abd594)
![WhatsApp Image 2026-03-30 at 5 45 20 PM](https://github.com/user-attachments/assets/ca7b4ca6-eb22-4139-b185-ddc3effd623e)

# RESULT :
The FIR filter was designed using Rectangular window.
