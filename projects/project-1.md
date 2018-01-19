---
layout: project
type: project
image: images/5zPzVYQt_400x400.jpg
title: Pokemon Text Game
permalink: projects/pokebattle
# All dates must be YYYY-MM-DD format!
date: 2017-05-05
labels:
  - Java
summary: I created a text-based game that simulates a Pokemon Battle
---

I made a Pokemon text-based game in Java using classes that I created for the different Pokemon (Bulbasaur, Venusaur, Ivysaur, Squirtle, Wartortle, Blastoise, Charmander, Charmeleon, and Charizard).

In this game:
Two players will alternate turns.
First, each player will choose a Pokemon
Then, the two players should alternate turns, entering commands to their Pokemon: fast attack, special attack,  or pass.
A player must "pass" three times to build up energy for a specialAttack.
They can do fast attacks in between, but three passes must happen between special attacks
The first player to reduce their opponent's Pokemon to 0 HP (hitPnts) wins.

Here is an excerpt from one run:

<hr>

<pre>
Lets play Pokemon!

Player 1
----------------------------------------------
What would you liked to be called? Bob

Okay Bob, enter the number of your choice:
	1. Bulbasaur
	2. Ivysaur
	3. Venusaur
	4. Charmander
	5. Charmeleon
	6. Charizard
	7. Squirtle
	8. Wartortle
	9. Blastoise

	Which Pokemon would you like to choose?
	Pokemon #: 3

	You chose Venusaur!




Player 2
----------------------------------------------
What would you liked to be called? John Smith

Okay John Smith, enter the number of your choice:
	1. Bulbasaur
	2. Ivysaur
	3. Venusaur
	4. Charmander
	5. Charmeleon
	6. Charizard
	7. Squirtle
	8. Wartortle
	9. Blastoise

	Which Pokemon would you like to choose?
	Pokemon #: 2

	You chose Ivysaur!







Bob goes first!
.
.
.
.
.
.

Bob's turn
----------------------------------------------
Enter the number of your choice:
	1. Poison Sting
	2. Solar Beam(needs at least 3 charge)
	3. Pass(charge)
	(Current charge: 0)

	Which attack would you like to choose?
	Attack: 1

	Venusaur performed Poison Sting on Ivysaur
 It was super effective!

	~John Smith's HP: 31~



John Smith's turn
----------------------------------------------
Enter the number of your choice:
	1. Vine Whip
	2. Seed Bomb(needs at least 3 charge)
	3. Pass(charge)
	(Current charge: 0)

	Which attack would you like to choose?
	Attack: 2
	**You need 3 more charge to perform Seed Bomb**
	Attack: 3

	You passed

	~Bob's HP: 36~



Bob's turn
----------------------------------------------
Enter the number of your choice:
	1. Poison Sting
	2. Solar Beam(needs at least 3 charge)
	3. Pass(charge)
	(Current charge: 0)

	Which attack would you like to choose?
	Attack: 1

	Venusaur performed Poison Sting on Ivysaur
 It was super effective!

	~John Smith's HP: 16~



John Smith's turn
----------------------------------------------
Enter the number of your choice:
	1. Vine Whip
	2. Seed Bomb(needs at least 3 charge)
	3. Pass(charge)
	(Current charge: 1)

	Which attack would you like to choose?
	Attack: 3

	You passed

	~Bob's HP: 36~



Bob's turn
----------------------------------------------
Enter the number of your choice:
	1. Poison Sting
	2. Solar Beam(needs at least 3 charge)
	3. Pass(charge)
	(Current charge: 0)

	Which attack would you like to choose?
	Attack: 1

	Venusaur performed Poison Sting on Ivysaur
 It was super effective!

	~John Smith's HP: 1~



John Smith's turn
----------------------------------------------
Enter the number of your choice:
	1. Vine Whip
	2. Seed Bomb(needs at least 3 charge)
	3. Pass(charge)
	(Current charge: 2)

	Which attack would you like to choose?
	Attack: 3

	You passed

	~Bob's HP: 36~



Bob's turn
----------------------------------------------
Enter the number of your choice:
	1. Poison Sting
	2. Solar Beam(needs at least 3 charge)
	3. Pass(charge)
	(Current charge: 0)

	Which attack would you like to choose?
	Attack: 1

	Venusaur performed Poison Sting on Ivysaur
 It was super effective!

	~John Smith's HP: 0~


----------------------------------------------

xxxxx Ivysaur fainted! xxxxx

----------------------------------------------


*.*.*.*.*.* Bob WINS! *.*.*.*.*.*
</pre>

<hr>



