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

