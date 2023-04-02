# what is a modulo 
the result of a the remainder after subtraction 
example 
5 mod 3 = 2 
6 mod 3 =0 
7.1 mod 3 =1.1 
# the Euclidean algorithm 
let say that we want to find an inverse 27^-1(mod 392)
we have this formula : 
	392= [27] * (14) + [(392- 27 * 14 )]
	with 14 being the number of time 392 divide 27 ie : 392/27 
	then we move each number to the right braket number to left
	27 = 14 * 1 + 13 
	and so on 
	14= 13 * 1 +1
## RSA encrytion algorithms 
encryption : (5,14) 
we need this pair of number it is a lock 
exp : send "B"tranform it into number 2 
2^5 (mod 14) = 32(mod 14)
					= 4 (mod 14) get the remainder of the number 32
ciphertext : D 
decryption:(11,14)
4^11 (mod 14)= 4194304(mod 14)
					= 299593.1429... ( take note of the integer part of the number )
					subtract the integer part of the number 
					= you will be left with a decimal ie : 0.1429 
					multiple the number with mode 14 
					= 1.999
					round it up we will have 2 which is the text "B"
## how does rsa work 
1. first you need to pick two prime number 
2. come up with a number that is a product of both the prime    number above let call it N, N became the mod in public and private key 
3. list out all the number  that have a common factor with N 
4. $\phi$(N) = 

![[Pasted image 20230402085839.png]]





