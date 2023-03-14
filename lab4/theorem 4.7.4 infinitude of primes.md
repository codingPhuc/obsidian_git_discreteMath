
#sumarize 
	the set of primes is infinite 
proof 
1. supppose the set of promes is finite : a total of k primes 
2. the we may list all the primes : p1,p2,p3 , .... , p5 

## theorem 4.2.3 
if p is a prime and x1,x2 , ......,xn are any integers such that : 
	p|x1x2......xn 
then p |xi , for some xi (1 =< i =< n )

## theroem 4.3.5 unique prime factorzation 
given any integers n> 1 , there exist a positive integer k , distinct prime numbers p1 , p2 , ..... pk , and positive integers e1 ,e2 , ...... , ek such that 
n = p1 , p2 ,....., pk
and any other expression for n as a product of prime numbers is identical to this , except , perhaps m for the order in which the factors are written  
## proposiition 4.3.3 (Uniqueness of least element)
if a set of integers has a least element , then the least element is unique 

### proposition 4.3.4 (Uniqueness of gratest element)
if a set S of integers has a greates element , then the greatest element is unique 

theorem 4.4.1(Quotient-remainder theorem)
given any integer a and any positive integer b , there exist unique integer q and r such that : 
	a = bq + r and 0=< r < b 
the integer q is called the quotient , while r is called the remainder  
note the limit on r : r lies in the range 0 ,1 , 2, 

## 4.5 GREATES COMMON DIVISOR 
DEFINITION 4.5.1(GREATEST COMMON DIVISOR)
let a and b be integers , not both zero . The greatest common 
divisor of a and b , denoted gcd(a,b) m is the integer d satisfying : 
(i) d | a and d|b 
(ii) $\forall$ c thuộc Z if c | a and c |b then c =< d 

## code  euclid's algorithm for gcd 
def gcd 
