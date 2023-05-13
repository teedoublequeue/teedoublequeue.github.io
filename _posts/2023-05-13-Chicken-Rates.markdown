---
layout: post
title:  "Confusing Rates"
date:   2023-05-13
categories: quant-interview-questions
---

# Confusing Rates

Suppose that $1.5$ chickens can produce $1.5$ eggs in $1.5$ days. How many eggs do 9 chickens produce in $9$ days?

**Solution** The important thing is to not say $9$ just because it jibes with the given pattern...

To simplify things, let's assume we know that a single chicken produces $n$ eggs in a single day. Then the answer to the question is $81n$. That is because a single chicken produces $9n$ eggs over $9$ days by producing $n$ each day. Then $9$ chickens produce $9\cdot 9n=81n$ eggs by producing $9n$ per chicken over the $9$ days.

To get $n$, we work in reverse and scale the $1.5$(s) down. If the $1.5$ chickens only worked for 1 day, they would produce $1$ egg. That is because they reduced their work time to $\frac{2}{3}$ of the time it takes to produce $1.5$ eggs, so they can only produce $\frac{2}{3}\cdot1.5=1$ egg in $1$ day. Similarly if we then reduce the number of chickens to $1$, they can only produce $\frac{2}{3}$ of an egg since we've reduced their workforce by $\frac{2}{3}$.

Thus, $n=\frac{2}{3}$ and the answer is $81\cdot{2}{3}=54$ eggs.
