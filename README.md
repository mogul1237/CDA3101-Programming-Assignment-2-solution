# CDA3101-Programming-Assignment-2-solution

Download Here: [CDA3101 Programming Assignment 2 solution](https://jarviscodinghub.com/assignment/cda3101-programming-assignment-2-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Instructions
Transform the following code into MIPS instructions. Your programs should run correctly on the QtSPIM simulator. Submit your assembly solution (project2.s) containing the neatly written/organized MIPS code in e-Learning (Canvas) website before the deadline.
Important • You should use comments (‘#’ followed by text) in order to make your programs more readable. • The name of the file submitted MUST be “project2.s” • You MUST verify that your submission in Canvas is successful by downloading your submission from Canvas and successfully testing it again using SPIM simulator. This will ensure that you uploaded the right file in eLearning and the upload is successful.
Problem Statement
Given three positive integers x, k and n (1 < n < 1000), write a program to compute [(x^k) mod n] using fast modular exponentiation. More references about fast modular exponentiation can be found in the following websites. https://discuss.codechef.com/questions/20451/a-tutorial-on-fast-modulo-multiplication-exponentialsquaring https://www.khanacademy.org/computing/computer-science/cryptography/modarithmetic/a/fastmodular-exponentiation Your assembly implementation should exactly follow the pseudo code sequence given below. Please do not perform any optimization at pseudo code level or at assembly level. Note: You can assume the three input values are 32-bit integers. In other words, the program should work with three inputs which are less than or equal to the number that can be represented by 32 bits. However, x to the power of k (x^k) may exceed 32 bits (e.g., 2^100). Tips: For printing to/reading from console, you should first load correct value to register $v0, and then call “syscall” method. If there is an input, the value would be returned in $v0
