# COMPILER-DESIGN-BASICS

COMPANY: CODTECH IT SOLUTIONS

NAME: LEMINA BHAGAT

INTERN ID: CT04WE100

DOMAIN: C PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

#DESCRIPTION:This program implements a basic data compression technique called Run-Length Encoding (RLE) using the C programming language. RLE is one of the simplest forms of lossless data compression, where the idea is to reduce the size of repetitive data by storing only the value and the number of times it appears consecutively. For example, instead of storing “AAAAAA”, the program stores it as “A6”, meaning the letter A appears six times in a row. This technique is widely used in image compression (like BMP or TIFF formats), basic data storage, and simple text-based applications where patterns repeat often. The beauty of RLE lies in its simplicity, and this C program is a clean and easy-to-understand implementation of the concept.

When the program runs, it takes a string as input—this could be any line of text from the user. The program then scans through the string one character at a time and counts how many times the same character appears consecutively. If a character repeats, the count increases; as soon as a different character is encountered, it records the character and its count, then starts counting the new character. For example, if the user enters a string like “aaabbbbcc”, the program outputs something like “a3b4c2”. This result is shorter than the original in terms of characters and is easier to store or transmit when dealing with long repetitions.

Internally, the program uses a loop that compares each character in the input string with the one following it. If the two characters match, it increases a counter. If they don’t, it prints (or stores) the current character and the counter, then resets the counter to 1 and continues to the next character. This approach ensures that all repeated segments are compressed correctly and no characters are missed. The final character group is also processed after the loop ends to handle the tail end of the string.

What makes this implementation especially helpful for beginners is that it sticks to basic programming constructs—simple loops, conditional statements, character arrays, and integer counters—without involving any complex data structures or libraries. This makes it easy to follow and learn from. At the same time, it introduces the idea of data encoding and compression, which is a very real-world problem in computing. It also encourages thinking in terms of optimization and efficiency, which are key aspects of programming.

RLE works best when the input data has lots of repeated characters. If the input has very few repetitions (for example, "abcdef"), the RLE version may not be smaller—in some cases, it may even be slightly longer. But in practical scenarios like compressing monochrome images or repeated characters in logs, the reduction in size can be significant. This implementation is a great way to understand how compression algorithms work at the most basic level.

In summary, this program helps students and learners grasp both a useful algorithm and core C programming techniques at the same time. It reinforces the concept of loops, arrays, and conditional logic, while also providing insight into how repeated data can be handled more efficiently. It’s an ideal starting point for anyone who wants to explore the world of data compression or improve their problem-solving skills with a real-world coding exercise.

#OUTPUT:

![Image](https://github.com/user-attachments/assets/c5f19179-9f2b-4866-aca0-1d58c67e3210)
