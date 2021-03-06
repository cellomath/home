---
title: "Meet-in-the-middle; Finite Fields"
output:
  html_document:
    toc: false
    df_print: paged
    theme: spacelab
---

Upload to Canvas a PDF scan of your work for problems 1-2. 

## Assignment: due Wednesday, 11:59 pm

1. Consider the meet-in-the-middle attack on Triple DES described in the [slides](../slides/07desaes1.html#/how-about-triple-des). Make the following calculations, showing work.
     a. Assuming that $m$ is a single block (64 bits), calculate the number of bytes that need to be stored in Step 3 of this attack. (Recall that 1 byte = 8 bits.) Give your answer in appropriate units (e.g., gigabytes, terabytes).
     b. Recall that the length of a DES key is 56 bits. Calculate the number of times the DES function needs to be executed ($D$ or $D^{-1}$).
     c. If your computer can crack Double DES in one day, approximately how long will it take to crack Triple DES? (Just consider the number of DES function calls, not the comparisons.) Give your answer in years.

2. Consider the field $F = \mathbb{Z}_2/(x^3+x+1)$.
     a. How many elements does $F$ have? List them (as polynomials).
     b. For each nonzero element you found in part (a), give its multiplicative inverse. (Note, in this field, using the standard abuse of notation, $1 = x^3 + x$, and $x^3 = x + 1$.)
