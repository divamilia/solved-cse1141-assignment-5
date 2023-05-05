Download Link: https://assignmentchef.com/product/solved-cse1141-assignment-5
<br>
<strong>Q1. </strong>In this question, you will write a program that grades multiple-choice tests. Assume that there are 40 questions, and the answer key will be given by the user. Your program will take the answers of each student as a single string, and it will grade the exam based on the given key. Your program should print the total number of correct and incorrect answers separately for each student.

There are several constraints regarding the program:

<ol>

 <li>There might be 4 different cases for answers (“A”, “B”, “C”, “D”). ii.  A student can leave a question blank, in which case his/her answer will be given with a dash (“-“).</li>

</ol>

<ul>

 <li>Your program should also provide detailed information about the student’s score.</li>

</ul>

Suppose that there are four different types of subjects (or chapters).

These are represented with S1, S2, S3, and S4. The question numbers for each subject are the followings:

<ul>

 <li>The question numbers for subject 1 (S1) are: 1, 5, 9,  13, …. 37.  o The question numbers for subject 2 (S2) are: 2, 6, 10, 14, …. 38. o The question numbers for subject 3 (S3) are: 3, 7, 11, 15, …. 39.</li>

 <li>The question numbers for subject 4 (S4) are: 4, 8, 12, 16, …. 40.</li>

</ul>




<ol>

 <li>Your program should display the percentage of success of each student in each subject. o Example: Suppose that student Leyla has the following sub-totals:

  <ul>

   <li>She has 8 correct and 2 incorrect answers for S1.</li>

   <li>She has 7 correct and 3 incorrect answers for S2.</li>

   <li>She has 5 correct and 5 incorrect answers for S3.</li>

   <li>She has 2 correct and 8 incorrect answers for S4.</li>

  </ul></li>

</ol>

o Then, your program should display the following output:

Leyla has 22 correct and 18 incorrect answers in total.

Her percentage of success is:

S1        S2        S3        S4

—       —       —       —

80%       70%       50%       20%

<ul>

 <li>Your program should take the answer key first, then it should ask the student’s name and his/her answers. Then it should print the output for that student. This process should continue repeatedly. If the user enters 0, that means the program ends. It should be noted that the answer key will be given once, for each execution.</li>

</ul>




<ul>

 <li>Error Checking:</li>

 <li>If the answers key or the students’ answers have less than 40 entries, then give an appropriate error message.</li>

</ul>

Illegal Input!

Here are some execution examples: Execution 1:

Hello Teacher!

Please enter the answer key:

<h1>AABBAACCCCBABADDAAAADDDDAACCAAAABBBCCDCC</h1>




Please enter the name of student: Leyla Please enter the answers of Leyla:

<h1>ABBBACCDCDA-BAACAAC-DDBAAABDCAABBBBA-DCC</h1>







Leyla has 22 correct and 18 incorrect answers in total.

The percentage of success is:

S1        S2        S3        S4

—       —       —       — 80%       70%       50%       20%




Please enter the name of student: Ali Please enter the answers of Ali:

<h1>DBAB-ACCBABADCDDBBAADDDD-A-CCDAAABCCCDBC</h1>







Ali has 23 correct and 17 incorrect answers in total.

The percentage of success is:

S1        S2        S3        S4

—       —       —       —

20%       50%       60%       100%







Please enter the name of student: 0

Program ends. Bye &#x1f642;

Execution 2:

Hello Teacher!

Please enter the answer key:

<h1>CCBBAACCBADABBCCBDDAABCDDCBACBADBCCADDBD</h1>




Please enter the name of student: Ahmet Please enter the answers of Ahmet:

AB—ACC-CDA-BAA- Illegal Input!




Please enter the name of student: Ahmet Please enter the answers of Ahmet:

<h1>AB—ACCCDA-BAA-AAC-DDB-AAB-CAA-BBB–BBD</h1>




Ahmet has 10 correct and 30 incorrect answers in total.

The percentage of success is:




S1        S2        S3        S4

—       —       —       — 30%       10%       40%       20%




Please enter the name of student: 0

Program ends. Bye &#x1f642;




<strong> </strong>

<strong>Q2. </strong>In this question, you will write a program that tests whether a two-dimensional list has seven-length string “CSE1141”, either horizontally, vertically, or diagonally (forwardà or backwardß and up  or down  ). Your program should prompt the user to enter the number of rows and columns of the list and then you will generate a two-dimensional list with random letters between ‘A’ to ‘Z’ and ‘0’ to ‘9’. Your program then displays <strong>True</strong> if the list contains “CSE1141”, either horizontally, vertically, or diagonally (forwardà or backwardß and up  or down   ). Otherwise, it will display False. Here are some examples of the true cases:




<table width="394">

 <tbody>

  <tr>

   <td width="266">


    <table width="249">

     <tbody>

      <tr>

       <td width="109">F 4 M G I G P5 5 1 C V 0 1Z G S K U T 9 6 5 6 1 1 9 1 K 3 R 1 V H 7C S E 1 1 4 1 5 7 0 3 0 3 8</td>

       <td width="31">       </td>

       <td width="109">C 4 M G I G PS 5 1 C V 0 1E X D 0 R 7 81 5 6 1 1 9 11 3 R 1 V H 74 S E 1 1 4 11 1 O P T R E</td>

      </tr>

     </tbody>

    </table></td>

   <td width="128">


    <table width="112">

     <tbody>

      <tr>

       <td width="112">C 4 M G I G P S S 1 C V 0 1E X E 0 R 7 81 5 6 1 1 9 11 3 R 1 1 H 74 S E 1 1 4 11 1 O P T R 1</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>







It should be noted that you do not need to highlight the true case with yellow.  We just add them to read it easily. Please do not forget to leave a space (‘ ’) after printing each item in the list.

Here are some execution examples: Execution 1:

Please enter the number of rows: 10

Please enter the number of columns: 15




S J A 5 P 0 C 2 G Y W 0 P H S  7 7 E X 3 4 5 W 1 M O 6 3 4 2  6 1 7 6 6 C S E 1 1 4 1 2 U Y  7 G 1 W 9 E V 7 K 4 P 0 A Y O  X 5 Z 9 H 3 V 0 L 3 S R 1 6 J  E Z 2 2 6 4 O E P L X P Z 7 0  5 5 5 G 0 N 6 9 2 P F 9 Y H Y  H H S E T H 1 J 8 7 8 P 9 2 8  2 L K C 1 M 9 G T X U 2 W 0 8  Z T B U 8 5 7 S 7 N 9 S X P O




<h2>TRUE</h2>




Execution 2:

Please enter the number of rows: 7

Please enter the number of columns: 10




1 6 3 3 2 2 X 9 I 3  9 0 Z W Y 3 0 B Z K  3 6 6 3 4 B 0 8 L D  3 T V 2 5 6 1 L 2 0  0 O Z P W X Q W Y L  P K V 7 O 2 3 6 2 8  F 2 L L 7 O 8 M S X




<h2>FALSE</h2>







Execution 3:

Please enter the number of rows: 9

Please enter the number of columns: 8




F 6 5 V 9 Q 1 4  P G 0 E 1 3 O 3  N 0 7 I 4 2 7 7  6 3 7 Q 1 Q 9 8  0 6 5 3 1 5 2 8  Z 0 P 8 E H I 8  Z 4 6 P S J C E  O 1 U 3 C 8 B L  3 Y C L L H 1 F




<h2>TRUE</h2>







Execution 4:

Please enter the number of rows: 14

Please enter the number of columns: 14




8 O A D 0 7 4 7 9 U L 2 1 Z  0 A K 2 J G 6 9 4 1 7 I 1 2  2 F 3 8 G 7 M R 8 T 3 9 H 0  Y 6 3 N I 7 I 9 F J 8 S I R  J W 8 W F 6 H E H O U Q 9 8  1 E T 1 0 6 U 2 0 7 U 4 4 2  9 2 C 5 N 6 X 7 Z 0 3 L U V  Z 5 O 3 D 4 1 B 3 8 S 6 B C

M 3 U F 3 4 7 S 4 F S R M L  2 1 9 7 1 6 M M 3 0 1 Y C 2  8 7 8 1 7 E 9 3 L F 7 2 Z J  1 6 E Y S D 8 R 5 X 9 0 F N  6 S 6 X 6 8 2 B 9 9 0 O 3 7  C 8 K 7 0 0 C R 9 5 V 2 K 9




<h2>TRUE</h2>