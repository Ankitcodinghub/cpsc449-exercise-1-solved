# cpsc449-exercise-1-solved
**TO GET THIS SOLUTION VISIT:** [CPSC449 Exercise 1 Solved](https://www.ankitcodinghub.com/product/cpsc-449-exercise-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116294&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPSC449 Exercise 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
For this exercise you are expected to develop at least 6 of the programs below. The tutorials will work through (some of) the solutions. You are expected to hand in a documented Haskell script containing your solutions … I encourage you to discuss these programs with your classmates: the aim is to complete these exercises (somehow!) so that you get used to thinking in Haskell syntax. You should comment your code indicating, in particular, from where you got the solution if it is not your own. Recall that it is important that you understand the solutions as this comprehension will be tested in the tutorial written tests and your ability to program will be tested by the assignment.

Please name your functions according to what is prescribed below. If there are name conflicts with names defined in Prelude, then (a) explicitly import Prelude, and (b) use the hiding clause to hide the conflicting names when importing (see the grey box on page 53 of [Thompson]).

1. Write a function

avgThree:: Int -&gt; Int -&gt; Int -&gt; Float

to take the average of three integers which returns a float.

2. Write a function

maxThree:: Int -&gt; Int -&gt; Int -&gt; (Int,Int)

which works out the maximum of three integers and returns also how many times that maximum occurs.

3. Write a function

data SF a = SS a | FF

invFac:: Integer -&gt; SF Integer

which returns the largest number whose factorial is no greater than the given number (what happens if the given number is negative?).

4. Implement a function myGcd that takes two integers as arguments, and returns the greatest common divisor using the Euclid’s Algorithm.

myGcd :: Int -&gt; Int -&gt; Int

5. The binomial coefficient is defined as follows for integers n ≥ 1 and 0 ≤ k ≤ n:

Write a function:

binom:: Integer -&gt; Integer -&gt; Integer

to calculate the binomial coefficients.

6. Write a function

grow :: String -&gt; String

which changes a string a1a2a3… to a1a2a2a3a3a3… so grow “now!” == “noowww!!!!”.

7. Write a function

instrictorder:: [Int]-&gt; Bool

which tests whether the list of integers is strictly increasing.

8. Write a function

cheapItems:: [(String,Int)] -&gt; Int -&gt; [String]

which given a list of items and their cost (here just an integer) returns a list of items whose cost is (strictly) below a given threshold cost.

9. Write a function

sortByCost :: [(String,Int)] -&gt; [(String,Int)]

which, given a list of items with a cost, returns a list in cheapest first order.

10. Write a function

divisors:: Integer -&gt; [Integer]

which calculates the list (in ascending order) of all prime divisors of a positive integer (returning the empty list if the number is less than or equal to one).

11. Defined function

substring :: String -&gt; String -&gt; Bool

which determines whether a given first string is a substring of a second string.

12. Write a function

sublists:: [a] -&gt; [[a]]

which given a list of any type returns the list of all sublists of that list.
