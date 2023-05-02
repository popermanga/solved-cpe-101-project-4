Download Link: https://assignmentchef.com/product/solved-cpe-101-project-4
<br>
Word Puzzle

<strong>Objectives: </strong>

<ul>

 <li>Practice on lists and strings.</li>

 <li>Opportunity to test your understanding of all of the different concepts:

  <ul>

   <li>Conditional logic, loops,</li>

   <li>lists, and functions</li>

  </ul></li>

</ul>




<strong>Required File Header:</strong>

All students are required to have the following header comment at the top of their source files. Note that the stuff to the right of the colon in red is information for an imaginary example student. (Please put YOUR appropriate information. Also, your header comment is not expected to have red text.) All program files require this header.

# Project 4 – Word Puzzle

# Name: Members Name

# Instructor: S. Einakian  # Section:




<strong>Resources: </strong>

<ul>

 <li>Your instructor, via office hours, email, Piazza, etc.</li>

 <li>Free tutoring Sunday-Thursday, 7-9 PM, 14-302          Your TA</li>

</ul>

<h1>Program Description</h1>

In this project, you will implement a program, which locates words in common word search puzzles (all puzzles are 10×10). A sample puzzle is shown below:

WAQHGTTWZE <strong>C</strong>BNSZQQELS

<strong>A</strong>ZXWKWIIML <strong>L</strong>DWLFXX<strong>S</strong>AV

<strong>P</strong>ONDTMV<strong>U</strong>XN

<strong>O</strong>EDSDYQ<strong>P</strong>OB

<strong>L</strong>GQCKGM<strong>M</strong>IT

<strong>Y</strong>C<strong>SLO</strong>AC<strong>A</strong>ZM

XVDMGSX<strong>C</strong>YZ

UUI<strong>UNIX</strong>FNU

The above puzzle contains the words (shown in bold): UNIX, CALPOLY, SLO, and CAMPUS. Words can appear in the puzzle running <strong>up, down, forward, or backward</strong>. You do not need to check diagonals.

<strong>Input and Output  </strong>




<strong>Input: </strong>

<ul>

 <li>Your program should read in a <strong>100 character long string </strong>from user via standard keyboard input.</li>

 <li>These strings are available (at the first line) in the input files called: puzzleAndWords0, puzzleAndWords1, puzzleAndWords2</li>

 <li>Using this user input, you should create a 10×10 puzzle which you can work with, in order to find the words in the puzzle.</li>

 <li>Your program should also at the same time read in <strong>words </strong>from user via standard keyboard input.</li>

 <li>These words are available (at the second line) in the input files called: puzzleAndWords0, puzzleAndWords1, puzzleAndWords2)</li>

 <li>These are the words that are to be found in the puzzle by your program.</li>

</ul>







<strong>Output: </strong>

<ul>

 <li>Your program should be tested as below:</li>

</ul>




<strong>Python3 wordFinder.py &lt; puzzleAndWords &gt; output0 </strong>o You may review the following files to know what the “expected output” should look like of your program:




output0, output1, output2




<ul>

 <li>Remember that the requirement for your project is to print the output to screen, not to a file.</li>

 <li>Output files mentioned above are ONLY provided to you for comparison purposes. So, you can compare your own output (<strong>prints to the screen</strong>) with the “expected output”.</li>

 <li>This comparison will help you verify whether or not your program is working as expected.</li>

 <li>You may access the <strong>input </strong>as well as <strong>output </strong>files (that are mentioned in steps above) via command given below or through PolyLearn:</li>

 <li>While being present in the location where you would like to copy, run the following command:</li>

</ul>




<strong>Copy the zip file from PolyLearn to your working directory of Project4.</strong>

<strong> </strong>

<h2>unzip Project4.zip</h2>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>




<strong>Sample output of program (print to the screen, not to a file) is shown as below: </strong>

Puzzle:




WAQHGTTWEE

CBMIVQQELS

AZXWKWIIIL

LDWLFXPIPV

PONDTMVAMN

OEDSOYQGOB

LGQCKGMMCT

YCSLOACUZM

XVDMGSXCYZ

UUIUNIXFNU




UNIX: (FORWARD) row: 9 column: 3

CALPOLY: (DOWN) row: 1 column: 0

GCC: word not found

SLO: (FORWARD) row: 7 column: 2

COMPILE: (UP) row: 6 column: 8

VIM: (BACKWARD) row: 1 column: 4

TEST: word not found




<h2>Submission</h2>

<ul>

 <li><strong>Use the same name for your files</strong></li>

 <li>You must have total of three files in your submission:

  <ol>

   <li><strong>py </strong>à This file must include the actual functions definitions/implementation.</li>

  </ol></li>

</ul>




<ol start="2">

 <li><strong>py </strong>à This file must include at least two unit tests for each function, which contain the assert statements testing the functions developed in funcs.py.</li>

</ol>




<ol start="3">

 <li><strong>py </strong>à This file must include the main function, which calls all the functions developed within funcs.py.</li>

</ol>




<ol start="4">

 <li>txt à This file must explain responsibilities of each member</li>

</ol>




<strong>NOTE: </strong>

<strong>Some of the suggested functions are given in a file funcs.py. You can create as many functions as you need. You can even ignore the suggested functions. But, you are not allow to write the whole project in One Function! </strong>

<strong> </strong>