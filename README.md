# eee472-cse422-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [EEE472/CSE422 Assignment 2 Solved](https://www.ankitcodinghub.com/product/eee472-cse422-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119742&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEE472\/CSE422 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Strange Bank Problem

Suppose, you are the owner of a bank that operates in a strange way. Customers can lend money from your bank (just like a normal bank) and they can also deposit money in your bank. A register is maintained to track the daily transactions. However, being the strange owner of a strange bank, you have a fascination with finding out whether a portion of your daily transactions (in/out) balance out to zero. For example, suppose your daily transaction register looks like this:

1 Lend 100

2 Deposit 150

3 Lend 400

4 Lend 500

5 Deposit 1000

6 Lend 460

7 Deposit 160

8 Deposit 200

9 Lend 500

10 Depost 100

In this case, there is a portion of the transactions that would balance itself out. (6th, 7th, 8th, and 10th transactions would amount to 0).

Your task is to use a genetic algorithm to solve this strange bank problem.

Task Breakdown:

1. Model the transaction register in a way suitable for the problem.

2. Write a fitness function. Hint: It is the sum of the non-zero elements of a register.

3. Write the crossover function.

4. Write the mutation function.

5. Create a population of randomly generated registers.

6. Run genetic algorithms on the population until highest fitness has been reached and/or number of maximum iterations has been reached. Input followed by 𝑁 lines each starting𝑁 with either l or d and a number 𝑆 denoting The first line has a number denoting the number of daily transactions

the amount of transaction. Here:

𝑁

Output𝑆 ( 1 𝑆 10 )

The output would be a binary string denoting the specific transactions that balance themselves to zero or -1 if such a string cannot be formed. String consisting of all zeros won’t be accepted.

Example:

Sample Input 1

7

l 120 l 289 d 475 l 195 d 6482 l 160 d 935

Sample Output 1

1011010

Sample Input 2

5

l 100 l 450 d 500 l 7923 d 9055

Sample Output 2

-1
