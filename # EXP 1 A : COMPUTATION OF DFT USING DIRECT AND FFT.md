# EXP 1 A : COMPUTATION OF DFT USING DIRECT AND FFT

# AIM: 

# To Obtain DFT and FFT of a given sequence in SCILAB. 

# APPARATUS REQUIRED: 
PC installed with SCILAB. 

# PROGRAM: 
// DISCRETE FOURIER TRANSFORM 
clc;
clear;

x = [1 4 0 8];
N = length(x);
X = fft(x, -1);

subplot(2,1,1);
plot2d3(0:N-1, x);
xtitle("Original Sequence x(n)", "n", "Amplitude");

subplot(2,1,2);
plot2d3(0:N-1, abs(X));
xtitle("Magnitude Spectrum |X(k)|", "k", "Magnitude");


# OUTPUT: 

<img width="755" height="723" alt="image" src="https://github.com/user-attachments/assets/621fc3f9-2b23-4d99-8239-69666712d0f9" />

# RESULT: 
Thus, the desired output is obtained
