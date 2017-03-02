# what is a secure password?

Referenced URL [Pope Kim's Youtube](https://www.youtube.com/watch?v=_5bkFRwSfFQ)

Let's started about **brute-force attack**. In cryptography, a brute-force attack consists of an attacker trying many passwords or passphrases with the hope of eventually guessing correctly. The attacker systematically checks all possible passwords and passphrases until the correct one is found.

Most of site provide secure password checking system. But that's NOT currectly. Then, How we SECURE password from brute-force attack? 

Let's assume. *Power Computer*( 1pc + 25 GPU ) can guess 350 Billion / sec.

|Num|Kinds|Secure|Convenience|
|:----|:----|:----:|:----:|
|1.|PIN(4 numbers)| X | O |
|2.|Alphabet(8-digits)| X | O |
|3.|Alpha + Number + Special Char| X | V |
|4.|Two Factor Authentication| V | X |
|5.|Biometric Authentication| O | O |

 1. PIN (4 numbers)  
  No security.

 2. Alpha (assume 8-digits)  
  52^8 = 53,000 B (The *Power Computer* can break in 151 sec.)

 3. Alpha + Num + Special Char (assume 8-digits)  
  62^8 = 218.000 B (The *Power Computer* can break in 600 sec.) And there is a pattern.  

 4. 2FA  
  If you are a target, it is not safe.

 5. BIO  
  Very Secure. **BUT**, If (fingerprint, Iris) scanned and stored data is not stored properly, maybe stolen. Once your info is stolen, you can not use it again. **because it can not be reset.**

Then, What is a secure password? Here is a simple way.

```
password = YouAreSuchALittleTurkey
```

You can use the sentence in your head(mind). There is No pattern. 52 characters ^ 23 (sentence length) = 2 * 10^39 = 266 * 10^18 years. This way is convenience and also very secure.

And in the near future, there will be more and more Super Computer. How to prepare brute-force Attack? There is also a simple way. If wrong password entered, delay few minutes or few hours.
