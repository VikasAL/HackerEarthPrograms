# Micro and Array Update
 Micro purchased an array A having N integer values. After playing it for a while, he got bored of it and decided to update value of its element. In one second he can increase value of each array element by 1. He wants each array element's value to become greater than or equal to K. Please help Micro to find out the minimum amount of time it will take, for him to do so.

Input:
First line consists of a single integer, T, denoting the number of test cases.
First line of each test case consists of two space separated integers denoting N and K.
Second line of each test case consists of N space separated integers denoting the array A.

Output:
For each test case, print the minimum time in which all array elements will become greater than or equal to K. Print a new line after each test case.

Constraints:


SAMPLE INPUT

2
3 4
1 2 5
3 2
2 5 5

SAMPLE OUTPUT

3
0

# Hamiltanion and Lagrangian

Students have become secret admirers of SEGP. They find the course exciting and the 
professors amusing. After a superb Mid Semester examination, it’s now time for the 
results. The TAs have released the marks of students in the form of an array, where arr[i] 
represents the marks of the ith student.
Since you are a curious kid, you want to find all the marks that are not smaller than those 
on its right side in the array.
Input Format
The first line of input will contain a single integer n denoting the number of students.
The next line will contain n space separated integers representing the marks of students.
Output Format
Output all the integers separated in the array from left to right that are not smaller than 
those on its right side.
Constraints
1 <= n <= 1000000
0 <= arr[i] <= 10000

SAMPLE INPUT
6
16 17 4 3 5 2

SAMPLE OUTPUT
17 5 2

# Monk watching Fight

Once Monk was watching a fight between an array and a tree, of being better. Tree got frustrated and converted that array into a Binary Search Tree by inserting the elements as nodes in BST, processing elements in the given order in the array. Now Monk wants to know the height of the created Binary Search Tree.

Help Monk for the same.

Note:

1) In Binary Search Tree, the left sub-tree contains only nodes with values less than or equal to the parent node; the right sub-tree contains only nodes with values greater than the parent node.

2) Binary Search Tree with one node, has height equal to 1.

Input Format :

The first line will consist of 1 integer N, denoting the number of elements in the array.
In next line, there will be N space separated integers,  , where , denoting the elements of array.

Output Format

Print the height of the created Binary Search Tree.

Constraints: :



SAMPLE INPUT 
4
2 1 3 4
SAMPLE OUTPUT 
3
Explanation
.

Insert 2. It becomes root of the tree.
Insert 1. It becomes left child of 2.
Insert 3. It becomes right child of 2.
Insert 4. It becomes right child of 3.
Final height of tree = 3.

# Frustrated coders
There are N frustrated coders standing in a circle with a gun in their hands. Each coder
has a skill value S[ i ] and he can only kill those coders that have strictly less skill than
him. One more thing, all the guns have only 1 bullet. This roulette can take place in
any random order. Fortunately, you have the time stone (haaan wo harre wala) and
you can see all possible outcomes of this scenario. Find the outcome where the total
sum of the remaining coder's skill is minimum. Print this sum.
Input Format
The first line contains N the no. of coders
The next line contains N elements where the ith element is theS[ i ] of ith coder.
Output Format
Print a single line containing the minimum sum.

Constraints
1<= N <= 1000000
1<=S[ i ]<=1000
sample input
6
1 7 2 2 4 4

sample output
11

# Pink Floyd and Happiness

Pink is sad because of some reasons, he wants to cheer up by listening to some songs
from his favorite band, Pink Floyd.
There are N records and Pink will be happy if he listens to them in the ascending
order, i.e., first the song No. 1, then No.2 and so on (He has to listen to all the N songs
to become Happy).
Pink is delivered his records in some given order, he can either add the record to the
Playlist in the delivered order or put some on another table. After being put on the
table only the topmost record can be added to the playlist at any time.
Print whether Pink will be sad or happy after the delivery of the records.
Input Format
N - Number of records followed by
N numbers- order of records.
Output Format
Print "Happy" if the playlist has songs from 1 to N in order else "Sad".

Constraints
1<=N<=10^5
The array consists of 1-N distinct numbers.

Sample input
5
1 2 4 3 5 
Sampe output
Happy

# Yatin plays PUBG
Yatin is playing PUBG and he has reached a place with a large staircase in front of him.
And there is an enemy at each landing of the staircase.
The staircase is analogous to a binary tree with each of its nodes as a landing of the
staircase and each of its edges as stairs from one landing to another.

Yatin wants to kill the maximum possible number of enemies. He can kill every person
he can see from his position with his suppressed sniper gun. But he can see only the
persons at the leftmost standing at each level and cannot see the rest.
Before starting shooting them, he wants to know how many persons he can kill. He is
busy keeping an eye on the enemies. So he wants you to find out the maximum
number of people he can kill from that location by providing you with the analogous
a binary search tree.

[ Note: Players do not change their position after one player has died, i.e. the leftmost
node remains the same even after player on that node has died. Or we can say that
the nodes are not removed after the player on that node has died.]

Input Format

The first line of input contains a number t denoting the number of test cases.
The first line of each test case contains n, the number of nodes in the tree.
The second line of each test case contains n space separated integers (unique) ai
denoting the value at each node of the BST.

Output Format

Print the answer for each test case on a new line.

Constraints
1 <= t <= 20
1 <= n <= 1000
1 <= ai <= 1000000000

SAMPLE INPUT
1
9
8 3 10 1 6 14 4 7 13

SAMPLE OUTPUT
4
