---
title: "Polynomer og fraktaler"
draft: false
ShowToc: false
math: true
ShowReadingTime: false
summary: "Kael-Mikael Perfekt"
weight: 1
---

Ta for deg polynomet $f(z) = z^2 -2$. Vi kan tenke på det som en funksjon, som sender et punkt $z$ i det koplekse planet til et annet punkt $f(z)$. Gitt et punkt $z$ kan vi også studere iterasjonene $z, f(z), f(f(z)), f(f(f(z))), \ldots$. Dersom vi tar $z=0$ får vi for eksempel

- $f(0) = -2$, 
- $f^2(0) = f(-2) = 2$, 
- $f^3(0) = f(2) = 2$, etc... 

Det neste punktet i listen får vi alltid ved å bruke funksjonen $f$ på det forrige.

*Julia-mengden* til funksjonen $f$ består av alle punktene $z$ slik at disse iterasjonene forblir små, og ikke divergerer mot uendelig. For eksempekl er Julia-mengden til $f(z)=z^2-2$ relativt lett å regne ut: den er intervallet $[-2,2]$. For et hvert punkt utenfor dette intervallet vil punktene i listen tilslutt nærme seg uendelig. For eksempel, dersom $z=i$ får vi

- $f(i) = i^2 - 2 = -1 - 2 = -3$, 
- $f^2(i) = f(-3) = 7$, 
- $f^3(i) = f(7) = 47$, etc...

Noe veldig interessant skjer dersom vi bytter ut tallet $2$ i funksjonen $f(z)=z^2-2$ med et annet komplekst tall $c$. I motsetning til eksempelet over vil Julia-mengden til $f_c(z)=z^2-c$ typisk være en komplisert mengde med en såkalt *fraktal* struktur. 

I dette foredraget skal vi se nærmere på dette spennende fenomenet, og samspillet mellom polynomer og fraktaler. 

---

[Karl-Mikael Perfekt](https://kmperfekt.com/) is an associate professor in mathematics at NTNU. His research area is mathematical analysis, a branch of mathematics that deals with limits, approximations, quantities and inequalities.

<img src="images/fractal1.jpg#invert" alt="Error loading image" width="700"/>