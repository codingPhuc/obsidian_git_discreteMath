bases on this video :[RECURRENCE RELATIONS - DISCRETE MATHEMATICS - YouTube](https://www.youtube.com/watch?v=eAaP4XaB8hM)
#sumarize 
 number in a sequence depend on the previous number
- fibonacci sequence and its formal definition An = An-1 + An-2 (A0=0 , A1=1) n >= 2 
- geometric progression An = 2An-1(A0 =3)

## formula
An - A(n-1) = K   , A0 =C  n>=1 
convert $a_n - a_{n-1} = k$ 
![[the resond why.PNG]]
to An = A0 + $\sum_{i=1}^{n} k$ 
example 
- given A0 = 0 
- n>=1 
- An -A(n-1) = 2n  
An = 0+ $\sum_{i=1}^{n} 2n$= 2$\sum_{i=1}^{n} n$ = 2 (n )(n+1) /2 



## sloving  re currence Relation 
we want an easy equation to find the value of any term 
[sloving the formula mean finding the formula $a_n =?$ ]
$a_n = 3a_{n-1}$
$a_0 = 7$  
-> $a_n = 7 *3^n$ 
another example 
$a_n - a_{n-1}= k /a_0 =c$ 
$a_n = C + \sum_{i=1}^{n}k$ 
### hard problem 
#### ex 1
$a_n - a_{n-1} - 6*a_{n-2} =0$ where $a_0 =1 , a_1=8$
$r^n - r^{n-1} - 6^{n-2}=0$
1. $r^2 - r^{} - 6^{}=0$ divide it by the $r^{r-2}$ 
For any base a and any integer exponents n and m, aⁿ⋅aᵐ=aⁿ⁺ᵐ. For any nonzero base, aⁿ/aᵐ=aⁿ⁻ᵐ. These are worked examples for using these properties with integer exponents.
2. (r-3)(r+2) =0  ( r= 3 , -2)
3. $a_n = \alpha*(3^n) + \beta* (-2)^n$
$a_0 = 1 = \alpha*(3^0) + \beta* (-2)^0 = \alpha + \beta$ 
$a_1 = 8 = \alpha*(3^1) + \beta* (-2)^1 = 3*\alpha + 2*\beta$ 
now slove for $\alpha , \beta , \alpha = 2 , \beta = -1$
we get => $a_n  = 2*(3^n) -1(-2)^n$ 
#### ex2 
$a_n - 4*a_{n-1} + 4*a_{n-2}=0, where, a_0=1, a_1 =3$
$r^n - 4*r^{n-1} + 4*r^{n-2}$
$r^2 - 4*r^{} + 4$ divide by the lowest number $r^{n-2}$
$(r-2)*(r-2)=0$ -> r=2,2
if we have similer root beta will have *n
$a_n = \alpha*(2^n) +\beta*n(2^n)$
$a_0 = 1  = \alpha$ 
$a_1 =3= 2\alpha + 2\beta$
-> $\alpha = 1 , \beta = \frac{1}{2}$ 
$a_n = 2^n + \frac{1}{2}n2^n$ 
#### important part 
so if you have a root that are different then 

![[different root.PNG]]
if you have the same root 
![[root same.PNG]]












	






