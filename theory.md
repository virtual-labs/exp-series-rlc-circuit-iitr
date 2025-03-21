# Series RLC Circuit 

### Theory

<div align="justify" style="font-size:18px;">

A series RLC circuit is a basic electrical circuit consisting of a resistor (R), an inductor (L), and a capacitor (C) connected in series with a voltage source. 
The components interact to create a circuit with unique electrical characteristics that depend on the frequency of the applied voltage.

<center>

![transformer1](images/series1.png)

Figure 1: Series RLC circuit
</center>

<br>

In this arrangement:<br>

•	The resistor (R) opposes current flow and dissipates energy as heat.<br>
•	The inductor (L) opposes changes in current and stores energy in its magnetic field.<br>
•	The capacitor (C) opposes changes in voltage and stores energy in its electric field.<br>

In a pure ohmic resistor the voltage waveform is **"in-phase"** with the current. In a pure inductance the voltage waveform **"leads"** the current by 90° and in a pure capacitance the voltage waveform **"lags"** the current by 90°.

Let,   

 V<sub>R</sub>  =  IR  = voltage drop across R   -in phase with I<br>
 V<sub>L</sub>  = I.X<sub>L</sub> = voltage drop across L   -leading I by π/2<br>
 V<sub>C</sub>  = I.X<sub>C</sub> = voltage drop across C   -lagging I by π/2<br>

**Inductive Reactance X<sub>L</sub>**: The opposition to current flow due to the inductor is given by:
                                  <center> X<sub>L</sub> = 2πf L </center> <br>
Where f is the frequency of the AC supply and L is the inductance of the inductor.

**Capacitive Reactance X<sub>C</sub>**: The opposition to current flow due to the capacitor is given by
                                <center> X<sub>C</sub> = 1/2πf C  </center> <br>
where C is the capacitance of the capacitor.

<center>

![series2](images/series2.png)

Figure 2: Voltage triangle

</center>

In the voltage triangle of Fig. 2, OA represents V<sub>R</sub>, AB and AC represents the inductive and capacitive drops respectively. It will be seen that V<sub>L</sub> and V<sub>C</sub> are 180° out of phase with each other i.e., they are in direct opposition to each other.<br>

Subtracting BD from AB, we get the net reactive drop AD = I (X<sub>L</sub> - X<sub>C</sub>).<br>
The applied voltage V is represented by OD and is the vector sum of OA and AD.<br>

Therefore, 

<center> 

$OD = \sqrt{OA^2 + AD^2} \quad \text{or} \quad V = \sqrt{(IR)^2 + (IX_L - IX_C)^2} = I\sqrt{R^2 + (X_L - X_C)^2}$ </br></br></br>
or $ I= \frac {V}{\sqrt{R^2 + (X_L - X_C)^2}} = \frac{V}{\sqrt{R^2+X^2}}=  \frac {V}{Z}$

</center>

The term $\sqrt{R^2 + (X_L - X_C)^2}$ is known as the impedance of the circuit. Obviously,</br></br> 
$(\text{impedance})^2 = (\text{resistance})^2 + (\text{net reactance})^2$</br></br> 
<center>

or $Z^2 = R^2 + (X_L - X_C)^2 = R^2 + X^2$
</center>

Where R is the resistance and X is the net reactance shown in Fig.3

<center>

![series3](images/series_new3.png)

Figure 3: Impedance triangle

</center>

The phase angle &straightphi; is given by:

<center>

$\tan \phi = \frac{X_L - X_C}{R} = \frac{X}{R} = \frac{\text{net reactance}}{\text{resistance}}$

</center>

<center>

$\text{Power factor is } \cos \phi = \frac{R}{Z} = \frac{R}{\sqrt{R^2 + (X_L - X_C)^2}} = \frac{R}{\sqrt{R^2+X^2}}$

</center>

Hence, it is seen that if the equation of the applied voltage is v = V<sub>m</sub> sinωt, then the equation of the resulting current in an RLC circuit is given by i = I<sub>m</sub> sin (ωt + ∅).
The +ve sign is to be used when current leads i.e., X<sub>C</sub> > X<sub>L</sub>.
The -ve sign is to be used when current lags i.e., X<sub>L</sub> > X<sub>C</sub>.

Further, Power absorbed in the circuit can be calculated as,<br>

<center> Apparent Power, S = VI <br>
Active Power, P = VI cos∅ <br>
Reactive Power, Q = VI sin∅ <br> </center>

<b>Advantages of series RLC circuit:</b><br>

1. Series RLC circuits can be utilised to improve the power factor in AC power systems, reducing energy losses and enhancing efficiency.<br>
2. Series RLC circuits are easy to design and analyse, making them ideal for filtering and tuning applications.<br>
3. Amplify voltages across the inductor and capacitor at resonance, useful in oscillators and signal generation.<br>
4. In antenna design, Series RLC circuits help achieve resonance at desired operating frequencies, maximising radiation  efficiency.<br>

<b> Disadvantages of series RLC circuit:</b><br>

1. Excessive current or voltage can also lead to overheating or damage to the resistor, inductor, or capacitor, reducing the circuit's lifespan.<br>
2. If one point breaks in the series circuit, the total circuit will break.<br>
</div>

