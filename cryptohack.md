
### General:
**1. XOR:**
- ***Favorite byte***: The flag character by character is xored with a single byte. To find the hidden byte, you can use the flag format of ```crypto{``` .
- ***You either know, XOR you don't***: It is quite similar to the ***Favorite byte*** challenge as you can find the key with the flag format. It won't give you the complete key, but your brain will tell you all :D.
- ***Lemur  XOR***: This seems to be a hard challenge at first. Take a look at the XOR Properties and think how to clear out the key. ```m1 = p1 XOR key. m2 = p2 XOR key```. So what if ```m1 XOR m2```?
**2. Mathemetics:**
- ***Greatest Common Divisor***: You can use the gmpy2 package to solve this chall.
- ***Extended GCD***: As p, q are prime, gcd(p,q) = 1. You should build a Python implementation of Extended Euclidean algorithm with [this pseudocode](https://en.wikipedia.org/wiki/Extended_Euclidean_algorithm#Pseudocode).
- ***Modular Inverting***: The Fermat's little theorem said that $e^{i\pi} + 1

**3. Data Format:*
### Mathematics:
