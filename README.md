# cse306-assignment-1-4bit-alu-design-solved
**TO GET THIS SOLUTION VISIT:** [CSE306 Assignment 1-4bit ALU design Solved](https://www.ankitcodinghub.com/product/cse306-assignment-1-4bit-alu-design-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;102991&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE306&nbsp;Assignment 1-4bit ALU design Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Introduction

As part of this assignment, you have to submit both software simulation and hardware implementa- tion of a simplified Arithmetic Logic Unit (ALU). The functional design specification for each group of each section can be found in Appendix A. This is a group assignment, and all group members have to participate equally. The software simulation submission deadline for all sections is the same, and it is June 8, 2022 (Wednesday) at 11:59 PM. On the other hand, the hardware implementa- tion deadline is the next sessional day and is different for each section (see the Deadline section for details). You also have to write a group report and submit it during the evaluation day.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

•

• •

•

</div>
<div class="column">
Specification for 4-bit ALU Simulation

The functional design specification for each group of each section can be found in Appendix A. First, read the specification of your group carefully. Then, go through the following require- ments/instructions of this section.

Efficiently design (with minimum possible ICs) the ALU according to the specification. In addition, you need to implement the following flags.

– Carry (C)

– Sign (S)

– Overflow (V) – Zero (Z)

Flags will be affected as per the rules of Assembly Language. However, we have added some exceptions (only for this assignment) to incorporate flexibility to flag status bits after logical operations. Remember that this flexibility is to make your assignment easier, although it breaks some of the rules of the assembly programming language.

1. For NOT Operation:

<ul>
<li>– &nbsp;After the NOT operation, which makes the result to 0000, if Z becomes 0 from 1, it will not be accepted. However, if Z becomes 1 or if Z value remains unchanged, both will be accepted.</li>
<li>– &nbsp;After the NOT operation, if S remains unchanged or it reflects the highest order bit of the result, both will be accepted. But if S bit changed and it changed to a wrong value, it will not be accepted.1</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
– To make your life easier, we shall not check the C and V bits after NOT operation, i.e., you can consider these as Don’t care.

2. For AND/OR/XOR Operation:

– C and V should be cleared (0) after the operation. – S and Z should be changed according to the output.

<ul>
<li>Any 2-input SSI (AND, OR, NOT, XOR etc.) and MSI (MUX, Decoder, Adder etc.) chip can be used.</li>
<li>Emphasis should be given on efficiency of design and minimization of ICs used.</li>
<li>For simulation, you can use any simulation software.</li>
<li>Your software design must be in IC-level.</li>
<li>Software Simulation Submission: A submission link will be opened on Moodle for sub- mitting your ALU simulation. Make a folder containing all your simulation project files, zip it and submit it following the naming format. If you submit only a single project file, then just submit the file following the naming format. The naming format should be your section name followed by your group id (e.g., B1 Group7). Please ensure a single submission from each group (only a single member of the group should submit).</li>
<li>Report Preparation Guideline: Your have to write a report containing the followings:– Introduction

– Problem Specification with assigned instructions – Detailed design steps with k-maps (if applicable) – Truth Table

– Block Diagram

– Complete Circuit diagram

– ICs used with count as a chart

– Simulator used along with the version number

– Discussion

The report must be handwritten.
</li>
<li>Software Simulation, Hardware Implementation Evaluation and Report Submis- sion: Both software simulation and hardware implementation will be evaluated in the regular laboratory for respective sections (See the Deadline section for the specific time and date). Each group has to bring at least one laptop to show the software simulation for the group. As an alternative, a group can install the required simulator on a laboratory PC before their eval- uation day. You have to show the full working hardware implementation during the sessional time. Also, you need to submit your report at the beginning of the sessional.</li>
<li>For hardware implementation, you can lend the required instruments from the laboratory from now on (on the condition of returning these immediately after the evaluations and without any alternation), or you can use your own instruments.</li>
<li>Any type of plagiarism will be punished.</li>
<li>All the specified date and time is according to the Bangladesh Time. Late submission is not allowed.2</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
3 Deadline

Software Simulation Submission Deadline: For all sections: June 8, 2022 (Wednesday) Bangladesh Time.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
<div class="column">
Software Simulation and Hardware Evaluation Timeline:

• A1: June 14, 2022 (11 AM) • A2: June 21, 2022 (11 AM) • B1: June 12, 2022 (2:30 PM) • B2: June 19, 2022 (2:30 PM)

Where to Ask?

</div>
</div>
<div class="layoutArea">
<div class="column">
For any query, you can ask your instructor during the theory or sessional class. You can also email at ”madhusudan.buet@gmail.com”. Please allow at least two days to respond to your answer (In most cases, your question will be answered in the shortest possible time). Hope you will enjoy the assignment. Best wishes to you!

5 Version

This section contains the version of the assignment. It starts with Version 0. If we find some major problems in this assignment description file, then we shall change this pdf. If that case, we shall increase the version number and list the changes in this section. So, keep an eye on this version number of the pdf in the moodle to see whether the version has been changed or not. If it is changed, first read this section to see where the changes have been made and whether it is applicable to your group. On the other hand, if the changes are minor (for example, correcting the grammatical mistakes), then the version number will not be changed.

5.1 Version 0

This is the initial version of the problem description pdf.

5.2 Version 1

• In the ”Specification for 4-bit ALU Simulation” sections following updates have been made.

<ul>
<li>– &nbsp;SSI chip has been restricted to 2-input only.</li>
<li>– &nbsp;Your software design must be in IC-level.</li>
<li>– &nbsp;A step in report writing, ”Detailed design steps with k-maps (if applicable)”, has been added.</li>
<li>– &nbsp;It has been specified that report writing must be handwritten.3</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Appendix A

</div>
</div>
<div class="layoutArea">
<div class="column">
Functional Design Specifications for All Groups

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
For Section A1

</div>
</div>
<div class="layoutArea">
<div class="column">
Section A1

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
cin

</div>
</div>
</td>
<td></td>
<td colspan="6" rowspan="1">
<div class="layoutArea">
<div class="column">
Functions for

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
cs2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
cs1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
cs0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 6

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Incerement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Increment A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Increment A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
x

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Complement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
XOR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
OR

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
x

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
XOR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Complement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
OR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
inputs

</div>
<div class="column">
A B

</div>
<div class="column">
Control Signals cs2 cs1 cs0

ALU Output

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
For Section A2

</div>
</div>
<div class="layoutArea">
<div class="column">
Section A2

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
cin

</div>
</div>
</td>
<td></td>
<td></td>
<td colspan="6" rowspan="1">
<div class="layoutArea">
<div class="column">
Functions for

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
cs2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
cs1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
cs0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 6

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
x

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
OR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
XOR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Complement A

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Increment A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Increment A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Increment A

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
x

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
XOR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Complement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
OR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
inputs

</div>
<div class="column">
A B

</div>
<div class="column">
Control Signals cs2 cs1 cs0

ALU Output

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
For Section B1

</div>
</div>
<div class="layoutArea">
<div class="column">
Section B1

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
cin

</div>
</div>
</td>
<td colspan="6" rowspan="1">
<div class="layoutArea">
<div class="column">
Functions for

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
cs2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
cs1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
cs0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 6

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Increment A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Increment A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
x

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
OR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
XOR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Complement A

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transter A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Increment A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
x

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
XOR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Complement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
OR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
inputs

</div>
<div class="column">
A B

</div>
<div class="column">
Control Signals cs2 cs1 cs0

ALU Output

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
For Section B2

</div>
</div>
<div class="layoutArea">
<div class="column">
Section B2

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
cin

</div>
</div>
</td>
<td></td>
<td></td>
<td colspan="6" rowspan="1">
<div class="layoutArea">
<div class="column">
Functions for

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
cs2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
cs1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
cs0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Group 6

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Decrement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract with borrow

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Increment A

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Transfer A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Increment A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subtract

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Increment A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Add with carry

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
x

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Complement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
XOR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
OR

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
x

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
XOR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Complement A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
OR

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
AND

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
inputs

</div>
<div class="column">
A B

</div>
<div class="column">
Control Signals cs2 cs1 cs0

ALU Output

</div>
</div>
</div>
