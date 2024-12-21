---
{"dg-publish":true,"permalink":"/physics/6-particles-and-medical-physics/capacitance/"}
---

##### Capacitors
- Capacitors are electrical devices used to store energy in electronic circuits by storing electric charge as electrical potential energy.
- Capacitance is the charge stored per unit potential difference between the conductive metals plates of a capacitor and it is measured in Farads where $1\ F =1 \ CV^{-1}$.
$$
C=\frac{Q}{V}
$$
-  Capacitors are charged by a power supply and the positive terminal pull electrons away from one of the plates which become positively charged and the negative terminal pushes electrons on to the other plate which is negatively charged.
	- When no more electrons can be pushed onto the negative plate due to electrostatic repulsion, the charging of the capacitor stops.
	- The potential difference across the plates slowly increases until it is the same as that of the power supply.
	- The charge of the plates increase until it is at its maximum charge defined by the capacitance of the capacitor.
	- The current against time graph of the current flowing through the capacitor is an exponential decay curve.
![Pasted image 20240912175454.png](/img/user/Attachments/Attachments/Pasted%20image%2020240912175454.png)
- Capacitors are discharged through a resistor with no power supply present and the electrons flow from the negative plate to the positive plate until there is an equal number on each plate with no potential difference.
	- At the start of the discharge the current is large and exponentially decays to zero.
	- The rate at which the capacitor discharges depends on the resistance and the higher the resistance the slower the charge will flow away from the capacitor so it takes longer to discharge.
![Pasted image 20240912175506.png](/img/user/Attachments/Attachments/Pasted%20image%2020240912175506.png)
- Capacitors connected in series have different potential difference across them but have the same charge where the total potential difference is defined by the total capacitance.
$$
\begin{align}
\frac{Q}{C_{total}}=\frac{Q}{C_{1}}+\frac{Q}{C_{2}}+\frac{Q}{C_{3}}+\dots \\
\Longrightarrow \frac{1}{C_{total}}=\frac{1}{C_{1}}+\frac{1}{C_{2}}+\frac{1}{C_{3}}+\dots
\end{align}
$$
- Capacitors connected in parallel each have a different charge as the current is split and the total charge is defined by the total capacitance while the potential difference across all capacitors is the same.
$$
\begin{align}
C_{total}V=C_{1}V+C_{2}V+C_{3}V+\dots \\
\Longrightarrow C_{total}=C_{1}+C_{2}+C_{3}+\dots
\end{align}
$$
- When capacitors are charged, work is done on the electrons and electrical energy is stored on the plates and as the charge increases a greater amount of work must be done to increase the charge.
- The charge on a capacitor is directly proportional to its potential difference so the electrical potential energy stored in the capacitor can be determined from the area under a potential difference against charge graph.
$$
E=\frac{1}{2}QV=\frac{1}{2}CV^2= \frac{Q^2}{2C}
$$
- The time constants is the time taken for the charge, current of voltage of a discharging capacitor to decrease to 37 % of its original value or 63 % of its maximum value if charging.
$$
\tau = CR
$$
	where *R* is the resistance of the resistor.
- The time to half for a discharging capacitor is the time taken for the charge, current or voltage of a discharging capacitor to reach half of its initial value.
$$
t_{1/2}=\ln(2) \tau
$$
- The time constant is used in the exponential decay equations of the current, charge and potential difference of a capacitor charging therefore the smaller the time constant, the quicker the exponential decay.
$$
\begin{align}
I=I_{0}e^{-\frac{1}{\tau}} \\
Q=Q_{0}e^{-\frac{1}{\tau}} \\ 
V=V_{0}e^{-\frac{1}{\tau}} 
\end{align}
$$
	where $I_{0}$ is the initial current before discharge, $Q_{0}$ is the charge on the capacitor plates, $V_{0}$ is the potential difference across the capacitor.
- When charging the shape of the charge-time graphs and potential difference-time graphs are the same.
$$
\begin{align}
Q=Q_{0}\left( 1-e^{-\frac{1}{\tau}} \right) \\ \\
V=V_{0}\left( 1-e^{-\frac{1}{\tau}} \right)
\end{align}
$$
	where $Q_{0}$ is the maximum charged stored in the capacitor when fully charged, $V_0$ is the maximum potential difference across the capacitor when fully charged.
- Taking logarithms of both sides of a charge-discharge equation will result in a straight-line equation which confirms the exponential relationship.
- The area underneath a current-time graph for a capacitor is the charge stored in the capacitor in the time interval.
- The gradient of the charge-time graph is the current at that point during charging and discharging.
- For a discharging capacitor:
$$
\frac{\Delta Q}{\Delta t}=-\frac{Q}{RC}
$$
