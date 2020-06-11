# Challenge every day a question

What's purpose: everyday solve one or more question.

Yesterday i did talk with one of friend, who has **Gold medal in Computer olympiad**.

It's what i begin after conversation...

Follow this way with me to solving questions, it will enhance your problem-solving ability.

# Contest Questions

Archive of my programs code for contest questions.

## Level of A

<details><summary>A. Watermelon</summary>
<p>

- time limit per test: 1 second
- memory limit per test: 64 megabytes
- input: standard input
- output: standard output
 
One hot summer day Pete and his friend Billy decided to buy a watermelon. They chose the biggest and the ripest one, in their opinion. After that the watermelon was weighed, and the scales showed w kilos. They rushed home, dying of thirst, and decided to divide the berry, however they faced a hard problem.
 
Pete and Billy are great fans of even numbers, that's why they want to divide the watermelon in such a way that each of the two parts weighs even number of kilos, at the same time it is not obligatory that the parts are equal. The boys are extremely tired and want to start their meal as soon as possible, that's why you should help them and find out, if they can divide the watermelon in the way they want. For sure, each of them should get a part of positive weight.
Input
 
The first (and the only) input line contains integer number w (1 ≤ w ≤ 100) — the weight of the watermelon bought by the boys.
Output
 
Print YES, if the boys can divide the watermelon into two parts, each of them weighing even number of kilos; and NO in the opposite case.
 
#Examples
 
##Input
8
 
## Output
YES
 
## Note
For example, the boys can divide the watermelon into two parts of 2 and 6 kilos respectively (another variant — two parts of 4 and 4 kilos).

</p>
</details>


<details><summary>A. Theatre Square</summary>
<p>

-	time limit per test: 1 second
-	memory limit per test: 256 megabytes
-	input: standard input
-	output: standard output
 
Theatre Square in the capital city of Berland has a rectangular shape with the size n × m meters. On the occasion of the city's anniversary, a decision was taken to pave the Square with square granite flagstones. Each flagstone is of the size a × a.
 
What is the least number of flagstones needed to pave the Square? It's allowed to cover the surface larger than the Theatre Square, but the Square has to be covered. It's not allowed to break the flagstones. The sides of flagstones should be parallel to the sides of the Square.
 
# Input
The input contains three positive integer numbers in the first line: n,  m and a (1 ≤  n, m, a ≤ 109).
# Output
Write the needed number of flagstones.
 
# Examples
## Input
6 6 4
## Output
4

</p>
</details>


<details><summary>A. Way Too Long Words</summary>
<p>

-	time limit per test: 1 second
-	memory limit per test: 256 megabytes
-	input: standard input
-	output: standard output
 
Sometimes some words like "localization" or "internationalization" are so long that writing them many times in one text is quite tiresome.
 
Let's consider a word too long, if its length is strictly more than 10 characters. All too long words should be replaced with a special abbreviation.
 
This abbreviation is made like this: we write down the first and the last letter of a word and between them we write the number of letters between the first and the last letters. That number is in decimal system and doesn't contain any leading zeroes.
 
Thus, "localization" will be spelt as "l10n", and "internationalization» will be spelt as "i18n".
 
You are suggested to automatize the process of changing the words with abbreviations. At that all too long words should be replaced by the abbreviation and the words that are not too long should not undergo any changes.
 
# Input
 
The first line contains an integer n (1 ≤ n ≤ 100). Each of the following n lines contains one word. All the words consist of lowercase Latin letters and possess the lengths of from 1 to 100 characters.
 
# Output
Print n lines. The i-th line should contain the result of replacing of the i-th word from the input data.
 
# Examples
## Input
4
word
localization
internationalization
pneumonoultramicroscopicsilicovolcanoconiosis
## Output
word
l10n
i18n
p43s

</p>
</details>



<details><summary>A. String Task</summary>
<p>

-	time limit per test: 2 seconds
-	memory limit per test: 256 megabytes
-	input: standard input
-	output: standard output
 
Petya started to attend programming lessons. On the first lesson his task was to write a simple program. The program was supposed to do the following: in the given string, consisting if uppercase and lowercase Latin letters, it:
 
- deletes all the vowels,
- inserts a character "." before each consonant,
- replaces all uppercase consonants with corresponding lowercase ones. 
 
Vowels are letters "A", "O", "Y", "E", "U", "I", and the rest are consonants. The program's input is exactly one string, it should return the output as a single string, resulting after the program's processing the initial string.
 
Help Petya cope with this easy task.
Input
 
The first line represents input string of Petya's program. This string only consists of uppercase and lowercase Latin letters and its length is from 1 to 100, inclusive.
Output
 
Print the resulting string. It is guaranteed that this string is not empty.
 
# Examples
## Input
tour
## Output
.t.r
 
## Input
Codeforces
## Output
.c.d.f.r.c.s
 
## Input
aBAcAba
## Output
.b.c.b
</p>
</details>



<details><summary>A. Football</summary>
<p>

-	time limit per test: 2 seconds
-	memory limit per test: 256 megabytes
-	input: standard input
-	output: standard output
 
Petya loves football very much. One day, as he was watching a football match, he was writing the players' current positions on a piece of paper. To simplify the situation he depicted it as a string consisting of zeroes and ones. A zero corresponds to players of one team; a one corresponds to players of another team. If there are at least 7 players of some team standing one after another, then the situation is considered dangerous. For example, the situation 00100110111111101 is dangerous and 11110111011101 is not. You are given the current situation. Determine whether it is dangerous or not.
 
# Input
The first input line contains a non-empty string consisting of characters "0" and "1", which represents players. The length of the string does not exceed 100 characters. There's at least one player from each team present on the field.
 
# Output
Print "YES" if the situation is dangerous. Otherwise, print "NO".
 
# Examples
## Input
001001
## Output
NO
 
## Input
1000000001
## Output
YES

</p>
</details>



<details><summary>A. Boy or Girl</summary>
<p>

-	time limit per test: 1 second
-	memory limit per test: 256 megabytes
-	input: standard input
-	output: standard output
 
Those days, many boys use beautiful girls' photos as avatars in forums. So it is pretty hard to tell the gender of a user at the first glance. Last year, our hero went to a forum and had a nice chat with a beauty (he thought so). After that they talked very often and eventually they became a couple in the network.
 
But yesterday, he came to see "her" in the real world and found out "she" is actually a very strong man! Our hero is very sad and he is too tired to love again now. So he came up with a way to recognize users' genders by their user names.
 
This is his method: if the number of distinct characters in one's user name is odd, then he is a male, otherwise she is a female. You are given the string that denotes the user name, please help our hero to determine the gender of this user by his method.
Input
 
The first line contains a non-empty string, that contains only lowercase English letters — the user name. This string contains at most 100 letters.
Output
 
If it is a female by our hero's method, print "CHAT WITH HER!" (without the quotes), otherwise, print "IGNORE HIM!" (without the quotes).
 
# Examples
 
## Input
wjmzbmr
## Output
CHAT WITH HER!
 
## Input
xiaodao
## Output
IGNORE HIM!
 
## Input
sevenkplus
## Output
CHAT WITH HER!
 
# Note
For the first example. There are 6 distinct characters in "wjmzbmr". These characters are: "w", "j", "m", "z", "b", "r". So wjmzbmr is a female and you should print "CHAT WITH HER!".

</p>
</details>


<details><summary>A. Dubstep</summary>
<p>

-	time limit per test: 2 seconds
-	memory limit per test: 256 megabytes
-	input: standard input
-	output: standard output
 
Vasya works as a DJ in the best Berland nightclub, and he often uses dubstep music in his performance. Recently, he has decided to take a couple of old songs and make dubstep remixes from them.
 
Let's assume that a song consists of some number of words. To make the dubstep remix of this song, Vasya inserts a certain number of words "WUB" before the first word of the song (the number may be zero), after the last word (the number may be zero), and between words (at least one between any pair of neighbouring words), and then the boy glues together all the words, including "WUB", in one string and plays the song at the club.
 
For example, a song with words "I AM X" can transform into a dubstep remix as "WUBWUBIWUBAMWUBWUBX" and cannot transform into "WUBWUBIAMWUBX".
 
Recently, Petya has heard Vasya's new dubstep track, but since he isn't into modern music, he decided to find out what was the initial song that Vasya remixed. Help Petya restore the original song.
Input
 
The input consists of a single non-empty string, consisting only of uppercase English letters, the string's length doesn't exceed 200 characters. It is guaranteed that before Vasya remixed the song, no word contained substring "WUB" in it; Vasya didn't change the word order. It is also guaranteed that initially the song had at least one word.
Output
 
Print the words of the initial song that Vasya used to make a dubsteb remix. Separate the words with a space.
# Examples
## Input
WUBWUBABCWUB
## Output
ABC 
 
## Input
WUBWEWUBAREWUBWUBTHEWUBCHAMPIONSWUBMYWUBFRIENDWUB
## Output
WE ARE THE CHAMPIONS MY FRIEND 
 
# Note
In the first sample: "WUBWUBABCWUB" = "WUB" + "WUB" + "ABC" + "WUB". That means that the song originally consisted of a single word "ABC", and all words "WUB" were added by Vasya.
 
In the second sample Vasya added a single word "WUB" between all neighbouring words, in the beginning and in the end, except for words "ARE" and "THE" — between them Vasya added two "WUB".



</p>
</details>

<details><summary>A. Bit++</summary>
<p>

-	time limit per test: 1 second
-	memory limit per test: 256 megabytes
-	input: standard input
-	output: standard output

The classic programming language of Bitland is Bit++. This language is so peculiar and complicated.

The language is that peculiar as it has exactly one variable, called x. Also, there are two operations:

- Operation ++ increases the value of variable x by 1.
- Operation -- decreases the value of variable x by 1. 

A statement in language Bit++ is a sequence, consisting of exactly one operation and one variable x. The statement is written without spaces, that is, it can only contain characters "+", "-", "X". Executing a statement means applying the operation it contains.

A programme in Bit++ is a sequence of statements, each of them needs to be executed. Executing a programme means executing all the statements it contains.

You're given a programme in language Bit++. The initial value of x is 0. Execute the programme and find its final value (the value of the variable when this programme is executed).

# Input

The first line contains a single integer n (1 ≤ n ≤ 150) — the number of statements in the programme.

Next n lines contain a statement each. Each statement contains exactly one operation (++ or --) and exactly one variable x (denoted as letter «X»). Thus, there are no empty statements. The operation and the variable can be written in any order.

# Output

Print a single integer — the final value of x.

# Examples

## Input
1
++X
## Output
1

## Input
2
X++
--X
## Output
0

</p>
</details>


<details><summary>A. Word Capitalization</summary>
<p>

- time limit per test: 2 seconds
-	memory limit per test: 256 megabytes
-	input: standard input
-	output: standard output

Capitalization is writing a word with its first letter as a capital letter. Your task is to capitalize the given word.

Note, that during capitalization all the letters except the first one remains unchanged.

# Input

A single line contains a non-empty word. This word consists of lowercase and uppercase English letters. The length of the word will not exceed 103.

# Output

Output the given word after capitalization.

# Examples

## Input
ApPLe

## Output
ApPLe

## Input
konjac
## Output
Konjac


</p>
</details>



<details><summary>A. Chat room</summary>
<p>

-	time limit per test: 1 second
-	memory limit per test: 256 megabytes
-	input: standard input
-	output: standard output

Vasya has recently learned to type and log on to the Internet. He immediately entered a chat room and decided to say hello to everybody. Vasya typed the word s. It is considered that Vasya managed to say hello if several letters can be deleted from the typed word so that it resulted in the word "hello". For example, if Vasya types the word "ahhellllloou", it will be considered that he said hello, and if he types "hlelo", it will be considered that Vasya got misunderstood and he didn't manage to say hello. Determine whether Vasya managed to say hello by the given word s.

# Input

The first and only line contains the word s, which Vasya typed. This word consisits of small Latin letters, its length is no less that 1 and no more than 100 letters.

# Output

If Vasya managed to say hello, print "YES", otherwise print "NO".

# Examples

## Input
ahhellllloou
## Output
YES

## Input
hlelo
## Output
NO

</p>
</details>



## Level of H


-------------

## Logs

- **2020/06/09**: Solve 7 questions
- **2020/06/10**: Solve 1 question
- **2020/06/11**: Solve 2 questions

---------

# Max Base

My nickname is Max, Programming language developer, Full-stack programmer. I love computer scientists, researchers, and compilers. ([Max Base](https://maxbase.org/))

## Asrez Team

A team includes some programmer, developer, designer, researcher(s) especially Max Base.

[Asrez Team](https://www.asrez.com/)
