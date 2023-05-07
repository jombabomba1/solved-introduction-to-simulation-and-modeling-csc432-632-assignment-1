Download Link: https://assignmentchef.com/product/solved-introduction-to-simulation-and-modeling-csc432-632-assignment-1
<br>
<strong><u>Chapters 1, 2, 3</u> </strong>

<u>Instruction:</u>

For this assignment submit a single file, either MS WORD or PDF in addition to your Python codes with descriptions. The Python codes need to have comments. The assignments must be done <strong>individually</strong>.

Format Requirements for all assignments:

<ul>

 <li>No page limits</li>

 <li>Single spaced, 12-point or larger font size; 1-inch margins</li>

 <li>Use headers and/or bullets to organize and convey key elements, and page numbers</li>

 <li>Only Latin alphabet characters are allowed (i.e., do not include any words or phrases that contain non-English characters)</li>

 <li>File type: Adobe PDF (recommended) or Word document</li>

</ul>










<strong><u>Chapter 1:</u>  </strong>




<ul>

 <li>There are multiple simulation languages and software in the market, provide a list of three languages and three software packages and explain the pros and cons.</li>

</ul>




<ul>

 <li>Use the “Managing Workshop Machinery” example in Page 17 and answer the following questions.</li>

</ul>




<ol>

 <li>Using the Classifying simulation models section in Page 9, in what classification</li>

</ol>

(static/dynamic, deterministic/stochastic, continuous/discrete) this problem falls into?

<ol>

 <li>Using the Approaching a simulation-based problem section in Page 10, explain the seven steps you would take to solve this problem using simulation.</li>

</ol>

<ul>

 <li>Similar to Q3 above, use the “Predator-prey model” example in Page 20 and answer the following questions.</li>

</ul>




<ol>

 <li>Using the Classifying simulation models section in Page 9, in what classification</li>

</ol>

(static/dynamic, deterministic/stochastic, continuous/discrete) this problem falls into?

<ol>

 <li>Using the Approaching a simulation-based problem section in Page 10, explain the seven steps you would take to solve this problem using simulation.</li>

</ol>




<strong>             </strong>

<strong><u>Chapter 2:</u>  </strong>




<ul>

 <li>Random Number Generators using <strong>Python</strong> codes

  <ol>

   <li>In <strong>Linear congruential generator</strong> (in Page 34) explain the formula and elaborate the sensitivity of the random variable generator with respect to the parameters. In other words, do you have a better set of random variables for into higher a, c, and m? Set the parameters to (a =3, c= 4, m=5, and x=3) and generate the first 100 pseudorandom values in Python. Explain the role of each Python function you use.</li>

   <li>Explain the <strong>Learmonth-Lewis generator</strong> method and its parameters (similar to Problem 5 above). Set the parameters equal to a = 60, c = 0, and m = 2^(31) -1, and generate the first uniform random variables in the range of [0, 1] in Python. Explain the commands and the role of each function you use.</li>

   <li>Explain about <strong>Lagged Fibonacci generator</strong> method and provide a list of benefits over other methods. Explain what m is in this method and how it helps to improve the generator. Implement a simple example of additive LFG in Python using the following parameters: x0 = x1 = 1 and m = 2^(32).</li>

  </ol></li>

</ul>







<ul>

 <li>Using <strong>Python</strong> function for random number generators do the following.

  <ol>

   <li>Generate 20 Pseudorandom numbers between 0 and 1.</li>

   <li>Do part (a) using random.seed() function to generate the same list of random variables.</li>

   <li>Make a random number generator using a “for-loop” that generates integer random numbers ‘n’ number of times</li>

   <li>Use a random generator to select three “same” sets of random countries from the following list.</li>

  </ol></li>

</ul>

{Canada, USA, Italy, China, India, South Africa, Spain, Brazil, Mexico}




<ul>

 <li><strong>Testing Uniformity of Final Exam Grades. </strong>A random sample of final examination grades for a college course follows.</li>

</ul>

55 85 72 99 48 71 88 70 59 98 80 74 93 85 74 82 90

71 83 60 95 77 84 73 63 72 95 79 51 85 76 81 78 65

75 87 86 70 80 64

In the book we had test of Uniformity. Use the above dataset and methods in page 4547to determine if these values are uniformly distributed. Setup your Null and Alternative hypothesis carefully.




<strong><u>Chapter 3:</u></strong><strong>  </strong>




******************************************************************************

<strong><u>Conditional Probability and Independence</u> </strong>

<strong>Conditional Probability of A given B:  </strong>The probability that event A will occur, given that event

B has occurred.  If <em>P</em>(<em>B</em>) &gt; 0, this is expressed as <em>P</em>(<em>A B</em>) =<em><sup>P</sup></em><sup>(<em>A</em></sup><sup>Ç</sup><em><sup>B</sup></em><sup>) </sup>. <em>P</em>(<em>B</em>)




<strong>Independent Events: </strong> Events A and B are considered <em>independent</em> if knowing the outcome of A gives no information about the outcome of B.  If A and B are independent, then <em>P</em>(<em>A</em>Ç<em>B</em>) =<em>P</em>(<em>A</em>)*<em>P</em>(<em>B</em>) , or equivalently, <em>P</em>(<em>A</em><em>B</em>) =<em>P</em>(<em>A</em>).




******************************************************************************




<ul>

 <li>According to the above definition, solve the following two problems.</li>

</ul>




<ol start="9">

 <li>Toss two fair dice. Let A be the event that the sum of the two dice is 9.  Let B be the event that the first die is a 4.  Are A and B independent?</li>

</ol>




<ol start="4">

 <li>Toss two fair dice. Suppose A is the event that the sum of the two dice equals 7, and B is the event that the first die shows a 4.  Are A and B independent?</li>

</ol>




<ul>

 <li>Using <strong>Python</strong> functions, generate a uniform distribution of random numbers contained in interval [0, 50] and do the following.

  <ul>

   <li>Draw a diagram in which we report the values of the 50 random numbers that we have generated.</li>

   <li>Draw a graph of the probability density function.</li>

   <li>Repeat the same graph by replicating 500 samples.</li>

  </ul></li>

</ul>




<ul>

 <li>Using <strong>Python</strong> functions and libraries, evaluate the probability density function of a binomial distribution X as the probability of success with N = 500, n = 25, and p = 0.1. Generate the probability distribution

  <ul>

   <li>Plot the data generated.</li>

   <li>Plot the histogram of the return values.</li>

   <li>Find probability of having 5 successes (that is p (X = 5))</li>

  </ul></li>

</ul>




<ul>

 <li>Using <strong>Python</strong> functions and libraries, generate a normal probability distribution Y with mu= 25, sigma = 3.

  <ul>

   <li>Generate the probability distribution</li>

   <li>Plot the data generated. Generate the same plot by changing Sigma = 4 and 5.</li>

   <li>Plot the histogram of the return values.</li>

   <li>Find P (Y &gt; 20)</li>

   <li>Find P (Y = 22.5)</li>

  </ul></li>

</ul>