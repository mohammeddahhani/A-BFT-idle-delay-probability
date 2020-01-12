# Intorduction:

This repository contains a mathematical model to compute the probability distribution of the number of A-BFT periods before
an IEEE 802.11ad station enters idle state.

# Features:

- First we find the distribution of the number of attempts until a given slot of the A-BFT period
- We then deduce the distribution of the number of attempts in an A-BFT period.
- We extend the last step to find the distribution of the number of attempts in k periods.
- The probability that `k` periods later the station enters idle state is equal to the probability a station reaches `MaxAttempts`
after `k` periods since the last time it was active.

# Requires:

A working installation of `python3` and `numpy` module are required.

# Related:

Success probability distribution in an A-BFT with `n` stations and `ns` slots per period.

Average success delay of a station in the A-BFT.
