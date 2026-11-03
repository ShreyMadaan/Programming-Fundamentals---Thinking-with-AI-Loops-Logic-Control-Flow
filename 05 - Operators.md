## Question 1:
What is the output of the JAVA code snippet?
int a = 5, b = 10, c = 15;
a -= 3;
b *= 2;
c /= 5;
System.out.println(a + " " + b + " " + c);

Choose the correct answer from below:
2 20 3
2 20 5
2 10 5
-2 20 3

## Question 2:
Given two numbers A and B. Multiply them and print the product.
Problem Constraints
105 <= A, B <= 106
Input Format
Two space separated integers A and B in the first line.
Output Format
Print in a single line the product of A and B.
Example Input
Input 1 : 100000 1000000
Input 2 : 1000000 10000000
Example Output
Output 1 : 100000000000
Output 2 : 10000000000000
Example Explanation
Explanation 1 : 100000 * 1000000 = 100000000000
Explanation 2 : 1000000 * 10000000 = 10000000000000

## Question 3:
What is the output of the Java code snippet?
boolean b = false;
b = !b;
System.out.println(b);
Choose the correct answer from below:
true
false
Compilation Error
None of the above

## Question 4:
What is the output of the following program :
int a = 20;
int b = 10;
System.out. print((a > b) && (b++ > 25));
System.out.println(b);

Choose the correct answer from below:
true 10
true 11
false 10
false 11

## Question 5:
What is the output of the Java code snippet?
int a=3, b=8;
boolean c = a > 5 && ++b > 6;
System.out.println(b);

Choose the correct answer from below:
8
9
6
Compilation Error

## Question 6:
Take three numbers from the user, i.e. n1, n2 and n3.
Now your target is Print the output in the following ways:
In the first line:  print "Number 1 is " then n1
In the second line: print "Number 2 is " then n2
In the third line:  print "Number 3 is " then n3
In the fourth line: print "(n1 < n2) condition is " then print boolean result of (n1 < n2).
In the fifth line:  print "(n2 == n3) condition is " then print boolean result of (n2 == n3).
In the sixth line:  print "(n1 < n2) && (n2 == n3) condition is " then print boolean result of (n1 < n2) && (n2 == n3).
Problem Constraints
-1000000 <= n1, n2, n3 <= 1000000
Input Format
The First line is an integer, n1
The Second line is an integer, n2
The Third line is an integer, n3
Output Format
Print the statement with Boolean results.
Example Input
Input 1 :
47
82
82
Input 2 :
14
78
98
Example Output
Output 1 :
Number 1 is 47
Number 2 is 82
Number 3 is 82
(n1 < n2) condition is true
(n2 == n3) condition is true
(n1 < n2) && (n2 == n3) condition is true
Output 2 :
Number 1 is 14
Number 2 is 78
Number 3 is 98
(n1 < n2) condition is true
(n2 == n3) condition is false
(n1 < n2) && (n2 == n3) condition is false
Example Explanation
Explanation 1 :
n1(47) is strictly smaller than n2(82) and n2(82) and n3(82) are equal
Explanation 2 :
n1(14) is strictly smaller than n2(78) but n2(78) and n3(98) are not equal

## Question 7:
Take three numbers from user, i.e. n1, n2 and n3.
Now your target is Print the output in following ways:
In first line : print "Number 1 is " then n1
In second line : print "Number 2 is " then n2
In third line : print "Number 3 is " then n3
In fourth line : print "(n1 > n2) condition is " then print boolean result of (n1 > n2).
In fifth line : print "(n2 <= n3) condition is " then print boolean result of (n2 <= n3).
In sixth line : print "(n1 < n2) || ((n2 == n3) && (n1 < n3)) condition is " then print boolean result of (n1 < n2) || ((n2 == n3) && (n1 < n3)).
Problem Constraints
-1000000 <= n1, n2, n3 <= 1000000
Input Format
First line is n1
Second line is n2
Third line is n3
Output Format
print the statement with boolean results
Example Input
Input 1 :
47
82
82
Input 2 :
14
78
98
Example Output
Output 1 :
Number 1 is 47
Number 2 is 82
Number 3 is 82
(n1 > n2) condition is false
(n2 <= n3) condition is true
(n1 < n2) || ((n2 == n3) && (n1 < n3)) condition is true
Output 2 :
Number 1 is 14
Number 2 is 78
Number 3 is 98
(n1 > n2) condition is false
(n2 <= n3) condition is true
(n1 < n2) || ((n2 == n3) && (n1 < n3)) condition is true
Example Explanation
Explanation 1 :
n1(47) is strictly smaller than n2(82) and n2(82) and n3(82) are equal
Explanation 2 :
n1(14) is strictly smaller than n2(78) but n2(78) and n3(98) are not equal