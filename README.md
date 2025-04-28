# nyu-cs-homework-15--linked-lists-file-reading-solved
**TO GET THIS SOLUTION VISIT:** [NYU-CS Homework 15- Linked Lists & File Reading Solved](https://www.ankitcodinghub.com/product/nyu-cs-homework-15-linked-lists-file-reading-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118809&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;NYU-CS  Homework 15- Linked Lists \u0026amp; File Reading Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Imagine a group of friends went out to dinner together. When the bill comes they all give different amounts to contribute to the total, but after wish to balance everything out equally so that each person pays the same amount. Knowing how much each person is supposed to pay is simple enough, just add up all the amounts paid and divide by the number of people; but that doesn’t tell anyone how to go about distributing the payments, who should give what amount to whom?

Write a program that will print out a step by step list of instructions of how to reimburse everyone given the name of the person and amount of money they paid. This program should prompt the user to enter a file name associated with the info, which will then be read in. All information from the external file should be read into a linked list. An example is provided below:

Input: Output:

A few things to note:

– You should design your own linked list and node classes for this. The node class would essentially be representing people, and you can choose whatever attributes you like for it, but might be helpful to store name and amount paid (from the input file), as well amount owed, which can be initialized to 0 and then altered later upon calculating the balances

– You must be able to read in full names, accounting for both 2 and 3 part names

– The information should be read into a linked list, but after that you can handle it in whatever format you find convenient

– Don’t worry about rounding to two decimal places for $ amounts

– You can assume the data file will have at least 2 names/amounts on it, we will not test it with empty files

– The program should not alter anything in the input file, you simply are reading it in

If you are confused about how to calculate who pays whom what amount, a good way to start is to calculate the target value for everyone (total sum of what everyone paid / # of people), and see who owes money, and who is owed money (whether their “paid” attribute is above or below the target value).
