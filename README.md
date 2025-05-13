# cs211-assignment-2-bit-manipulation-solved
**TO GET THIS SOLUTION VISIT:** [CS211 Assignment 2-Bit Manipulation Solved](https://www.ankitcodinghub.com/product/cs211-assignment-2-bit-manipulation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93351&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS211 Assignment 2-Bit Manipulation Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

This assignment is designed to give you a better understanding of bits and bit manipulation. Your task is to write 3 small C bit-related programs. Your programs must follow the input-output guidelines listed in each section, with no additional or missing output.

You can assume all your input files will be in proper format as described.

Bit Introduction

Because this assignment is focused on bits, to receive credit, all parts of this assignment must only use bit operations to complete the tasks of the program. You may not use arithmetic or logic equivalents to the bit tasks being asked for.

C provides six operators for bit manipulation:

</div>
</div>
<div class="layoutArea">
<div class="column">
~ complement &amp; bitwise AND

| bitwise inclusive OR ^ bitwise exclusive OR &lt;&lt; left shift

&gt;&gt; right shift

For example:

1 2 3 4

1 2

</div>
<div class="column">
All 0 bits are set to 1 and 1 bits are set to 0.

The bits in the result are set to 1 if the corresponding bits in the two operands are both 1.

The bits in the result are set to 1 if at least one of the correspond- ing bits in the two operands is 1.

The bits in the result are set to 1 if exactly one of the correspond- ing bits in the two operands is 1.

Shifts the bits of the first operand left by the number of bits specified by the second operand.

Shifts the bits of the first operand right by the number of bits specified by the second operand.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
unsigned short x = 5, y = 2, z; //in binary 5 is 101 and 2 is 10 z=x&amp;y; //result: 0

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
z = 5 | y; //result: 7 z = 5 ˆ 1; //result: 4

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
An example using shifting:

</div>
</div>
<div class="layoutArea">
<div class="column">
unsigned short x = 5; printf(”%u\n%u\n”, x &lt;&lt; 1, x &gt;&gt; 1);

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
First: Bit functions

You have to write a program that will read a number followed by a series of bit operations from a file and perform the given operations sequentially on the number. The operations are as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
For example:

</div>
</div>
<div class="layoutArea">
<div class="column">
set(x, n, v) comp(x, n) get(x, n)

</div>
<div class="column">
sets the nth bit of the number x to v

sets the value of the nth bit of x to its complement (1 if 0 and 0 otherwise) returns the value of the nth bit of the number x

</div>
</div>
<div class="layoutArea">
<div class="column">
The least significant bit (LSB) is considered to be index 0.

Input format: Your program will take the file name as input. The first line in the file provides the value of the number x to be manipulated. This number should be considered an unsigned short. The following lines will contain the operations to manipulate the number. To simplify parsing, the format of the opera- tions will always be the command name followed by 2 numbers, separated by tabs. For the set(x, n, v) command, the value of the second input number (v) will always be either 0 or 1. For the comp(x, n) and get(x, n) commands the value of the second input number will always be 0 and can be ignored. Note that the changes to x are cumulative, rather than each instruction operating independently on the original x.

Output format: Your output for comp and set commands will be the resulting value of the number x after each operation, each on a new line. For get commands, the output should be the requested bit’s value.

Example Execution:

For example, a sample input file “file1.txt” contains the following (except the annotation comments):

5 #x=5

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>get   0  0
comp  0  0
set   1  1
</pre>
</div>
<div class="column">
# get(x, 0), ignoring second value (0) # comp(x, 0), ignoring second value (0) #set(x,1,1)

</div>
</div>
<div class="layoutArea">
<div class="column">
The result of the sample run is:

<pre>$ ./first file1.txt
1
4
6
</pre>
Second: Bit Count functions (35 points)

In this part, you have to determine the parity of a number and the number of 1-bit pairs present in the number. Parity refers to whether a number contains an even or odd number of 1-bits. 1-bit pairs are defined by two adjacent 1’s without overlap with other pairs.

</div>
</div>
<div class="layoutArea">
<div class="column">
Number Binary sequence Parity Number of pairs 7 111 Odd 1

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre> 15          1111
367       101101111
</pre>
</div>
<div class="column">
Even 2 Odd 3

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Input format: This program takes a single number as an argument from the command line. This number should be considered as an unsigned short.

Output format: Your program should print either “Even-Parity” if the input has an even number of 1 bits and “Odd-Parity” otherwise, followed by a tab. Your program should then print the number of 1-bit pairs present in the number followed by a new line character.

Example Execution:

<pre>$ ./second 12
Even-Parity   1
</pre>
<pre>$ ./second 31
Odd-Parity    2
</pre>
Third: Bit Pattern function (30 points)

In this part, you have to determine whether a number’s bit representation is a palindrome. A palindrome is defined as a sequence that is the same both forwards and backwards.

We will be working with unsigned shorts which are 2 bytes or 16 bits. For example the number 384 has the binary sequence 0000000110000000 and is thus a palindrome while the sequence 0100100010111011 is not. Note that all values should be considered 16-bit, so while 5 is 101 in binary and looks like a palindrome, in 16 bits it’d be 0000000000000101, which is not.

You can and should use the same get(x, n) function that you created in part 1.

Input format: This program takes a single number as an argument from the command line. This number

should be considered as an unsigned short.

Output format: Your program should print either “Is-Palindrome” if the input is a palindrome and “Not-Palindrome” otherwise, followed by a new line character.

Example Execution:

Some sample runs and results are:

<pre>$ ./third 5
Not-Palindrome
</pre>
<pre>$ ./third 384
Is-Palindrome
</pre>
<pre>$ ./third 1001
Not-Palindrome
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Structure of your submission folder

All files must be included in the pa2 folder. The pa2 directory in your tar file must contain 3 subdirectories, one each for each of the parts. The name of the directories should be named first through third (in lower case). Each directory should contain a c source file, a header file (if you use it) and a Makefile. For example, the subdirectory first will contain, first.c, first.h (if you create one) and Makefile (the names are case sensitive).

pa2 first

<pre>        Makefile
        first.c
        first.h (if used)
</pre>
<pre>     second
        Makefile
</pre>
second.c

<pre>        second.h (if used)
     third
</pre>
<pre>        Makefile
        third.c
        third.h (if used)
</pre>
Submission

You have to submit the assignment using Sakai. Your submission should be a tar file named pa2.tar. To create this file, put everything that you are submitting into a directory (folder) named pa2. Then, cd into the directory containing pa2 (that is, pa2’s parent directory) and run the following command:

tar cvf pa2.tar pa2

To check that you have correctly created the tar file, you should copy it (pa2.tar) into an empty directory

and run the following command:

tar xvf pa2.tar

This should create a directory named pa2 in the (previously) empty directory.

The pa2 directory in your tar file must contain 3 subdirectories, one each for each of the parts. The name of the directories should be named first through third (in lower case). Each directory should contain a C source file, a header file (if necessary) and a make file. For example, the subdirectory first will contain, first.c, first.h and Makefile (the names are case sensitive).

AutoGrader

We provide the AutoGrader to test your assignment. AutoGrader is provided as autograder.tar. Executing the following command will create the autograder folder.

<pre>tar xvf autograder.tar
</pre>
There are two modes available for testing your assignment with the AutoGrader.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
First mode

Testing when you are writing code with a pa2 folder

(1) Lets say you have a pa2 folder with the directory structure as described in the assignment. (2) Copy the folder to the directory of the autograder

(3) Run the autograder with the following command

<pre>python auto_grader.py
</pre>
It will run your programs and print your scores.

Second mode

This mode is to test your final submission (i.e, pa2.tar) (1) Copy pa2.tar to the auto grader directory

(2) Run the auto grader with pa2.tar as the argument. The command line is

<pre>python auto_grader.py pa2.tar
</pre>
Scoring

The autograder will print out information about the compilation and the testing process. At the end, if your assignment is completely correct, the score will something similar to what is given below.

<pre>You scored
17.5  in  second
15.0  in  third
17.5  in  first
Your TOTAL SCORE =  50.0 /50
Your assignment will be graded for another 50 points with test cases not given to you
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
