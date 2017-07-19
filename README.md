# An-Army-Helicopter

<h3>Problem statement</h3>
<p>The host government has promised that in addition to the security guards in each match, there will be a platoon of elite commandos that will be deployed for extra protection in each stadium for each match. In order to move quickly between cities and stadiums there will be a dedicated army helicopter on permanent stand by.

The army helicopter has to land in city (rectangular area) which contains several towers (mobile communication towers). For the safe landing of the helicopter, the landing space must not contain any tower in the landing space. A helicopter needs a square shaped landing area which has the side length greater than or equal to the helicopter length. Given a description of the tower positions of the city, you have to tell the largest helicopter that can land in the city.</p>


<h4>Input Format: </h4>
You will be given a function which contains a string array of N length, each string contains M symbols (either 'x' or 'o'). x represents a tower and 'o' represents empty space.

<h4>Output Format: </h4>
Your function will return the Length of the largest helicopter that can land in the city, else -1 if input is invalid.


<h4>Sample Test Case 1:</h4>
<h5>Sample Input:</h5>
<code>
  5 
  x#o#o#o#x#o 
  x#o#o#o#x#x 
  x#o#o#o#x#x 
  x#o#x#o#o#x 
  x#o#x#o#o#x
</code>

<h5>Sample Output : </h5>
<code>3</code>

<h4>Sample Test Case 2:</h4>
<h5>Sample Input:</h5>
<code>
  5 
  x#o#o#o#x#o 
  x#o#x#o#x#x 
  x#o#o#o#x#x 
  x#o#x#o#o#x 
  x#o#x#o#o#x
</code>

<h5>Sample Output : </h5>
<code>-1</code>
