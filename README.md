
This repository contains the artifact related to the corresponding article.

## Prerequisites

The following material requires:

* SageMaths >= 9.5

## Description

Part of the functions and some of the syntax are taken from the Article "Loop-Abort Faults on Lattice-Based Fiat–Shamir and Hash-and-Sign Signatures"(https://eprint.iacr.org/2016/449)

The notebook attack.ipynb proposes three versions of the attack presented in the paper:

-The first function ‘attack_single_sig’ generates a signature made with a random y whose d highest degree coefficients are zero, then finds the key from this single signature.

-The second function ‘attack_two_sig’, generates two signatures made with random y whose d coefficients of higher degrees are zero, then finds the key from these two signatures.

-The third and last function ‘attack_many_sig’, generates m signatures made with nonces where each of the highest degree coefficient is zero, then finds the key from these signatures.
