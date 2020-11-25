
### General:
**1. XOR:**
- ***Favorite byte***: The flag character by character is xored with a single byte. To find the hidden byte, you can use the flag format of ```crypto{``` .
- ***You either know, XOR you don't***: It is quite similar to the ***Favorite byte*** challenge as you can find the key with the flag format. It won't give you the complete key, but your brain will tell you all :D.
- ***Lemur  XOR***: This seems to be a hard challenge at first. Take a look at the XOR Properties and think how to clear out the key. ```m1 = p1 XOR key. m2 = p2 XOR key```. So what if ```m1 XOR m2```? \

**2. Mathemetics:**
- ***Greatest Common Divisor***: You can use the gmpy2 package to solve this chall.
- ***Extended GCD***: As p, q are prime, gcd(p,q) = 1. You should build a Python implementation of Extended Euclidean algorithm with [this pseudocode](https://en.wikipedia.org/wiki/Extended_Euclidean_algorithm#Pseudocode).
- ***Modular Inverting***: The Fermat's little theorem said that ` a^p ≡ a mod p `. So what if we multiply both sides with `a^-1`. A little more math will take you to the flag.

**3. Data Format:**
- ***Transparency***: I want to give hints for this chall because at the time I write this, it has less than 400 solves. A small (I don't know, maybe big) hint is to find the subdomain of `cryptohack.org`

### Mathematics:
coming soon~~
