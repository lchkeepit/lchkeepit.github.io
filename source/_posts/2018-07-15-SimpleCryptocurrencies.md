---
title: Simple Cryptocurrencies
date: 2018-07-15 21:44:12
tags: 
- cryptocurrencies
- block chain
categories:
- Block Chain
- Simple Cryptocurrencies
---
## hash functions
- collision-free
  It is hard to find a *k2* has the same hash value as the given *k1*
- hide
  Given hash value H(k2), it is hard to get k2
- puzzle-friendly
  ..
## digital signature
- definition
  - sk(secret key), pk(public key)  = generate_random_keys
  - sig = mk_sig(msg, sk)
  - verify(sig, msg, pk) == true?
## Issues
- Double spending
- Decentralization