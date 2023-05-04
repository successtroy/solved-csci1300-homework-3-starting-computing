Download Link: https://assignmentchef.com/product/solved-csci1300-homework-3-starting-computing
<br>
Understand how to implement decisions using if statements.

You can find <a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45795">hw3 note: if-else, switch on Moodl</a>​ <a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45795">e</a><a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45795">.</a><u>​</u>




<h1>Questions</h1>

<strong>Question 1: Practicum average  </strong>

In this course, students need to have at least 67 average score on practicums to earn​            ​ C- or higher letter grades. It would be useful to have a program to calculate your practicum average. Write a program that asks the user to enter three practicum scores and calculate the average score. Then, it prints the average score and prints the message depending on the average score.




If the calculated average score is 67 or higher, then it prints

“You have a passing practicum average.​ ”​

If it’s below 67, then it prints

“You can retake practicums during the final.​ ”​




Each practicum score should be an integer value. The practicum average should be a double​        formatted with a two-digit precision as shown below.




Expected output 1 (<strong>bold</strong>​ is user input)​

<table width="624">

 <tbody>

  <tr>

   <td width="624">Enter practicum 1 score: <strong>90 </strong>Enter practicum 2 score: <strong>85 </strong>Enter practicum 3 score: <strong>75 </strong>Practicum average: 83.33You have a passing practicum average.</td>

  </tr>

 </tbody>

</table>




The file should be named as practicum.cpp​           . Don’t forget to head over to the code runner on​        Moodle and paste your solution in the answer box!







<strong>Question 2: Total pay </strong>

Write a program that asks the number of hours worked and hourly pay rate, as floating point numbers. Then, it displays the calculated total pay. Hours worked over 40 hours are considered as overtime and should be calculated at 1.5x the pay rate.




Be sure to have input validation. If one or both input values are negative values, it does not make sense. If a pay rate of -$10 and 41 hours worked, then the pay would be -$415. Instead of printing the negative value of the pay, print “Invalid input​          ”.​




For example, if Punith worked 42 hours (40 hours + 2 hours of overtime), and his pay rate is $12. Then, his paycheck will be $516.




Regular Pay:        $ 480.00    ($12 x 40 hours)

Overtime Pay:      $   36.00    (1.5 x $12 * 2 hours)

Total Pay:             $ 516.00




The total pay(pay check) should be formatted with a two-digit precision as shown below.













Expected output 1 (<strong>bold</strong>​ is user input)​

Enter the number of hours worked

<strong>45.5 </strong>

Enter an hourly pay rate

<strong>17.6 </strong>

Paycheck: 849.20




Expected output 2 (<strong>bold</strong>​ is user input)​

Enter the number of hours worked

<strong>-45.5 </strong>

Enter an hourly pay rate

<strong>20.0 </strong>

Invalid input

The file should be named as pay.cpp​             . Don’t forget to head over to the code runner on Moodle​       and paste your solution in the answer box!




<strong>Question 3: Sushi restaurant </strong>

Ashwin opened a sushi restaurant in Seattle. Each sushi piece is $1.99. His restaurant offers a student discount depending on the number of pieces they eat.




<table width="288">

 <tbody>

  <tr>

   <td width="186">Quantity</td>

   <td width="102">Discount</td>

  </tr>

  <tr>

   <td width="186">10 – 1920 – 4950 – 99100 or more</td>

   <td width="102">10 %15 %20 %25 %</td>

  </tr>

 </tbody>

</table>




Write a program that asks the number of sushi pieces eaten and compute the total price. Be sure to have an input validation. The value entered should be greater than 0. If not, print “Invalid​ input”.​ The total price should be formatted with a two-digit precision as shown below.







Expected output 1 (<strong>bold</strong>​ is user input)​

Enter the number of sushi:

<strong>3 </strong>

Total price: $5.97




Expected output 2 (<strong>bold</strong>​ is user input)​

Enter the number of sushi:

<strong>-7 </strong>

Invalid input







Expected output 3 (<strong>bold</strong>​ is user input)​

Enter the number of sushi:

<strong>23 </strong>

Total price: $38.90




The file should be named as sushi.cpp​       . Don’t forget to head over to the code runner on​        Moodle and paste your solution in the answer box!




<strong>Question 4(10pt): boxers’ weights  </strong>

Your manager gave a task to write a program that takes weights of three boxers (as integer values) and check if they are sorted by their weights. If the weights are sorted, then it prints

“Ascending order​  ”, “​ Descending order​          ”, or “​    Neither​           ”. If two or more weights are the​ same, they are considered as neither. The users are well trained, and they will enter weights separated by spaces.




Expected output 1 (<strong>bold</strong>​ is user input)​

Enter boxers’ weights

<strong>162 180 225 </strong>

Ascending order <strong> </strong>




Expected output 2 (<strong>bold</strong>​ is user input)​

Enter boxers’ weights

<strong>225 180 162 </strong>

Descending order <strong> </strong>




Expected output 3 (<strong>bold</strong>​ is user input)​

Enter boxers’ weights

<strong>162 135 225 </strong>Neither




The file should be named as boxer.cpp​       . Don’t forget to head over to the code runner on​        Moodle and paste your solution in the answer box!




<strong>Question 5: Days in a month </strong>

Write a program that asks the user to enter a year and month(1-12). Then, the program should display the number of days in that month. If the entered month is not between 1 and 12, then print “Invalid month​ ”. Don’t forget about leap years!​




What is a leap year? In general, years divisible by 4 are leap years. For dates after 1582, however, there is a Gregorian correction: years that are divisible by 100 are not leap years but years divisible by 400, are. So, for instance, 1900 was not a leap year but 2000 was.




Expected output (​<strong>bold</strong>​ is user input)

Enter a year:

<strong>2008 </strong>

Enter a month:

<strong>2 </strong>

29 days




Extra credit: if you use a ​switch​ statement for this question, we will give you 5pt extra credit.




The file should be named as ​daysInMonth.cpp​. Don’t forget to head over to the code runner on Moodle and paste your solution in the answer box!




<strong>Question 6(15pt): Personalized ad </strong>

You have graduated from CU Boulder, and now have a job to create a personalized ad program to serve a person on a social media platform. The program prompts the user for information and then text that describes ads based on their inputs. There are three scenarios for the program. The program asks the users which scenario they want to do. Then, depending on the choices, the program asks information and show an ad. Please make sure to print “​Invalid option.​” if they choose other than three scenarios.




Extra Credit: If you use a ​switch​ statement for this question, we will give you 5 pt extra credit.




<em>Scenario 1</em>​: For advertisers using the lowest tier of personalization on this social media platform, there is limited data about users available — we only know whether a user self-reported that they own dog.




For scenario 1, the program asks the user to enter if they own a dog. If they own a dog, then the program prints:

“​Meat’s the need of dogs like yours!​”




Otherwise, the program prints:

“​Dirty mouth? Clean it up with new Orbit Raspberry Mint.​”




The users will be more likely to type “​yes​” or “​no​”, but some of them might not. We consider “​yes​” and “​Yes​” as “​yes​”. If the users type other than “​yes​” or “​Yes​”, then the program considers them as a “​no​”.







Expected output for Scenario 1  (<strong>bold</strong>​ ​ is user input):

How personalized should the ad be?   (1-3)​

<strong>1 </strong>

Do you own a dog?

<strong>yes </strong>

Meat’s the need of dogs like yours!







<em>Scenario 2</em>​: Combining data from a marketing platform with the results from personality tests, we know that people with at least 500 Facebook friends are likely to be extroverts, and people with less than 500 friends are likely to be introverts. By using computer-vision, we also know extroverts post more dog photos, and introverts tend to post more photos of cats. Market research has shown that dog people are highly likely to be positively influenced by advertisements for any product that includes dogs, and similar for cat people and cats.




For Scenario 2, the program asks the user how many Facebook friends they have. If  the number of Facebook friends is greater than or equal to 500, the program prints:

“Don’t like cleaning up after your dog? Call Doody Free to sign up​          for backyard cleanup or dog walking service.”​




If the number of Facebook friends is less than 500, it prints:

“Who doesn’t need another cat? Adopt a shelter pet right meow.​  ”​




Expected output for Scenario 2  (<strong>bold</strong>​ ​ is user input):

How personalized should the ad be?   (1-3)​

<strong>2 </strong>

How many Facebook friends do you have?

<strong>450 </strong>

Who doesn’t need another cat? Adopt a shelter pet right meow.




<em>Scenario 3</em>​: Based on ad clicks and third-party data shared through purchases on a “marketplace” platform, we have data about likely income averages for every zip code in the country. We also know based on self-reported age how incomes vary based on life stage (e.g., college students have less disposable income no matter where they live). Advertisers strategically advertise to people who are more likely to be able to afford their product.




For Scenario 3, the program asks the users to enter their zip code and age. Then, it prints the ad.

<ul>

 <li>If the zipcode is in Boulder (i.e. between and including 80301 and 80310) and the user is at least 25, print ad text for an expensive product.</li>

</ul>

“You are surrounded by professional athletes. Up your exercise​       game in the privacy of your home with a Peloton bike.”​

<ul>

 <li>If the zipcode is in Boulder and the user is younger than 25, print ad text for an inexpensive product.</li>

</ul>

“Looking for dinner that won’t break the bank? Tacos. Come grab​      a $3 at Centro Latin Kitchen.”​

<ul>

 <li>Otherwise, print ad text encouraging the user to visit Boulder.</li>

</ul>

“Feeling Uninspired? The Boulder Flatirons are calling. Come​          hike to inspiring views, delicious food, and enjoy the hospitality of Boulder, CO.”​




Expected output for Scenario 3 (<strong>bold</strong>​ is user input):​

How personalized should the ad be?   (1-3)​

<strong>3 </strong>

What is your zip code?

<strong>80302 </strong>

What is your age?

<strong>22 </strong>

Looking for dinner that won’t break the bank? Tacos. Come grab a $3 at Centro Latin Kitchen.




<em>Invalid Scenario</em>​: If the user chooses a scenario that is not between 1 and 3, print “Invalid​          option.”​




Expected output for an invalid scenario (<strong>bold</strong>​ is user input):​

How personalized should the ad be?   (1-3)​

<strong>7 </strong>

Invalid option.




The file should be named as personalizedAd.cpp​            . Don’t forget to head over to the code​              runner on Moodle and paste your solution in the answer box!

<h1>Homework 3 checklist</h1>

Here is a checklist for submitting the assignment:

<ol>

 <li>Complete the <a href="https://moodle.cs.colorado.edu/mod/quiz/view.php?id=45793"><strong>conceptual reviews(mcq</strong></a><u>​ </u><a href="https://moodle.cs.colorado.edu/mod/quiz/view.php?id=45793"><strong>)</strong></a></li>

 <li>Complete the code <a href="https://moodle.cs.colorado.edu/mod/quiz/view.php?id=45794"><strong>Homework 3 CodeRunne</strong></a><u>​ </u><a href="https://moodle.cs.colorado.edu/mod/quiz/view.php?id=45794"><strong>r</strong></a></li>

 <li>Submit one zip file to <a href="https://moodle.cs.colorado.edu/mod/assign/view.php?id=40830"><strong>Homework </strong></a><u>​ </u><a href="https://moodle.cs.colorado.edu/mod/assign/view.php?id=40830"><strong>3</strong></a>. The zip file should be named, ​         <strong>zip</strong>​        . It​           should have the following 6 files:</li>

</ol>

<strong>○    practicum.cpp </strong>

<strong>○    pay.cpp </strong>

<strong>○    sushi.cpp </strong>

<strong>○    boxer.cpp </strong>

<strong>○    daysInMonth.cpp </strong>

<strong>○    personalizedAd.cpp </strong>

<h1>Homework 3 points summary</h1>

<table width="422">

 <tbody>

  <tr>

   <td width="215"><strong>Criteria </strong></td>

   <td width="93"> </td>

   <td width="114"><strong>Pts </strong></td>

   <td width="0"></td>

  </tr>

  <tr>

   <td width="215">Conceptual reviews (MCQ)</td>

   <td width="93"> </td>

   <td width="114">10</td>

   <td width="0"></td>

  </tr>

  <tr>

   <td width="215">CodeRunner (problem 1 – 6)</td>

   <td width="93"> </td>

   <td width="114">60</td>

   <td width="0"></td>

  </tr>

  <tr>

   <td rowspan="2" width="215">C++ file submission (compiles a and comments)Recitation attendance (Week 4)*</td>

   <td rowspan="2" width="93">nd runs, style </td>

   <td rowspan="2" width="114">30-30</td>

   <td width="0"></td>

  </tr>

  <tr>

   <td width="0"></td>

  </tr>

  <tr>

   <td width="215">Total</td>

   <td width="93"> </td>

   <td width="114">100</td>

   <td width="0"></td>

  </tr>

  <tr>

   <td width="215">5% early submission bonus</td>

   <td width="93"> </td>

   <td width="114">+5%</td>

   <td width="0"></td>

  </tr>

  <tr>

   <td width="215">Implement with ​switch​ (proble</td>

   <td width="93">m 5, 6)</td>

   <td width="114">+5pt each</td>

   <td width="0"></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

* if your attendance is not recorded, you will lose points. Make sure your attendance is recorded on Moodle.











