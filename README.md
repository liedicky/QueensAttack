# QueensAttack
Solution to Queen's Attack 2 problem from www.hackerrank.com

Function Description

Complete the queensAttack function in the editor below. It should return an integer that describes the number of squares the queen can attack.

queensAttack has the following parameters:

n: an integer, the number of rows and columns in the board
k: an integer, the number of obstacles on the board
r_q: integer, the row number of the queen's position
c_q: integer, the column number of the queen's position
obstacles: a two dimensional array of integers where each element is an array of integers, the row and column of an obstacle
Input Format

The first line contains two space-separated integers and , the length of the board's sides and the number of obstacles.

The next line contains two space-separated integers and , the queen's row and column position.

Each of the next lines contains two space-separated integers and , the row and column position of .

Constraints

A single cell may contain more than one obstacle.

There will never be an obstacle at the position where the queen is located.

Output Format

Print the number of squares that the queen can attack from position .

Sample Input 0

4 0

4 4

Sample Output 0

9

Sample Input 1

5 3

4 3

5 5

4 2

2 3

Sample Output 1

10

Sample Input 2

1 0

1 1

Sample Output 2

0

Explanation 2

Since there is only one square, and the queen is on it, the queen can move 0 squares.
