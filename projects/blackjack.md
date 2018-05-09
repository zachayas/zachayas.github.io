---
layout: project
type: project
image: images/blackjack/back_cards.png
title: Blackjack 21
permalink: projects/blackjack
# All dates must be YYYY-MM-DD format!
date: 2018-5-01
labels:
  - Java
  - Oracle
  - SQL
summary: Recreation of Blackjack 21
---

<img class="ui medium image" src="/images/blackjack/landing.PNG">

This was my first time working with file input in C and Unix. I had to take a text file or direct input and parse it then count how many times letters appear in the text. The issue with this was having to parse chars from strings with spaces and punctuation. 

How I solved this was one array to keep tally. Then whenever the program parse a char, it would convert the letter into a number to represent the index (e.g a = 1, b = 2, etc.) then increment the tally array at the letters index, then print. This worked for small sentences but txt files would parse it incorrectly (reads the space or periods). 
I then created two more arrays to check if char parsed was valid by comparing the char with the actual letter for both upper and lower case. If it was valid then we convert and increment the tally. 

What I learned from this was to smetimes just brute force your way into the solution, my original method was more efficient but it didn't work in all situations while the brute force method of validating every letter works in any condiitons. This helped me to work faster since copying and pasting in Unix messes with the format, so just typing faster is better than copy and paste. 


<a href="https://github.com/zachayas/blackjack"><i class="large github icon"></i>Blackjack</a>


