# Acadgild_Assignment-3.1
Assignment 3.1
Define an m x n matrix of zeros and then enters a nested-for loop to fill the
locations of the matrix, only if the two indexes differ.
• The purpose is to create a lower triangular matrix, that is a matrix whose
elements below the main diagonal are non-zero, the others are left
untouched to their initialized zero value.
• When the indexes are equal (if condition in the inner loop, which runs over
j, the column index), a break is executed and the innermost loop is
interrupted with a direct jump to the instruction following the inner loop,
which is a print; then control gets to the outer for condition (over the
rows, index i), which is evaluated again.
• If the indexes differ, the assignment is performed and the counter is
incremented by 1.
• At the end, the program prints the counter ctr, which contains the
#number of elements that were assigned.

Answer: m=8, n=8
ctr=0 # used to count the assignment
x_mat = matrix(0,m,n)
x_mat
[,1] [,2] [,3] [,4] [,5] [,6] [,7] [,8]
[1,]    0    0    0    0    0    0    0    0
[2,]    0    0    0    0    0    0    0    0
[3,]    0    0    0    0    0    0    0    0
[4,]    0    0    0    0    0    0    0    0
[5,]    0    0    0    0    0    0    0    0
[6,]    0    0    0    0    0    0    0    0
[7,]    0    0    0    0    0    0    0    0
[8,]    0    0    0    0    0    0    0    0
> for(i in 1:n)
+ for(j in 1:m)
+ print(i+j)
[1] 2
[1] 3
[1] 4
[1] 5
[1] 6
[1] 7
[1] 8
[1] 9
[1] 3
[1] 4
[1] 5
[1] 6
[1] 7
[1] 8
[1] 9
[1] 10
[1] 4
[1] 5
[1] 6
[1] 7
[1] 8
[1] 9
[1] 10
[1] 11
[1] 5
[1] 6
[1] 7
[1] 8
[1] 9
[1] 10
[1] 11
[1] 12
[1] 6
[1] 7
[1] 8
[1] 9
[1] 10
[1] 11
[1] 12
[1] 13
[1] 7
[1] 8
[1] 9
[1] 10
[1] 11
[1] 12
[1] 13
[1] 14
[1] 8
[1] 9
[1] 10
[1] 11
[1] 12
[1] 13
[1] 14
[1] 15
[1] 9
[1] 10
[1] 11
[1] 12
[1] 13
[1] 14
[1] 15
[1] 16
ctr=ctr+1
> print(ctr)
[1] 1
