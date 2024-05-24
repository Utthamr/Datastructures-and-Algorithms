LINEAR SEARCH 

| 8   | 6   | 12  | 9   | 5   | 18  | 7   | 4   | 16  | 3   |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   |

**BEST CASE** 
searching key element present at first index.
**BEST CASE TIME** 
constant time 
which can be written as O(1)
==B(n) = O(1)==  or ==B(n) = Ω(1)== or ==B(n) = θ (1)

**WORST CASE** 
searching key element present at last index.
**WORST CASE TIME**
==W(n)=O(n)====== or ==W(n)=Ω(n)====== or ==W(n)=θ(n)======



**AVERAGE CASE**
$all possible case time / no. of cases$

rarely used and mostly the time we get for the average case is almost similar to worst case , so we mostly try to find worst case .

==A(n)= n+1/2==

**BINARY SEARCH TREE** 
![[Pasted image 20240522134039.png]]
**BEST CASE** 
searching root element(3 or10).
**BEST CASE TIME** 
constant time 
which can be written as O(1)
==B(n) = O(1)==  or ==B(n) = Ω(1)== or ==B(n) = θ (1)

**WORST CASE** 
searching leaf element present (4 or 7 or 13).
**WORST CASE TIME**
==W(n)=HEIGHT OF THE TREE=======  FOR ALL THREE NOTATIONS
**MIN WORST CASE TIME** 
min w(n) = logn

**MAX WORST CASE TIME** 
max w(n) = n


NOTE : **TIME TAKEN IS ALWAYS DEPENDED ON THE  HEIGHT OF THE TREE**.

NOTE : **THE  HEIGHT OF THE TREE MIN IS LOG N AND MAX IS N** 

Sorting
Algorithm	                                  Complexity	                                       Max value of N possible
Bubble sort, insertion sort	                O(n^2)
Merge sort                                  O(NlogN)


