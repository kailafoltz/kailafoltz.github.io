---
layout: project
type: project
image: images/maxresdefault.jpg
title: ICS 211 - SHA-1
permalink: projects/sha1
# All dates must be YYYY-MM-DD format!
date: 2017-05-10
labels:
  - C++
  - SHA-1
summary: A C++ program that produces a hash value (message digest) from a file's contents.
---

This is a program that I made for my final project in ICS 212, Spring 2017 at Kapiolani Community College. The SHA-1 algorithm takes a file, processes the data, and produces a message digest, which is represented as an alphanumeric string. I implemented SHA-1 using C++ in order to output the message digest of text files. 

To create this program, I made several functions. The first function reads the entire contents of a file and stores the characters of the file in a large array of unsigned integers. The second function calculated the block count of the file by dividing the total bits in the file by 512 (block sizes for SHA-1 is 512 bits). Next, I made a function that coverts an array of unsigned characters to an array of unsigned integers because it is easier to read from a file using the former. I also added a function that would add the size of the file in bits into the last index of the last block. Finally, I computed the messaeg digest, initializing the blocks according to the secure hash standard, and looping through each block to process them. 

This project introduced me to the vast and complex subject of cryptogrpahy in computer science. I hope to explore more of this topic and implement it in future programs, such as one that produces hashes for passwords on a website. 
