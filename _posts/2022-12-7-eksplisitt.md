---
layout: post
title: Hvorledes finner vi en rekursiv formel for en rekke?
date: 2022-12-07
author: Simon 
category: matematikk 
---
La oss se på noen rekker.

Den aritmetiske rekken på eksplisitt form er, 

$$a_n = a_1 + (n - 1)d$$ 

For $$ n + 1 $$,

$$a_{n + 1} = a_1 + (n + 1 - 1)d = a_1 + nd$$

Fra den aritmetiske rekken så har vi, 

$$ a_n = a_1 + nd - d = a_{n + 1} + d$$ 

Vi får,

$$a_{n + 1} = a_n + d \, \blacksquare$$

Som var det vi skulle bevise!

Det gjelder også for en geometrisk rekke; den geometriske rekken på eksplisitt form er, 

$$a_n = a_1k^{n-1}$$

For $$ n + 1 $$, 

$$ a_{n + 1} = a_1k^{n} $$

Fra den geometriske rekken, så har vi, 

$$a_n = a_1k^{n-1} = a_1k^nk^{-1}$$

$$ a_n = \frac{a_{n+1}}{k}$$

$$ a_{n+1} = a_nk \, \blacksquare$$

Og en harmonisk rekke!

$$\sum_{n = 1}^{\infty} \frac{1}{n}$$

$$a_n = \frac{1}{n}$$

$$ a_{n + 1} = \frac{1}{n + 1}$$

$$a_nn = 1$$

$$ a_{n + 1} = \frac{a_nn}{n + 1} \, \blacksquare$$
