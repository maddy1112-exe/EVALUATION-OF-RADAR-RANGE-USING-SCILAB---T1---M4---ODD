
## Aim
To calculate the maximum range of a radar system using the Radar Range Equation and verify the results through Scilab programming.

## Apparatus Required
1. **Software:** Scilab environment
2. **Hardware:** Personal Computer

---

## Theory
The Radar Range Equation is a fundamental formula used in radar system design to determine the maximum range at which a radar can detect a target. 
<img width="346" height="554" alt="image" src="https://github.com/user-attachments/assets/8d4d0bab-8b23-4a88-acc1-a9f490661b4c" />

### Mathematical Representation
The maximum radar range $R_{\max}$ is given by:

$$R_{\max} = \left( \frac{P_t G_t G_r \lambda^2 \sigma}{(4\pi)^3 P_{\min}} \right)^{\frac{1}{4}}$$

Where:
* $R_{\max}$ : Maximum detectable range of the radar (m)
* $P_t$ : Transmitted power (W)
* $G_t$ : Gain of the transmitting antenna
* $G_r$ : Gain of the receiving antenna
* $\lambda$ : Wavelength of the radar signal (m), calculated as $\lambda = \frac{c}{f}$ (where $c = 3 \times 10^8 \text{ m/s}$)
* $\sigma$ : Radar cross-section of the target ($\text{m}^2$)
* $P_{\min}$ : Minimum detectable signal power of the receiver (W)

---

## Procedure / Algorithm
1. **Set Up the Scilab Environment:** Launch the Scilab workspace/console.
2. **Define Parameters:** Set values for transmitted power ($P_t$), antenna gains ($G_t, G_r$), frequency ($f$), radar cross section ($\sigma$), and minimum power ($P_{\min}$).
3. **Calculate Wavelength:** Convert signal frequency to wavelength using $\lambda = \frac{c}{f}$, where $c = 3 \times 10^8 \text{ m/s}$.
4. **Define Radar Range Equation:** Compute the numerator and denominator using Scilab's built-in math functions and `%pi`.
5. **Calculate Maximum Range:** Evaluate $R_{\max}$ by raising the ratio to the power of $0.25$ (1/4th power).
6. **Execute and Display Results:** Run the Scilab script (`.sce`) to display the maximum radar range in meters and kilometers.
<img width="293" height="486" alt="image" src="https://github.com/user-attachments/assets/d1f5e7f2-838c-48d7-b6f6-a432746a27ae" />
<img width="267" height="488" alt="image" src="https://github.com/user-attachments/assets/89dcd1de-a057-46a9-a478-764deec93634" />

---

## MODEL GRAPH
<img width="809" height="628" alt="image" src="https://github.com/user-attachments/assets/a5e12449-1fcd-44b9-a426-03d89db6c96c" />
<img width="1237" height="653" alt="image" src="https://github.com/user-attachments/assets/f283b18e-d674-417a-964f-0eb1eba64454" />
<img width="821" height="627" alt="image" src="https://github.com/user-attachments/assets/93afc474-7cec-463a-8b11-7d4b6392031d" />
## RESULT
<img width="300" height="440" alt="image" src="https://github.com/user-attachments/assets/6219c525-6044-455f-8a0b-0cc35823d9f5" />


