# HAMMING WINDOW BASED FIR FILTER DESIGN
# AIM :
To design a Low Pass FIR filter using Hamming Window and study its frequency characteristics.
# THEORY:

Hamming window is defined as:

w(n)=0.54-0.46cos⁡(2πn/N)

Characteristics:
Reduced side lobes

Better stopband attenuation (~41 dB)

Slightly wider main lobe than rectangular

Reduced ripple

Design Equation:

h(n)=h_d (n)⋅w(n)

Where hd(n) is ideal impulse response.

# ALGORITHM:
1.	Choose N and ωc
2.	Compute ideal impulse response
3.	Generate Hamming window
4.	Multiply and obtain h(n)
5.	Plot magnitude & phase

# MATLAB CODE :
"https://github.com/user-attachments/assets/bfc9054d-c1bc-4e88-b92f-90c66d6aeac4" 
# OUTPUT GRAPH :
![WhatsApp Image 2026-03-30 at 5 45 49 PM](https://github.com/user-attachments/assets/1d26fcd1-61ed-477a-b39f-33b99a83d070)
![WhatsApp Image 2026-03-30 at 5 46 07 PM](https://github.com/user-attachments/assets/78bae098-3e09-4781-bb62-8bf543844054)

# RESULT :
The FIR filter was designed using Hamming window .

