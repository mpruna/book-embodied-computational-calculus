Dual hash
=========

  -------------- ----------------------
  **Created:**   *12/8/2019 7:05 AM*
  **Updated:**   *12/26/2019 4:20 AM*
  **Author:**    *Bogdan Bocse*
  -------------- ----------------------

\

\

\

\

19275dbf741b5f9c2cdd70b605e99187a03af4d3320416af2ebbb07dac42f1c489ac64e6aa568ec807b0b4134d8f546f6942529702881ab7f0b43d667268ea3d

sha512

\

627bb4c115a8fd35be59d13b55bceeb1536dc297ee7ca0d4f805c956e54307a5

sha256

\

A, B, C agree on a contract and want to sign it

they all apply their avatar A private keys to digest and encrypt the
contract,

on each of several encodings or languages E1, E2, E3

(A-\>a1) signs E1

(A-\>a1) signs E2

(A-\>a1) signs E3

(B-\>b1) signs E1

(B-\>b1) signs E2

(B-\>b1) signs E3

(C-\>c1) signs E1

(C-\>c1) signs E2

(C-\>c1) signs E3

\

Each signatary may also append a secret key to the hash (passwords ,
biometric signatures, seed-key for a predefined random number generator)

These secrets may be later revealed to a trusted executor, to provide
proof of identity.

\

\|signataries\| \* \|encodings\|

\

Additionally, the signature can be done by circulation.

\

The opener/proposer: (A-\>a1) signs (E1 + nonce1) -\> (signature1,
nonce1)

(B-\>b1) signs (E1 + signature1 + nonce2) -\> (signature2, nonce2)

(C-\>c1) signs (E1 + signature2) -\> (signature3, nonce3)

The closer/concealment (A-\>a1) signs (E1 + signature3) -\> final
signature

\

The final signature is timestamped, nonced and published as the value
assigned to the timestamped key of the contract (time+digest).

This key-value proof is published on IPFS or

\

\_Boxing\_  the following components:

\* the measurement instrument source which outputs to

\* a memory buffer which is only writeable by the instrument

\* an random number generator which can only be commanded by the
cryptographic processor,

\* storage for the identified private keys generated from the random
number and

\* the cryptographic processor which can only be used to generate new
keys, sign the buffer with old ones

\* a clock

\* a mechanism to synchronize to an external pre-trusted clock

\

 
