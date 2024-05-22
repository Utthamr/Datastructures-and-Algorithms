
**very important topic**

(O)- big oh (upper bound)
(Ω)-big -omega (lower bound)
(θ)- theta  (Average bound)



**BIG-OH**
The function f(n)=O(g(n)) if there exists positive constants c and n0 such that f(n)<= c * g(n) for all n >= n0

**EXAMPLE**  - f(n)= 2n+3
2n + 3 <= 10 n
**f(n)= O(n)**

simple method to get C X *g(n) is 
write the same function on the other side in terms of n 
**EXAMPLE**  - f(n)= 2n+3
2n + 3 <= 2n+3n
2n+3 <= 5n for (n>=1)
2n +3  <= c x n (we know the condition f(n)<=c x g(n))
so (g(n)=n)
f(n)= O(g(n))
**f(n)= O(n)**
NOTE:- all upper bounds like f(n)= O(nlogn) are also correct but nearest one is useful.

**OMEGA**
The function f(n)=Ω(g(n)) if there exists positive constants c and n0 such that f(n)>= c * g(n) for all n >= n0
**EXAMPLE**  - f(n)= 2n+3
2n + 3 >= 1*n
**f(n)= Ω(n)**

**NOTE:- all lower bounds like f(n)= Ω(log n) are also correct but nearest one is useful.**

**THETA**
The function f(n)=θ(g(n)) if there exists positive constants C1,C2 and n0 such that **c1*g(n)<= f(n)<= c2 * g(n)** for all n >= n0

**EXAMPLE**  :- f(n)= 2n+3
1n<=2n + 3 <= 5 n
 **c1*g(n)<= f(n)<= c2 * g(n)**
 
**f(n)= θ(n)**
**NOTE:- we cannot write lower bound values or upper bound values because its average bound ,so it should exactly be f(n)= θ(n).**

**Always theta is preferable if you can find it.**
**Go for big o and omega if you cannot find theta (which is exact value).**











