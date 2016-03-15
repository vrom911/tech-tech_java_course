<h1>Tech Tech Xanim Java Web Development Course</h1>
This is directory with Tasks from the course. There will be description for every module.
<h2>#1 CalcMath</h2>
<p>
  <b>The Parser for Math Expressions</b>
  <hr>
  <br>
  To run you need to input in the console <code>java CalcMath your_expression</code>
  Ex.: <code>java CalcMath 2 + 2 * 2</code>
  The output will be the result of the operations: <code> 2 + 2 * 2 = 6 </code> if data is corect and <code>Wrong input</code> otherwise.<br>
  <ul> Possible operations
    <li>+ Addition</li>
    <li>- subtraction</li>
    <li>* Multiplication</li>
    <li>/ Division</li>
    <li>() Brackets are also possible </li>
    <li> Unary Operations</li>
  </ul>
  
  Some other features:<br>
  - Possibility to write decimals starting with "." , ex.: <code>.125</code><br>
  - Possibility not to add "*" sign before brackets
  
</p>
<h2>#2 Array Tasks </h2>
<p>
  <b>Finding Max Min and other operations with Arrays</b>
  <hr>
  <br>
  <ul>In main function User need to input number of operation you'd like to run.<br>
    <li>#1  Finds max and min of random array. Input - array's length.</li>
    <li>#2  Finds max and min in each row of n-dimention array.</li>
    <li>#3  #2 and change max and min of each row between each other.</li>
    <li>#4 Exit. Stops running.</li>
  </ul>
<br>
Additional functions written :<br>
  * <code>round(double num, int scale)</code> - returns double rounded by scale numbers after the dot.<br>
  * <code>maxMinArray(Array)</code> - returns array of { index_of_max , index_of_min } of the given simple array<br>
</p>
<h2>#3 Matrix Practice </h2>
<p>
  <b>Multiplication of two Matrix</b>
  <hr>
  <br>
  Multiplication of Matrix of any dimentions(possible for operations)<br>
 <b>Input:</b> 4 integers: dim of 1st matrix &dim of 2nd matrix<br>
 <b>Output:</b> Matrix - result of computation.
<br>
Additional functions written :<br>
  * <code>round(double num, int scale)</code> - returns double rounded by scale numbers after the dot.<br>
  * <code>makeArray(int num1, int num2)</code> - returns random array of given dimentions<br>
  * <code>multipl(double[][] a, double[][] b)</code> - returns array - result of multiplication of two args given<br>
</p>
<h2>#4 Links Parser </h2>
<p>
  <b>Parsing all links of the given web-page</b>
  <hr>
  <br>
  
<br>

</p>

<h2>#5 Zoo Project </h2>
<p>
  <b>A simple simulation of a zoo. This zoo will have enclosures of
animals that are looked after by zookeepers. The animals will eat food, produce waste and have special
treats to keep them healthy.</b>
  <hr>
	For more info about the task, please, visit <a href = ""> this link</a>.
  <br>
  <b>Input:</b> name of the file with basic data in the proper format<br>
<em>Example</em>
<code> 
	zoo:<br>
	steak:50<br>
	enclosure:50<br>
	hay:20<br>
	celery:10<br>
	lion:M,12,5<br>
	bear:F,10,4<br>
	playZookeeper:<br>
</code>
 <b>Output:</b> Description of all activities at each Enclosure of each Zoo made by <strong> Animal or Zookeper</strong>. Continue till there is not empty (has animals) operatable Enclosure.
<br>
<b>NOTE:</b> Comments can be helpful for understanding every class/method/variable definition<br>

</p>

<i>to be continued..</i>
