# DIFFERENTIATOR-USING-OP-AMP

AIM:
To design and test the performance of differentiator circuits using Op-amp.

APPARATUS REQUIRED:
<img width="711" height="200" alt="image" src="https://github.com/user-attachments/assets/bb2d2881-17e3-4c7d-bbb1-ad332bbbc5c9" />

THEORY:
DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,

<img width="175" height="52" alt="image" src="https://github.com/user-attachments/assets/5577dd59-b261-43e8-852e-28c4a9bfea20" />

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:
1.	Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 µF, calculate the value of Rf.
2.	   Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.

The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

DESIGN (DIFFERENTIATOR):

Design an op-amp differentiator that will differentiate an input signal with fmax = 100HZ
Select fa = fmax = 100 HZ = 1 / 2πRFC1
Let C1 = 0.1μF
Then RF = 1 / 2π(102)(10-7)
                = 15.9KΩ
Now choose fb = 10fa = 1 / 2πR1C1
Therefore, R1 = 1 / 2π(103)(10-7)
         		= 1.59KΩ
Since RFCF = R1C1
We get, CF = (1.59*103*10-7) / 15.9*103
       = 0.01μF

DIFFERENTIATOR  CIRCUIT DIAGRAM:
<img width="759" height="414" alt="image" src="https://github.com/user-attachments/assets/ed2d11b0-7ae1-4526-b4f6-27014619c24a" />

PROCEDURE:
1. Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3. By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4. The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.

MODEL GRAPH:  
DIFFERENTIATOR          
(i) SINE WAVE INPUT
<img width="688" height="480" alt="image" src="https://github.com/user-attachments/assets/5a790cb8-1a8b-4990-b599-3c7680c24545" />

(ii) SQUARE WAVE INPUT
<img width="757" height="447" alt="image" src="https://github.com/user-attachments/assets/3bb38583-c020-43ad-8b15-c03f1f545842" />

TABULATION:
![WhatsApp Image 2025-10-28 at 10 51 56_a77487cb](https://github.com/user-attachments/assets/76adf1d1-4a95-425d-a2ab-87679ea57e16)


GRAPH:
![WhatsApp Image 2025-10-28 at 10 51 56_6a1f333c](https://github.com/user-attachments/assets/ff832dbb-6751-4788-82fd-f874855203b7)
![WhatsApp Image 2025-10-28 at 10 51 56_bdf87a76](https://github.com/user-attachments/assets/942aba2e-7898-4355-9635-cc5d1810c3c3)



RESULT:
thus the differentiator using opamp are designed and their  performance was successfully using opamp741
