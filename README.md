Download Link: https://assignmentchef.com/product/solved-csc110-fundamentals-of-programming-i-assignment-4-more-methods-while-loops-random
<br>
<strong>Learning outcomes </strong>

When you have completed this assignment, you should understand:

<ul>

 <li>How to pass <em>parameters</em> and <em>return</em> values using static</li>

 <li>How to use while</li>

 <li>How to use the Random class and its nextInt</li>

 <li>How to logically decompose a program into smaller parts.  How to <em>indent </em>and<em> document</em> a Java program.</li>

</ul>




Write the code for a Java program named Pig.java. The instructions on how to play Pig, as well as the specification for the methods required in your program can be found in the Pig.html file linked <a href="https://connex.csc.uvic.ca/access/content/group/c695ec2f-7536-40a4-8ddc-eec4c5c20d41/Assignment%20Resources/Assignment4/Pig.html">here</a><a href="https://connex.csc.uvic.ca/access/content/group/c695ec2f-7536-40a4-8ddc-eec4c5c20d41/Assignment%20Resources/Assignment4/Pig.html">.</a> Read the specification document carefully, as it describes what each method should do.  Each of the methods <strong>must</strong> be present in the Pig class, with the headers (parameters and return values) exactly as described. (Note that for the Scanner and Random parameters, you can omit the java.util. prefix by writing import statements at the top of the source code.)

For this assignment, <em>testing </em>is crucial.  All tests for the methods are implemented in the main method.  During and after the writing of each method, call the current method from main, setting up enough tests to satisfy yourself that the method works.  See <strong>Appendix A</strong> for examples of good testing output.  As you progress, comment out the previous tests (don’t delete them; we’ll be checking), and carry on with the next test.

<strong>             </strong>

<strong>Recommended steps to follow in order </strong>

<ol>

 <li>The diceRoll method is a nice place to start. Focus on the simple responsibility this method has, without thinking about the rest of the game.  It simply rolls a die and returns the value that of the roll.</li>

 <li>The playerTurn and the computerTurn methods are similar and yet still different. One requires some user interaction and the other does not.  Choose whichever one you would like to do first.  Make sure you finish and test them both before moving to the next step.</li>

 <li>The final method puts the whole game together and should be implemented only after the previous three are tested successfully. When you test this method in main and it produces output that is similar to the final output in <strong>Appendix A</strong>, you can play Pig!</li>

</ol>

<strong> </strong>

<strong>Marking  </strong>

Your mark will be based on the following criteria:

<ul>

 <li>Your code <em>must compile and run</em>. It must prompt the user, generate Random numbers, and produce the expected output as demonstrated in <strong>Appendix A.</strong></li>

 <li>Your code must conform to all the requirements mentioned in the <a href="https://connex.csc.uvic.ca/access/content/group/c695ec2f-7536-40a4-8ddc-eec4c5c20d41/Assignment%20Resources/Assignment4/Pig.html">specification document</a><a href="https://connex.csc.uvic.ca/access/content/group/c695ec2f-7536-40a4-8ddc-eec4c5c20d41/Assignment%20Resources/Assignment4/Pig.html">.</a></li>

 <li>The main method must show all of your testing code. It may be commented out once you have tested parts of it.  The final call to <em>gameLoop()</em> should not be commented out.</li>

 <li>Your code must follow the guidelines outlined in Style_Guidelines.pdf, found through the Lectures &amp; Stuff link in the Lab Resources folder on conneX. You may note that the specifications provide some very nice comments you are welcome to borrow.</li>

</ul>

<strong><u>Appendix A – Testing your code</u></strong>

As you work through a solution, it is recommended that you save, compile and test your code after every line or two of code that you write. This can be something as easy as printing out the value of a variable, or calling a method to print out the value returned. It is important to do this to confirm a component of your code works correctly, so you can be confident using that component throughout your code later.




<strong>Testing the </strong>diceRoll<strong> method: </strong>

One way to do this is to create a for-loop that loops 20 times. Inside the for-loop, call the diceRoll method and assign the value it returns to an integer variable roll. Then, print out the value of roll.










playerTurn <strong>method: (user input underlined in red): </strong>










<strong><em>gameLoop</em></strong><strong> method: (with user input in red font) </strong>




C:UsersAnthony EsteyDocumentscsc110Assignments&gt;java Pig




Welcome to the game of Pig. Beginning the game…




<h1>You rolled a 5. Your score so far is 5</h1>

Do you want to roll again? (yes or no)

<h1><strong>yes </strong></h1>

<h1>You rolled a 2. Your score so far is 7</h1>

Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 6. Your score so far is 13 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 4. Your score so far is 17 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 5. Your score so far is 22

Do you want to roll again? (yes or no)

<strong>yes </strong>

You rolled a 5. Your score so far is 27 Do you want to roll again? (yes or no) <strong>yes </strong>

<table width="144">

 <tbody>

  <tr>

   <td width="144">The same process is repeated until someone reaches 100 points: a)  <em>playerTurn</em>b)  <em>computerTurn</em>c)   Print scores</td>

  </tr>

 </tbody>

</table>

You rolled a 5. Your score so far is 32

Do you want to roll again? (yes or no)     <strong>no </strong>

Ending your turn with a score of 32.




The computer rolled a 4. Its total score this turn is 4.

The computer rolled a 5. Its total score this turn is 9.

The computer rolled a 3. Its total score this turn is 12.

The computer rolled a 1, ending its turn with a score of 0 this round




The scores at the end of the current round are:

Player: 32      Computer: 0







You rolled a 5. Your score so far is 5 Do you want to roll again? (yes or no) <strong>yes </strong>

Uh oh, you rolled a 1!

Your turn is over and you get 0 points this round




The computer rolled a 2. Its total score this turn is 2.

The computer rolled a 5. Its total score this turn is 7.

The computer rolled a 5. Its total score this turn is 12.

The computer rolled a 2. Its total score this turn is 14.

Ending computer’s turn with a score of 14.







The scores at the end of the current round are:

Player: 32      Computer: 14







You rolled a 2. Your score so far is 2

Do you want to roll again? (yes or no)

<strong>yes </strong>

You rolled a 5. Your score so far is 7 Do you want to roll again? (yes or no) <strong>yes </strong>

Uh oh, you rolled a 1!

Your turn is over and you get 0 points this round




The computer rolled a 1, ending its turn with a score of 0 this round




The scores at the end of the current round are:

Player: 32      Computer: 14







You rolled a 5. Your score so far is 5 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 6. Your score so far is 11 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 2. Your score so far is 13 Do you want to roll again? (yes or no) <strong>no </strong>

Ending your turn with a score of 13.




The computer rolled a 4. Its total score this turn is 4.

The computer rolled a 3. Its total score this turn is 7.

The computer rolled a 5. Its total score this turn is 12.

The computer rolled a 2. Its total score this turn is 14.

Ending computer’s turn with a score of 14.




The scores at the end of the current round are:

Player: 45      Computer: 28







You rolled a 5. Your score so far is 5 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 3. Your score so far is 8

Do you want to roll again? (yes or no) <strong>yes </strong>

Uh oh, you rolled a 1!

Your turn is over and you get 0 points this round




The computer rolled a 2. Its total score this turn is 2.

The computer rolled a 3. Its total score this turn is 5.

The computer rolled a 1, ending its turn with a score of 0 this round




The scores at the end of the current round are:

Player: 45      Computer: 28







You rolled a 4. Your score so far is 4 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 6. Your score so far is 10 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 3. Your score so far is 13 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 5. Your score so far is 18 Do you want to roll again? (yes or no) <strong>no </strong>

Ending your turn with a score of 18.




The computer rolled a 4. Its total score this turn is 4.

The computer rolled a 5. Its total score this turn is 9.

The computer rolled a 2. Its total score this turn is 11.

The computer rolled a 5. Its total score this turn is 16.

Ending computer’s turn with a score of 16.




The scores at the end of the current round are:

Player: 63      Computer: 44







You rolled a 5. Your score so far is 5 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 2. Your score so far is 7 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 2. Your score so far is 9

Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 3. Your score so far is 12 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 4. Your score so far is 16 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 4. Your score so far is 20 Do you want to roll again? (yes or no) <strong>no </strong>

Ending your turn with a score of 20.




The computer rolled a 1, ending its turn with a score of 0 this round The scores at the end of the current round are:

Player: 83      Computer: 44







You rolled a 2. Your score so far is 2 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 2. Your score so far is 4 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 4. Your score so far is 8 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 4. Your score so far is 12 Do you want to roll again? (yes or no) <strong>yes </strong>

You rolled a 6. Your score so far is 18 Do you want to roll again? (yes or no) <strong>no </strong>

Ending your turn with a score of 18.




The computer rolled a 5. Its total score this turn is 5.

The computer rolled a 6. Its total score this turn is 11.

The computer rolled a 2. Its total score this turn is 13.

The computer rolled a 1, ending its turn with a score of 0 this round




The scores at the end of the current round are:

Player: 101     Computer: 44





