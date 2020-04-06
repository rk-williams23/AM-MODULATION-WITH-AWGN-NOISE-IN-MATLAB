# AM MODULATION WITH AWGN NOISE IN MATLAB
Simulation a MATLAB program for amplitude modulation with Vc>Vm , Fc>Fm.
Adding an additive white Gaussian noise with SNR=10dB and analyze by varing the SNR value.

ALGORITHM:
1. Create a vector 't'(time) that varies from zero to two (or) three combination.
2. Create a message Signal with Single Sine frequency or combination of few Sine frequency. All the frequency used in message signal should be less than the carrier frequency likewise amplitude of message signals should be less than carrier amplitude. [AmSin(2πfnt)].
3.Create the modulated Signal using the Am equation. Am[1+maSin(2πfnt)]Sin(2πfct)
4.Create a carrier Signal [Ac Sin(2πfct)].
5.Introduce AWGN noise and observe the changes in the amplitude modulated Signal.
6.Plot the message signal, carrier signal, and amplitude modulated signals with AWGN noise.
