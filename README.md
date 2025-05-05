# ee-cse371-lab-1-parking-lot-occupancy-counter-solved
**TO GET THIS SOLUTION VISIT:** [EE-CSE371 Lab 1-Parking Lot Occupancy Counter Solved](https://www.ankitcodinghub.com/product/ee-cse371-lab-1-parking-lot-occupancy-counter-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99232&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE-CSE371 Lab 1-Parking Lot Occupancy Counter Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Lab1: Parking Lot Occupancy Counter

</div>
</div>
<div class="layoutArea">
<div class="column">
Lab Objectives

</div>
</div>
<div class="layoutArea">
<div class="column">
This lab provides a refresher of the finite state machines that you learned in EE 271 by designing a parking lot occupancy counter.

Laboratory Design Kits

We will use the Quartus Prime Software/ ModelSim and LabsLand. You do not need to use any physical lab kits.

Please see Lab 0 regarding how to install Quartus Prime Software/ModelSim and log in LabsLand.

Assigned Task

Parking Lot Occupancy Counter

Consider a parking lot with a single entry and exit gate. Two pairs of photosensors are used to monitor the activity of cars, as shown in Figure 1. When an object is between the photo transmitter and the photoreceiver, the light is blocked, and the corresponding output is asserted to 1. By monitoring the events of two sensors, we can determine whether a car is entering or exiting, or a pedestrian is passing through. For example, the following sequence indicates that a car enters the lot:

<ul>
<li>● &nbsp;Initially, both sensors are unblocked (i.e., the a and b signals are 00).</li>
<li>● &nbsp;Sensor a is blocked (i.e., the a and b signals are 10).</li>
<li>● &nbsp;Both sensors are blocked (i.e., the a and b signals are 11).</li>
<li>● &nbsp;Sensor a is unblocked (i.e., the a and b signals are 01).</li>
<li>● &nbsp;Both sensors become unblocked (i.e., the a and b signals are 00).</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Figure 1. Parking lot sensors

Design a parking lot occupancy counter as follows:

<ol>
<li>Design an FSM with two input signals, a and b, and two output signals, enter and exit. The enter and exit signals assert true for one clock cycle when a car enters or exits the lot, respectively. Derive the SystemVerilog code for the FSM and simulate it in ModelSim. Do not assume that cars will not change direction while entering or exiting the parking lot.</li>
<li>Design a counter with two control signals, inc and dec, which increment and decrement the counter when asserted. Assume that the maximum capacity of the parking lot is 25 spots. however, you may test (and demo) your system with a maximum of 5 spots. Your system must work with both of these sizes. Derive the SystemVerilog code for the FSM and simulate it in ModelSim.</li>
<li>Combine the counter and the FSM and then model the parking lot, using two switches on the breadboard to mimic the two sensor outputs and the seven-segment displays to display the car count. Your system should have the following:
<ol>
<li>Display the car counts as they enter the parking lot on the seven-segment displays HEX0 and HEX1.</li>
<li>If the counter reaches 25 (or 5 for simulation and demo purposes), display the word “FULL” on HEX5-HEX2</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
c. As cars exit the lot, the counter decrements and the corresponding number should be displayed on HEX0 and HEX1.

<ol start="4">
<li>When the lot is empty. Display the word “CLEAR” on HEX5-HEX1 and display the number ‘0’ on HEX0.</li>
<li>Use 2 LEDs on the breadboard to represent the a and b signals. When a is 1, turn on the LED on the left, and when a is 0, turn off the LED on the left. Stimulatingly, when b is 1, turn on the LED on the right, and when b is 0, turn off the LED on the right.</li>
<li>Use the third switch on the breadboard as the reset signal.</li>
</ol>
4. Please read the “GPIO guide” for the instructions regarding how to wire and use

switches and LEDs. The general rule is labeled as below.

<ol>
<li>Wire 2 LEDs to output ports (GPIO0_0[26] and GPIO0_0[27])</li>
<li>Wire 3 switches to any input ports (GPIO0_0[5] – GPIO0_0[22]) (Please pick any
three you would like to use, and update your SystemVerilog code accordingly)
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 2. LabsLand GPIO headers

<ol start="5">
<li>Simulate the system in ModelSim.</li>
<li>Upload the program onto LabsLand FPGA and record a 2-3 mins video to demonstrate your work. Note, we do not need to see your compilation part.</li>
<li>Create a block diagram for your system and include it in your lab report.</li>
<li>In the report, include the state diagram(s) that you used in designing this system</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Lab Demonstration and Submission Requirements

<ul>
<li>● &nbsp;Record a video to demo the task assigned above. You will need to demonstrate the soundness of your design by executing the design on the FPGA. Moreover, you are expected to utilize testbench simulations to demonstrate that your modules work as expected.</li>
<li>● &nbsp;Write a Lab Report, as framed by the Lab Report Outline document on Canvas. Comment your code. Follow commenting guidelines as discussed in the Commenting Code document on Canvas. Submit your lab report as a pdf file and all of your SystemVerilog files on Canvas.</li>
<li>● &nbsp;On Padlet, write about a problem you had in the lab and the fix to it, and share a tip or trick you learned while working on the lab. You can also share an aha moment that you discovered while working on the lab. Avoid duplicating comments made by your classmates. NO videos for this Padlet task, please use textual comments. The link to the Padlet can be found in the corresponding Canvas assignment.</li>
</ul>
</div>
</div>
</div>
</div>
