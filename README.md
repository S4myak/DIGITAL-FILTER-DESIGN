# DIGITAL-FILTER-DESIGN

**COMPANY**: CODTECH IT SOLUTIONS PVT.LTD

**NAME** :SAMYAK MANOJ PATIL

**INTERN ID** :CT06MVO

**DOMAIN** :VLSI

**BATCH DURATIOIN** :January 15th, 2025 to February 15th, 2025

**MENTOR NAME** :NEELA SANTHOSH KUMAR

**DESCRIPTION** :
 # INFORMMATION:
   A Digital FIR (Finite Impulse Response) Filter is a type of digital filter that processes a sequence of input samples to produce an output sequence. It is called "finite" because its impulse response has a finite duration, meaning it only responds to input signals over a limited period of time, typically defined by the number of filter taps 

# FEATURES OF FIR:
 
  1)Finite Impulse Response:
    The "impulse response" refers to how a filter responds to a single input pulse (impulse). In an FIR filter, this impulse response is of finite length, meaning it lasts only for a specific        number of time steps, and after that, the output becomes zero.
    Mathematically, the impulse response is the sequence of coefficients that define how much each input sample (over a certain time window) contributes to the output.
    
  2) Linear and Time-Invariant:
    FIR filters are linear because they satisfy the principles of superposition and scaling.
    They are time-invariant, meaning their behavior does not change over time. The same input will always produce the same output, regardless of when it is applied.

  3) Non-Recursive (No Feedback):
    FIR filters are non-recursive, meaning they do not use feedback. The output at any given time is only a weighted sum of current and previous input samples, with no dependence on previous         output values.
    This contrasts with IIR (Infinite Impulse Response) filters, which involve feedback and can have an infinite impulse response.

  4)Filter Coefficients:
    The coefficients ℎ[𝑘] ,h[k] define the characteristics of the FIR filter. These coefficients are typically designed based on the filter's desired behavior, such as low-pass, high-pass ,band-     pass, etc.
    For example, for a low-pass filter, the coefficients will attenuate high-frequency components of the signal, passing only low-frequency components.
    
# GENERAL EQUATION OF FIR FILTER:
![Image](https://github.com/user-attachments/assets/e5310942-b7a7-46fc-8bc8-c227503995d6)
 
Where:
 y[n] is the output signal.
 x[n] is the input signal.
 h[k] are the filter coefficients (taps).
 M is the number of taps (order + 1).


# STEPS TO MAKE A DIGITAL FINITE IMPULSE RESPONSE FILTER:
  1) Define Specifications: Decide on the filter type (low-pass, high-pass, etc.), sampling frequency, cutoff frequency, and filter order.
  2) Choose a Design Method: Select from methods like the Window Method (Hamming, Hanning), Frequency Sampling, or the Parks-McClellan Algorithm.
  3) Calculate Coefficients: For the Window Method, compute the ideal impulse response and apply a window function.
  4) Implement the Filter:
      In MATLAB, use functions like fir1 to design and simulate the filter.
      In Verilog, write the code to process the input using shift registers and multiply with coefficients.
  5)Simulate: Test the filter using a testbench (Verilog) or input signals (MATLAB) to observe the response.

# WEBSIITES USED :
WEBSITES :
https://www.elprocus.com/fir-filter-for-digital-signal-processing/
https://web.ece.ucsb.edu/~yoga/courses/DSP/P11_FIR_Design_Examples.pdf

YOUTUBE VIDEOS :
https://youtu.be/7f50sQYjNRA?si=-SiX07dhotZHuz4M
https://youtu.be/_WoqwSBkhj0?si=Eao8n5vFRjgEyQyr
https://youtu.be/Jf9NvCU6siU?si=OBRFhs_-goiIEXu0

# OUTPUT:
![Image](https://github.com/user-attachments/assets/e0fb5f2e-ddcd-424b-8306-d4c8c7d92d03)


# APPLICATION :
 
  1) Signal Processing: FIR filters are used in various applications such as noise reduction, signal smoothing, and feature extraction in fields like audio processing, image processing, and           biomedical signal processing.

  2) Communications: FIR filters are used in communication systems to shape signals, filter out unwanted frequencies, or perform equalization.

  3) Control Systems: FIR filters can be used in control systems for filtering sensor data or feedback signals.

   
