# Secure-Communicaion-using-QKD

The security of our critical infrastructure is threatened by the advent of future quantum computers, breaking asymmetric cryptography – an essential part of our secure communication architecture. Quantum key distribution (QKD) remedies this weakness by providing a long term secure solution, safe against attacks from quantum computers.

There are indeed many aspects to cryptography, and many different cryptographic tasks that one may consider. Likely the
first cryptographic task that comes to mind is private communication: Alice and Bob wish to
communicate, and they do not want an eavesdropper (Eve) to learn any information about their
communication. There are many other cryptographic tasks or protocols one may consider, such as
message authentication, digital signatures, and voting schemes. Often these tasks are broken down
into more primitive operations, such as bit-commitment and oblivious transfer.

Quantum key distribution
The aim of quantum key distribution is to allow Alice and Bob to generate a secure private key
that can be used for the one-time pad without having to meet privately. They will be able to
accomplish this task by using quantum information. There are a few different schemes for doing
this, and among them one  of them is:
BB84,which is Easy to implement, relatively hard to prove security.


For detailed explanation:
https://arxiv.org/ftp/arxiv/papers/1409/1409.1452.pdf
