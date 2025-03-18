# Stacks-and-Queues-Activity-
# Cheyenne Awelewa


1.
PUSH(S,4): Insert 4 at S[1} because S.top is from 0 to 1. The so result is S[1]=4 S.top =1 

PUSH(S,1): Insert 1 at S[2] increment S.top from 1 to 2. This will result in S[1]=4 and S[2]=1

PUSH(S,3):  Insert 3 at S[3] from 2-3 so the result is s[1]=4. S[2]=1 and S[3] =3 

POP(S): Removes the element S[3] (the current top0, I.e. remove 3, and decrement S.top from 3-2 the result is S[1]=4 S[2]=1 S[3] is empty

PUSH(S,8): This will insert 8 at S[3] and the result is S[1]=4 S[2]=1 S[3]=8  S.top=3

POP(S): This operation will remove the element from S[3] and decrement S.top from 3 to 2. The result is S[1]=4 and S[2] =1 sp S.top =2 

2.
For ENQUEUE (Q,4) that will place 4 at Q[1]
For ENQUEUE (Q,1) that will place 1 at Q[2]
For ENQUEUE (Q,3) that will place 3 at Q[3]
For For DEQUEUE(Q) this is going too remove the element number 4 from Q[1]
For ENQUEUE (Q,8) this is going to place 8 at Q[4] 
For DEQUEUE(Q) this will remove Q[2] or 1.

3.

For overflow detection:
The code checks (tail +1) % MAX-SIZE == head. Before inserting an element. If the statement is true this will indicate of the queue is full. If it is full the overflow is thrown out. 




For underflow detection the code checks is head == tail is true before removing an element. If it is empty the error is not included

4.
The queue allows deletion and insertion in the beginning and in the end of an array. There are four time procedures. 
INSERT-LEFT (D,a) has to be inserted at the left
INSERT-RIGHT (D,a) has to be inserted at the right
DELETE-LEFT(D) has to be deleted from the left
DELETE-RIGHT (D) has to be deleted from the right

If we use two pointers D.left is for the left element
D.right is for the right element 

Reference:

https://mitpress.mit.edu/9780262533058/introduction-to-algorithms/
