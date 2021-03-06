# Educational Crypto in Python

This repo is for learning various cryptographic concepts and techniques.

# RSA

| File | Technique | Applicable CTF Challenges |
|------|-----------|---------------------------|
| [modular_arithmetic.py](modular_arithmetic.py) | Introduction to modular arithmetic | |
| [rsa.py](rsa.py) | Introduction to RSA encryption | |
| [rsa_exponentfault.py](rsa_exponentfault.py) | Recover the secret exponent when unpadded RSA (non-CRT) is used and random bitflips affect the secret exponent |[Broken box - CSAW quals 2016](https://ctftime.org/task/2825]) |
| [rsa_broadcast_attack.py](rsa_broadcast_attack.py) | Recover a secret message if it is encrypted with low-exponent, unpadded RSA and it is encrypted using different moduli |[CRYPTONET - Hack You CTF 2014](http://v0ids3curity.blogspot.it/2014/01/hack-you-ctf-2014-crypto-400-cryptonet.html) |

# Elliptic Curve
...

# AES
...

# ...


Have a good example?
Add it here!
Try to inline the whole technique in a single `.py` -- it's a lot easier to learn that way.


# Other resources

### General Resources

- This is an online book that introduces many concepts of cryptography: [Cryptography, An Introduction](https://www.cs.bris.ac.uk/~nigel/Crypto_Book/).

### RSA

[Twenty Years of Attacks on the RSA Cryptosystem](https://crypto.stanford.edu/~dabo/papers/RSA-survey.pdf)
