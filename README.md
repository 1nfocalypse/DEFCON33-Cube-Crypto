<p align="center">
  <a href="https://github.com/1nfocalypse/DEFCON33-Cube-Crypto">
	<img alt="Cube" src="https://defcon.org/images/defcon-33/logos/contests/cnt-questioncube.webp"/>
  </a>
</p>
<p align="center">
  <a href="https://choosealicense.com/licenses/CC-BY-SA-4.0/">
  	<img alt="License: CC-BY-SA-4.0" src="https://img.shields.io/github/license/1nfocalypse/DEFCON33-Cube-Crypto"/>
  </a>
</p>
<h2 align="center">DEFCON 33's "? Cube" - Modern Cryptography Track Writeup</h2>
<h3 align="center">
  A Post-Mortem on the Modern Cryptography Challenges of a Black Badge CTF
</h3>
<p align="center">
  By <a href="https://github.com/1nfocalypse">1nfocalypse</a>
</p>

## What is this?
This is an overview and guide to the modern cryptography challenges presented in the ? Cube CTF at DEFCON 33. While source, tooling, and flags are retained, this writeup discusses the motivation behind each challenge,
why each challenge was selected, and how it was supposed to be solved. For those unfamiliar with DEFCON culture, multiple contests are held throughout the conference, and at the end, The Dark Tangent, or DT, selects
some of them. Nobody quite knows how his mind works, but usually, the selected contests are difficult or culturally relevant to the conference. Those who win them are awarded a "black badge", which grants lifetime
free access to the conference. No small thing!

## Overview
- Challenge 1: Taking Candy From the Crib - an exercise in breaking a weak stream cipher using a LCG for a keystream via cribdragging and Marsaglia's Theorem.
- Challenge 2: Friendly Primes - a Fermat Factorization challenge for RSA-4096.
- Challenge 3: Hasty Handshakes - a textbook Hastad's Broadcast Attack challenge.
- Challenge 4: Cracking Crypto Like the NSA - a curve25519-based implementation of DUAL_EC_DRBG, requiring use of the backdoor to obtain the flag.
- Challenge 5: Move Over - the MOV attack on a custom-generated elliptic curve of embedding degree 1. 

## Who is this for?
These challenges were originally developed for DEFCON 33's ? Cube CTF. The writeup is intended to help explain the motivations for each challenge from the designer's
point of view, as well as educate regarding each challenge so those curious and players (hopefully) learn something.

Past that, it may be useful to those looking for an applied lens into some of these topics, CTF players, and those curious about making crypto CTF challenges.

## Further Reading and References
Provided in the writeup!

## Greetz and Thank You's
Greetz:
- [The Algebraists Anonymous](https://aamath.org)
- DC702

Thank You's:
- cookies & aj
- The rest of the cube designers
- The players
- DEFCON
- CPV 12 for letting me yap about crypto
