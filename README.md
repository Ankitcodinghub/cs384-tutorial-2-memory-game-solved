# cs384-tutorial-2-memory-game-solved
**TO GET THIS SOLUTION VISIT:** [CS384 Tutorial 2–Memory Game Solved](https://www.ankitcodinghub.com/product/cs384-tutorial-2-memory-game-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95725&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS384 Tutorial 2–Memory Game Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Things to be kept in mind

<ol>
<li>You should first check that the list does not contain any floating numbers or characters. The list should have only integers as input. If a non int is present, just output: “Please enter a valid input list” and show all the elements that was invalid. E.g, if input nums = [1,4, ”a”, 3, 5, ”Star”, 7.5], then output will be: “Please enter a valid input list”. Invalid inputs detected”: [“a”, “Star”, 7.5] and exit the code. You can use isdigit() function also.</li>
<li>While evaluating your program, the TA we will modify the input list (input nums), and check for correctness. End user will not enter any input via keyboard, the input will be static in nature, input nums = []</li>
<li>Program will be checked for plagiarism.</li>
</ol>
# Returns the score from a memory game. The strategy is to remove the number that has been in the memory the longest time.

A memory game is played (and scored) as follows: Random numbers between 0 and 10 (zero inclusive) are called out one at a time. In this memory game the player can remember a maximum of 5 previously called out numbers. If the called number is already in the player’s memory, a point is added to the player’s score. If the called number is not in the player’s memory, the player adds the called number to his memory, first removing another number if his memory is full. In our simulation of this game, the number which is removed from the player’s memory is the number that has been in the player’s memory the longest time. For example, if the random numbers are [3, 4, 3, 0, 7, 4, 5, 2, 1, 3], the game proceeds as follows:

Called number 3: Score: 0, Numbers in memory: [3]

Called number 4: Score: 0, Numbers in memory: [3, 4]

Called number 3: Score: 1, Numbers in memory: [3, 4]

</div>
</div>
<div class="layoutArea">
<div class="column">
Called number 0: Score: 1, Numbers in memory: [3, Called number 7: Score: 1, Numbers in memory: [3, Called number 4: Score: 2, Numbers in memory: [3, Called number 5: Score: 2, Numbers in memory: [3, Called number 2: Score: 2, Numbers in memory: [4, Called number 1: Score: 2, Numbers in memory: [0, Called number 3: Score: 2, Numbers in memory: [7,

Complete the get memory score() function which

and returns the final score using the algorithm described above. For example, the following code:

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
4, 0]

4, 0, 7]

4, 0, 7]

4, 0, 7, 5] 0, 7, 5, 2] 7, 5, 2, 1] 5, 2, 1, 3]

</div>
</div>
<div class="layoutArea">
<div class="column">
is passed a list of random numbers as a parameter

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
print(”1. Score:”, get memory score([3, 4, 1, 6, 3, 3, 9, 0, 0, 0]))

print(”2. Score:”, get memory score([1, 2, 2, 2, 2, 3, 1, 1, 8, 2]))

print(”3. Score:”, get memory score([2, 2, 2, 2, 2, 2, 2, 2, 2]))

print(”4. Score:”, get memory score([1, 2, 3, 4, 5, 6, 7, 8, 9]))

input nums = [7, 5, 8, 6, 3, 5, 9, 7, 9, 7, 5, 6, 4, 1, 7, 4, 6, 5, 8, 9, 4, 8, 3, 0, 3] print(”5. Score:”, get memory score(input nums))

prints: 1. Score: 4 2. Score: 6 3. Score: 8 4. Score: 0

5. Score: 10

Sample input output

Input

input nums = [3, 4, 1, 6, 3, 3, 9, 0, 0, 0]

Output

Score: 4

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
