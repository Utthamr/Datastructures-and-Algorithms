 General Properties :
*1.**if f(n) is O(g(n)) then a * f(n) is also O(g(n))**
2.**if f(n) is Ω(g(n)) then a * f(n) is also Ω(g(n))**
3.**if f(n) is θ(g(n)) then a * f(n) is also θ(g(n))**


Eg: $f(n)=2n^2+5 is O(n^2) then 7*f(n)=7(2n^2+5)$
is also $***O(n^2)***$
same for omega and theta also.

**Reflixive** **property** :
if f(n) is given then f(n) = O(f(n))

Eg: $f(n)=n^2$
    $f(n) = O(g(n))$
    $f(n)=O(n^2)$ 
    we know $n^2$ is nothing but f(n).  

**Transitive property:**
1.if f(n) is O(g(n)) and  g(n) is O(h(n)) then f(n) is O(h(n)).
2..if f(n) is Ω(g(n)) and  g(n) is Ω(h(n)) then f(n) is Ω(h(n)).
3..if f(n) is θ(g(n)) and  g(n) is θ(h(n)) then f(n) is θ(h(n)).

Eg: $f(n) = n$  , $g(n) = n^2$ , $h(n)=n^3$
n is $O(n^2)$ and $n^2$ is $O(n^3)$ then n is $O(n^3)$
same for omega and theta also.

**Symmetric** **property**:

if f(n) is θ(g(n)) then  g(n) is θ(f(n))

Eg: $f(n) = n^2$  and $g(n)=n^2$
f$(n) = θ(n^2)$
$g(n)=θ(n^2)$

Note: only true for theta 

**Transpose symmetric property:**

if f(n)=O(g(n)) then g(n) is Ω(f(n))

Eg: $f(n)=n$ , $g(n)=n^2$
then n is $O(n^2)$ and $n^2$ is Ω(n)

Note: only true for big O and omega

**Important properties:
*1.if f(n)=O(g(n))*
*and f(n)= Ω(g(n)) then f(n)=θ(g(n))*

$c1(g(n)) <= f(n) <= c2(g(n))$

2.*if f(n)=O(g(n)) and d(n)=O(e(n)) then f(n)+d(n) = O(max(g(n),e(n)))*****


Example:
$f(n) = n ; O(n)$
$d(n)=n^2=O(n^2)$
$f(n)+d(n)=n^2 +n =O(n^2)$

3.*if f(n)=O(g(n)) and d(n)=O(e(n)) then f(n)*d(n) = O(g(n)*e(n))*****


Example:
$f(n) = n ; O(n)$
$d(n)=n^2=O(n^2)$
$f(n)*d(n)=n^2 *n =O(n^3)$


 