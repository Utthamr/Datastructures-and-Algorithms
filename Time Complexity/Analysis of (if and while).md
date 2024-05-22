1.
i=0;
while(i<n){
	//do
	i++;
}
f(n)=o(n)

2.
a=1;
while(a<b){
	//do
	a=a X *2;
}
f(n)=o(lognbase2)

3.
i=n;
while(i>1){
	//do
	i=i/2;
}
f(n)=o(lognbase2)

4.
i=1;
k=1;
while(k<n){
	//do
	 k=k+i;
	 i++;
}
f(n)=o(√n)

5.
`while(m!=n){`
	`if(m>n){`
		`m=m-n;`
	`}``else{`
		`n=n-m;`
	`}`
`}``
f(n)=o(n)-max , o(1)-min

6.
`Algorithm Test(n){`
	`if(n<5){`
		`printf("%d",n);`
	`}``else{`
		`for(i=0;i<n;i++){`
		`printf("%d",i);`
		`}`
	`}`
`}``
best case - O(1)
worst case - O(n)

*Note:- dont always think if there is a condition there must be a best case and worst case . it is not necessary at all.*

7.
`Algorithm Test(n){`
	`if(n<5){`
		`printf("%d",n);`
	
		`for(i=0;i<n;i++){`
		`printf("%d",i);`
		`}`
	`}`
`}``
f(n)=o(n)
we can see there is no best case or worst case here, if n <5 it will execute n times.






`
