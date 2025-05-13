# csc347-ens211-lab-6-2-bit-adder-subtractor-solved
**TO GET THIS SOLUTION VISIT:** [CSC347-ENS211 Lab 6-2-bit Adder/Subtractor Solved](https://www.ankitcodinghub.com/product/csc347-ens211-lab-6-2-bit-adder-subtractor-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94109&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC347-ENS211 Lab 6-2-bit Adder\/Subtractor Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<strong>Lab </strong><strong>6&nbsp; 2-bit Adder/Subtractor </strong>

<ol>
<li><strong>Introduction </strong></li>
</ol>
Arithmetic circuits such as the digital adder and subtractor are simple combinational logic. In this lab, students learn to construct a 2-bit full adder/subtractor from basic combinational logic.

&nbsp;

<ol start="2">
<li><strong>Experimental Equipment List</strong>:
<ul>
<li>74HC<strong>08</strong> AND gate chip, two 74HC<strong>86</strong> XOR gate chips, and 74HC<strong>32 </strong>OR gate chip</li>
</ul>
</li>
</ol>
<table width="100%">
<tbody>
<tr>
<td><strong>(XOR)</strong></td>
</tr>
</tbody>
</table>
&nbsp;

<ol start="3">
<li><strong>Design Procedure</strong></li>
</ol>
Hierarchy in circuit design is often necessary to manage complex layouts that reuse common components such as basic logic gates.&nbsp;We start with logic gates, then we build half adders from them, then a full adder from half adders, and finally, we cascade 2 full adders to obtain a 2-bit adder block. The basic half-adder diagram is:

The Boolean expression for the sum of A and B is S = A⊕B, and carry is C =A⋅B. The half-adder adds two single bits, A and B, but does not make a provision for carry-in. If we wish to make a full adder (an adder that provides for carry-in), it looks like:

The full adder sum is: S =A⊕B⊕Cin, and carry is Cout =AB + (A⊕B)Cin, The full adder accommodates three variables, two input bits and a carry, which can be built from 2 half adders. A 2-bit full adder requires connecting two 1-bit full adders together like below.

&nbsp;

The 2-bit full adder can be used to perform subtraction by inverting B input and setting Cin = 1. The addition and subtraction operations can be combined into one circuit with one common binary adder by including an XOR gate with each full adder and a control input M that controls the operation.

&nbsp;

<ol start="4">
<li><strong>Circuit Construction on Tinkercad</strong></li>
</ol>
<strong>&nbsp;</strong>

<ul>
<li>After you log in to the Tinkercad, copy and paste the following link to your web browser <a href="https://www.tinkercad.com/things/h3EJqRMU0aa">https://www.tinkercad.com/things/h3EJqRMU0aa</a> to make a copy of the Lab 6 starter circuit.</li>
</ul>
&nbsp;

<ul>
<li>Constructing a 2-bit adder/subtractor requires XOR, OR, and AND gates. The gates should be connected as follows</li>
</ul>
&nbsp;

<strong>Switches:&nbsp;&nbsp; A1, A0, B1, B0, M&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; LEDs:&nbsp;&nbsp;&nbsp;&nbsp; C2, S1, S0</strong>

&nbsp;

<ul>
<li>Connect inputs A1-A0 (number A) and B1-B0 (number B) to four of the <strong>data switches</strong> according to the order of <strong><u>A1, A0, B1, B0</u></strong> from left to right. A fifth data switch should be connected to <strong>M</strong>. Note that A0 and B0 are the least significant bits of each number. The Sum <strong>S1-S0</strong> and carry-out <strong>C2</strong> should go to three <strong>LED</strong> inputs according to the order of <strong><u>C2, S1, S0</u></strong> from left to right.</li>
<li>Start the simulation and turn on combinations of the input switches to check that addition/subtraction of two-bit binary numbers is successful.</li>
<li>Complete the following additions/subtractions at least: 1+2, 3+1, 0+3, 2+2, 3+3, 3-1, 2-2, 2-0, 3-2, 1-2. Tabulate the results.</li>
</ul>
<strong>Note the subtraction result is 2 bit and not 3 bits so you need to disconnect the C2 wire from the LED to the bottom breadboard to see the correct result.</strong>

<strong><u>Submission Instructions:</u></strong>

<u>Lab work submission</u>

<ol>
<li>Take screenshots of your circuit for all your testing cases.</li>
<li>Copy the link of your circuit for sharing.</li>
<li>On the Blackboard, click on Lab 6. Attach the screenshots from Step 1 and paste the link from Step 2 into the Comments area, then hit the “Submit” button.</li>
</ol>
&nbsp;

<strong>Lab report is not needed for this lab. </strong>

&nbsp;
