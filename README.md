<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body>
   <h3> Javascript-Roadmap-With-Assignment</h3>

   <details>
    <summary><a href="https://youtu.be/OipNpUBpUPs?si=TDBmOjqeo2kYBiOB" target="_blank">What is programming & Javascript</a></summary>
    <br> 
      Programming is the process of writing instructions or code that tells a computer how to perform specific tasks. These instructions are written in programming languages, which allow humans to communicate with computers. The main goal of programming is to solve problems or automate tasks by creating software, applications, websites, or systems
    <br><br>  
  </details>
   
<details>
  <summary>Practice questions using only console.log()</summary>

  Practice questions using only console.log() to draw shapes, patterns, and other creative outputs in the console.

  <ol>
    <li>Use console.log() to draw a 5x5 square of * symbols.</li>
    <li>Use console.log() to draw a right-angled triangle made of *</li>
    <li>Use console.log() to draw an inverted triangle</li>
    <li>Use console.log() to draw a diamond shape</li>
    <li>Use console.log() to draw a hollow right-angled triangle</li>
    <li>Use console.log() to draw a hollow right-angled triangle</li>
    <li>Use console.log() to create a zigzag pattern.</li>
 </ol>
 
</details>

<details>
  <summary>What is Data & Data Types</summary>
<h5>What is data ?</h5>
In programming, data refers to any information that can be processed, stored, or transmitted by a computer. It is the core of what computers operate on and manipulate. Data can come in various forms, such as numbers, text, images, audio, and more. The way data is represented and stored depends on its data type.
<h5>1. Primitive Data Types</h5>
<ol>
    <li>String</li>
    <li>Number</li>
    <li>Bool</li>
    <li>Undefined</li>
    <li>Null</li>
    <li>Symbol</li>
    <li>BigInt</li>
 </ol>

<h5>2. Non-Primitive Data Type</h5>
<ol>
    <li>Object</li>
    <li>Array</li>
    <li>Function</li>
    <li>Date</li>
    <li>RegExp</li>
    <li>Map</li>
    <li>Map</li>
 </ol>
</details>

<details>
  <summary>Number Data Type Practice Question</summary>

- Write Program to Add Two Integers and store their sum in the third variable.
- Write Program to Multiply two decimal Point Numbers. 
- Write Program to perform all arithmetic operations.
- Write Program to Swap Values of Two Variables 
- Write Program to Swap Values of Three variables like that.
  - Input : ( x = 3 , y = 4 , z = 5)
  - output : (x = 4 , y = 5 , z = 3)
- Write Program to convert feet to meter and meter into KM.
- Write Program to convert celcius to farenheit. formula: (°C × 9/5) + 35
- Write Program to convert farenheit to celcius. formula: (°F − 32) × 5/9 
- Write Program to Calculate Area of Circle. formula A=πr2
- Write Program to Calculate Area of Square. formula A=a2
- Write Program to Calculate Area of Rectangle. A=wl
- Write Program to convert days to years and weeks
</details>


<details>
  <summary>Arthematic operator</summary>

<table border="1" cellpadding="5">
  <thead>
    <tr>
      <th>Operator</th>
      <th>Description</th>
      <th>Example</th>
      <th>Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>+</td>
      <td>Addition</td>
      <td>5 + 2</td>
      <td>7</td>
    </tr>
    <tr>
      <td>-</td>
      <td>Subtraction</td>
      <td>5 - 2</td>
      <td>3</td>
    </tr>
    <tr>
      <td>*</td>
      <td>Multiplication</td>
      <td>5 * 2</td>
      <td>10</td>
    </tr>
    <tr>
      <td>/</td>
      <td>Division</td>
      <td>5 / 2</td>
      <td>2.5</td>
    </tr>
    <tr>
      <td>%</td>
      <td>Modulus (Remainder)</td>
      <td>5 % 2</td>
      <td>1</td>
    </tr>
    <tr>
      <td>++</td>
      <td>Increment</td>
      <td>let x = 5; x++;</td>
      <td>6</td>
    </tr>
    <tr>
      <td>--</td>
      <td>Decrement</td>
      <td>let x = 5; x--;</td>
      <td>4</td>
    </tr>
  </tbody>
</table>

</details>


<details>
  <summary>Bool Relational & Equality Operator </summary>
  
<table>
        <thead>
            <tr>
                <th>Operator</th>
                <th>Type</th>
                <th>Description</th>
                <th>Example</th>
                <th>Result</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>&lt;</td>
                <td>Relational</td>
                <td>Less than</td>
                <td>5 &lt; 10</td>
                <td>true</td>
            </tr>
            <tr>
                <td>&gt;</td>
                <td>Relational</td>
                <td>Greater than</td>
                <td>10 &gt; 5</td>
                <td>true</td>
            </tr>
            <tr>
                <td>&lt;=</td>
                <td>Relational</td>
                <td>Less than or equal to</td>
                <td>5 &lt;= 5</td>
                <td>true</td>
            </tr>
            <tr>
                <td>&gt;=</td>
                <td>Relational</td>
                <td>Greater than or equal to</td>
                <td>10 &gt;= 10</td>
                <td>true</td>
            </tr>
            <tr>
                <td>==</td>
                <td>Equality</td>
                <td>Equal to (compares values, ignores type)</td>
                <td>5 == "5"</td>
                <td>true</td>
            </tr>
            <tr>
                <td>===</td>
                <td>Equality</td>
                <td>Strict equal to (compares values and type)</td>
                <td>5 === "5"</td>
                <td>false</td>
            </tr>
            <tr>
                <td>!=</td>
                <td>Equality</td>
                <td>Not equal to (compares values, ignores type)</td>
                <td>5 != "6"</td>
                <td>true</td>
            </tr>
            <tr>
                <td>!==</td>
                <td>Equality</td>
                <td>Strict not equal to (compares values & type)</td>
                <td>5 !== "5"</td>
                <td>true</td>
            </tr>
        </tbody>
    </table>
</details>


<details>
  <summary>if else if & else statement Practice</summary>
  
  Practice questions using only if, else if and else statement based on the our prevous learning.
  
1. Grade Calculator
- Problem: Write a program that takes a student's score as input and assigns a letter grade based on the score:
- A: 90-100
- B: 80-89
- C: 70-79
- D: 60-69
- F: Below 60
  
2. Traffic Light Simulation
- Practice: Use conditions to check the color of the traffic light.
- Problem: Simulate a traffic light system. The program should display:
- "Go" if the light is green,
- "Slow down" if the light is yellow,
- "Stop" if the light is red.

3. Age-Based Ticket Pricing
- Problem: Create a program that calculates ticket prices for a movie based on age:
- Children (under 12) get a 50% discount,
- Seniors (60+) get a 30% discount,
- Regular price for everyone else.
- Practice: Use if, else if, and else to determine the ticket price based on the user's age.

4. Shopping Discount Calculator
- Problem: Create a program that calculates a discount based on the total purchase amount:
- No discount if the purchase is less than $50,
- 10% discount if the purchase is between $50 and $100,
- 20% discount if the purchase is more than $100.
- Practice: Use conditional statements to calculate the discount.

5. Shipping Cost Calculator
- Problem: Create a program to calculate shipping costs based on the weight of a package:
- Free shipping for packages weighing less than 1kg,
- $5 for packages between 1kg and 5kg,
- $10 for packages heavier than 5kg.
- Practice: Use conditional statements to calculate shipping cost.

6. Restaurant Tip Calculator
- Problem: Write a program that calculates the tip based on service quality:
- "Excellent" service: 20% tip,
- "Good" service: 15% tip,
- "Average" service: 10% tip,
- "Poor" service: 5% tip.
- Practice: Use if, else if, and else to calculate the tip percentage.

7. Simple ATM Withdrawal
- Problem: Write a program that simulates a simple ATM withdrawal system. The program should:
- Deny the transaction if the requested withdrawal is more than the account balance,
- Allow the transaction if the balance is sufficient.
- Display the remaining balance after withdrawal.
- Practice: Use if, else if, and else to handle different cases of balance and withdrawal amounts.

</details>

<details>
    <summary>What is Loop</summary>

    <p>Loops can execute a block of code a number of times.</p>

<table border="1" cellpadding="5" >
    <thead>
      <tr>
        <th>Value of i</th>
        <th>Condition (i &lt; 3)</th>
        <th>Output (console.log(i))</th>
        <th>Update i (i++)</th>
      </tr>
    </thead>
    <tbody>
      <!-- 1st iteration -->
      <tr>
        <td>i = 0</td>
        <td>0 &lt; 3 (true)</td>
        <td>0</td>
        <td>i++ → i = 1</td>
      </tr>
      <!-- 2nd iteration -->
      <tr>
        <td>i = 1</td>
        <td>1 &lt; 3 (true)</td>
        <td>1</td>
        <td>i++ → i = 2</td>
      </tr>
      <!-- 3rd iteration -->
      <tr>
        <td>i = 2</td>
        <td>2 &lt; 3 (true)</td>
        <td>2</td>
        <td>i++ → i = 3</td>
      </tr>
      <!-- Loop ends -->
      <tr>
        <td>i = 3</td>
        <td>3 &lt; 3 (false)</td>
        <td>--</td>
        <td>Loop stops</td>
      </tr>
    </tbody>
</table>    

</details>

<details>
  <summary><a href="https://youtu.be/OipNpUBpUPs?si=TDBmOjqeo2kYBiOB" target="_blank">loop practice Question</a></summary>

  <ol>
    <li>Write a program using for loop that prints numbers from 1 to 10.</li>
    <li>Use a for loop to calculate and print the sum of the first 10 natural numbers</li>
    <li>Write a for loop that prints all even numbers between 1 and 20.</li>
    <li>Create a for loop that prints the multiplication table for any number provided by the user (e.g., multiplication table for 5).</li>
    <li>Write a for loop that counts down from 10 to 1 and prints each number.</li>
    <li>Write a for loop that calculates the factorial of a given number (e.g., factorial of 5 is 5*4*3*2*1)</li>
    <li>Use a for loop to print the multiples of 3 from 3 to 30.</li>
    <li>Write a program using for loop to display the cube of the number up to an integer.</li>
   

  </ol>

  <br> 
   
</details>

</body>
</html>
