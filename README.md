Download Link: https://assignmentchef.com/product/solved-ee316-lab-11-and-12-mosfet
<br>



<strong>Lab 11 </strong>

<strong> </strong>Introduction




The MOSFET (Metal Oxide Semiconductor Field Effect Transistor) is a three terminal unipolar semiconductor. The MOSFET is a voltage controlled field effect transistor that differs from a JFET in that it has a metal oxide gate electrode which is electrically insulated from the main semiconductor N-channel or P-channel by a thin layer of insulating material. Thus, the gate terminal is isolated from the main current carrying channel, and no current flows into the gate. Just like the JFET, the MOSFET acts like a voltage controlled resistor where the current flowing through the main channel between the drain and source is proportional to the input voltage. MOSFETs operate in two different modes. In depletion mode, the transistor requires the Gate-Source voltage, (V<sub>GS</sub>) to switch the device OFF. The depletion mode MOSFET is equivalent to a normally slosed switch. In the enhancement mode, the transistor requires a gate-source voltage, (V<sub>GS</sub>) to switch the device ON. The enhancement mode MOSFET is equivalent to a normally open switch.

<strong>*Figure 11.1</strong> Symbolic representation of MOSFET.




<strong>*Figure 11.2</strong> Structural diagram of N-channel MOSFET







<strong>      </strong>

<h1>(a)</h1>

<strong> </strong>

<strong> </strong>




<h1>(b)</h1>




<strong>*Figure 11.3</strong> N-Channel MOSFET (a) Depletion Mode (b) Enhancement Mode.







<h1>(a)</h1>

<strong> </strong>

<strong> </strong>




<h1>(b)</h1>




<strong>*Figure 11.4</strong> P-Channel MOSFET (a) Depletion Mode (b) Enhancement Mode.










<strong>Figure 11.5</strong>










<table width="639">

 <tbody>

  <tr>

   <td colspan="2" width="160">V<sub>2</sub> = 2.5V</td>

   <td colspan="2" width="160">V<sub>2</sub> = 3V</td>

   <td colspan="2" width="160">V<sub>2</sub> = 3.5V</td>

   <td colspan="2" width="160">V<sub>2</sub> = 4V</td>

  </tr>

  <tr>

   <td width="80">V<sub>ds</sub></td>

   <td width="80">V<sub>gs </sub>=</td>

   <td width="80">V<sub>ds</sub></td>

   <td width="80">V<sub>gs</sub> =</td>

   <td width="80">V<sub>ds</sub></td>

   <td width="80">V<sub>gs</sub> =</td>

   <td width="80">V<sub>ds</sub></td>

   <td width="80">V<sub>gs</sub> =</td>

  </tr>

  <tr>

   <td width="80">(mV)</td>

   <td width="80">I<sub>d</sub> (mA)</td>

   <td width="80">(mV)</td>

   <td width="80">Id (mA)</td>

   <td width="80">(mV)</td>

   <td width="80">Id (mA)</td>

   <td width="80">(mV)</td>

   <td width="80">Id (mA)</td>

  </tr>

  <tr>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

  </tr>

  <tr>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

  </tr>

  <tr>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

   <td width="80"> </td>

  </tr>

 </tbody>

</table>

<strong>Table 11.1</strong>




<table width="156">

 <tbody>

  <tr>

   <td width="78">V<sub>gs</sub> (V)</td>

   <td width="78">I<sub>d</sub> (mA)</td>

  </tr>

  <tr>

   <td width="78"> </td>

   <td width="78"> </td>

  </tr>

  <tr>

   <td width="78"> </td>

   <td width="78"> </td>

  </tr>

  <tr>

   <td width="78"> </td>

   <td width="78"> </td>

  </tr>

  <tr>

   <td width="78"> </td>

   <td width="78"> </td>

  </tr>

  <tr>

   <td width="78"> </td>

   <td width="78"> </td>

  </tr>

  <tr>

   <td width="78"> </td>

   <td width="78"> </td>

  </tr>

  <tr>

   <td width="78"> </td>

   <td width="78"> </td>

  </tr>

  <tr>

   <td width="78"> </td>

   <td width="78"> </td>

  </tr>

  <tr>

   <td width="78"> </td>

   <td width="78"> </td>

  </tr>

  <tr>

   <td width="78"> </td>

   <td width="78"> </td>

  </tr>

 </tbody>

</table>

<strong>Table 11.2 </strong>

<u>Part 1</u>

<ul>

 <li>Construct the circuit in Figure 11.5 using the 2N70000 MOSFET.</li>

 <li>Set V<sub>2</sub> = 2.5V and then starting with V<sub>1</sub> = 0V, increase the value of V<sub>1</sub> until I<sub>d</sub> While adjusting the value of V<sub>1</sub>, measure V<sub>GS</sub>, V<sub>DS</sub>, and I<sub>d</sub> and record your results in Table 11.1. Repeat with V<sub>2</sub> = 3, 3.5, and 4V. Note: V<sub>DS</sub> is not equal to V<sub>1</sub>, and V<sub>GS</sub> is not equal to V<sub>2</sub>. <strong>Note: create your own table as you will need more rows than are provided in Table 11.1</strong>. Use your best judgment for how many data points to collect. Make sure to collect more data points in the non-linear regions.</li>

 <li>Plot the results that you have recorded in Table 11.1.</li>

 <li>Using your plot for Table 11.1 for each V<sub>GS</sub> value, identify the V<sub>DS</sub> range for which the MOSFET is in the linear ohomic region (i.e. where the MOSFET behaves like a voltage controlled resistor).</li>

 <li>For each V<sub>GS</sub> value, identify the minimum V<sub>DS</sub> value that places the MOSFET in saturation.</li>

</ul>




<u>Part 2</u>

<ul>

 <li>Construct the circuit in Figure 11.5 and set V<sub>1</sub> = 22V.</li>

 <li>Record the value of V<sub>GS</sub> and I<sub>d</sub> in the first row of Table 11.2 when V<sub>2</sub> = 0V. Fill out the rest of Table 11.2 by varying the value of V<sub>2</sub> from 2V in 0.25V increments until I<sub>d</sub> no longer increases.</li>

 <li>Plot the results that you have recorded in Table 11.2.</li>

 <li>Using your plot from Table 11.2, identify the threshold voltage (i.e. the minimum V<sub>GS</sub> needed for the MOSFET to conduct). Mark the threshold voltage on your plot.</li>

 <li>Based on your plots and Figures 11.3-11.4, is the 2N7000 an enhancement or depletion mode MOSFET? Is it an n-channel or p-channel device (NMOS or PMOS)?</li>

</ul>




Bonus Points (up to 100): Compare your MOSFET, JEFT (lab 9), and BJT (lab 7) results and identify the reasons these devices behave differently.  What are the MOSFET vs. JFET vs. BJT pros and cons?




<strong>Reference</strong>:

*Electronic Devices and Circuit Theory, 7<sup>th</sup> Ed.  by Robert Boylestad and Louis Nashelsky. <strong> </strong>







<h1>Lab 12</h1>

The purpose of this lab is to examine the bandwidth of the 2N7000 MOSFET with a range of frequencies from 10Hz to 3MHz. For each frequency the input and output voltages of the circuit will be measured. Finally, after a plot of the frequency vs. the gain is made, the bandwidth will be measured.

<strong> </strong>




<strong>Figure 12.1 Procedure: </strong>

<strong> </strong>

<ol>

 <li>Build the circuit as shown in Figure 12.1 and amplify a sinusoidal signal with V<sub>p</sub> = 100mV for the given frequency range (See table 12.1) using MOSFET (2N7000). In lab use the smallest amplitude that your function generator will output.</li>

</ol>




<ol start="2">

 <li>Based on Table 12.1 results, plot voltage gain as a function of frequency. Calculate the approximate bandwidth and identify f<sub>low</sub> and f<sub>high</sub>.</li>

</ol>




<ol start="3">

 <li>Comment on the phase relationship between the input and output waveforms.</li>

</ol>

<strong> </strong>

<strong>Bonus</strong> Connect a Bode plotter to the input and output. For Mode select Magnitude and for Horizontal and Vertical select Log. Under Horizontal set F to 3

MHz and I to 10 Hz. For Vertical set I to -30 dB and F to 30 dB (you may need to adjust the I and F settings for Vertical as you go). Modify the circuit to maximize the bandwidth <strong>while keeping the gain above 10 dB</strong> within the pass band of the circuit. You may change the value of V<sub>1</sub> or any of the capacitors or resistors (<strong>except the load resistor</strong>, R6). You may also add or remove resistors and capacitors. Use the oscilloscope to verify that the output is not clipped for input frequencies within the circuit’s bandwidth. Two example Bode plots are provided for clarification. <strong>Submit and discuss your modified circuit in the lab report (not the prelab). No credit will be given if you do not submit your modified circuit diagram. </strong>

<strong> </strong>

<strong>Bonus </strong>Compare MOSFET signal amplification to JFET (Lab # 10) and BJT (Lab # 08). What are the pros and cons of using MOSFETs, JFETs, and BJTs?

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<h1>Table 12.1</h1>

<strong> </strong>

<table width="559">

 <tbody>

  <tr>

   <td width="142"><strong>Frequency </strong></td>

   <td width="198"><strong>Vout </strong></td>

   <td width="219"><strong>Voltage Gain </strong></td>

  </tr>

  <tr>

   <td width="142">10</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">30</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">60</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">100</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">200</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">500</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">1 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">2 kHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">5 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">10 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">15 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">20 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">50 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">75 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">100 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">150 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">200 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">500 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">750 KHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">1 MHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">1.5 MHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">2.0 MHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

  <tr>

   <td width="142">3.0 MHz</td>

   <td width="198"> </td>

   <td width="219"> </td>

  </tr>

 </tbody>

</table>








































<strong> </strong>

<strong>Figure 12.2</strong> Bode plot for circuit as given







<strong> </strong>

<strong>Figure 12.3</strong> Bode plot for a modified circuit




The circuit that produced the Bode plot in Figure 12.3 has a bandwidth 162 kHz wider and a gain nearly 7 dB higher than the given circuit. You should be able to do better than Figure 12.3. Remember to use the oscilloscope to verify that the output is not clipped for input frequencies at f<sub>low</sub> and f<sub>high</sub>.


