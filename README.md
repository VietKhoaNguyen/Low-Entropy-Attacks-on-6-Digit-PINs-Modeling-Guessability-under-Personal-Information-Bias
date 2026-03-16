# Project Overview

This project investigates the security of human-chosen 6-digit PINs under low-entropy attacks. Although a 6-digit PIN theoretically offers one million possible combinations, real users often select predictable patterns such as birthdays, repeated digits, or simple sequences. As a result, the effective security of PIN-based authentication may be significantly lower than the theoretical key space.

The goal of this project is to model how human bias and personal information influence PIN selection and to evaluate the effectiveness of different guessing strategies. A simulation framework will be developed to generate PIN datasets with various distributions and to simulate several attack models, including random guessing, frequency-ranked guessing, and pattern-based attacks.

The project evaluates PIN security using metrics such as entropy and top-k guess success rates. The results aim to provide insights into how user behavior and personal-information leakage affect the practical security of PIN systems.