---
`1.`
``for(i=0; i <n, i ++){``
		``//do something``
   ``}``
``f(n)= O(n)``
			`==OR==`

   `for(i=0; i <n, i --){```
		```//do something```
   ``}``
``f(n)= O(n)``

			`==OR==`
				
``for(i=0; i <n, i +2){``
		``//do something``
   ``}``
`$`f(n)= O(n)`$`

`2.`
``for(i=0; i <n, i ++){``
		``for(j=0; j<n, j ++){``
		``//do something``
		``}`
   ``}``
`$`f(n)= O(n^2)`$`

`3.`
``for(i=0; i <n, i ++){``
		``for(j=0; j<i, j ++){``
		``//do something``
		``}`
   ``}``
`$`f(n)= O(n^2)`$`

`4.`
``p=0;``
``for(i=1; p <=n, i ++){``
		``p=p+i;``
   ``}``
`$`f(n)= O(√n )`$`

`5.`
``for(i=0; i <n, i*2){``
		``//do something``
   ``}``
`$`f(n)= O(logn base 2)`$`
`NOTE: we need to take the seal(round) value for log` 

`6.`
``for(i=n; i >=n, i=i/2){``
		``//do something``
   ``}``
`$`f(n)= O(logn base 2)`$`
`NOTE: we need to take the seal(round) value for log` 

`7.`
``for(i=0; i*i < n, i ++){``
		`//do me a favour;``
   ``}``
`$`f(n)= O(√n )`$`

`8.`
``for(i=0; i <n, i ++){``
``//do something``
`}`
``for(j=0; j<i, j ++){``
`//do something``
`}`
   ```
`$`f(n)= O(n)`$`

`9.`
``for(i=1; i <n, i=i*2){``
``p++;`
`}`
``for(j=1; j<p, j=j*2){``
`//do something``
`}`
   ```
$f(n)= O(loglogn)$

`10.`
``for(i=0; i <n, i ++){``
``for(j=0; j<n, j*2){``
`//do something``
`}`
`}`
   ```
`$`f(n)= O(nlogn)`$`

**Summary:-**
**for(i = 0;i <n;i++)------ o(n)**
**for(i = 0;i <n;i=i+2)------ o(n)**
**for(i = n;i>1;i--)------ o(n)**
**for(i = 1;i <n;i=i*2)------ o(lognbase2)**
**for(i = 1;i <n;i=i*3)------ o(lognbase3)**
**for(i = n;i>1;i=i/2)------ o(lognbase2)**

















