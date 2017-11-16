
# Tanning-Salon

Tanning Salon


Description

Tan Your Hide, Inc., owns several coin-operated tanning salons. Research has shown that if a customer arrives and there are no beds available, the customer will turn around and leave, thus costing the company a sale. Your task is to write a program that tells the company how many customers left without tanning.

Input

The input consists of data for one or more salons, followed by a line containing the number 0 that signals the end of the input. Data for each salon is a single line containing a positive integer, representing the number of tanning beds in the salon, followed by a space, followed by a sequence of uppercase letters. Letters in the sequence occur in pairs. The first occurrence indicates the arrival of a customer, the second indicates the departure of that same customer. No letter will occur in more than one pair. Customers who leave without tanning always depart before customers who are currently tanning. There are at most 20 beds per salon.

Output

For each salon, output a sentence telling how many customers, if any, walked away. Use the exact format shown below.

Sample Input

2 ABBAJJKZKZ
3 GACCBDDBAGEE
3 GACCBGDDBAEE
1 ABCBCA
0

Sample Output

All customers tanned successfully.
1 customer(s) walked away.
All customers tanned successfully.
2 customer(s) walked away.
