# Return to the Hundred Acre Woods
### what I've learnt in 3 years
### _or_
### 3eeyore5u

---

# `finger lojikil` 

```
[lojikil.com]
Stefan Edwards (lojikil) is not presently logged in.

- Assurance Practice Lead, Trail of Bits
- Twitter/GitHub/Lobste.rs: lojikil
- Works in: Defense, FinTech, Blockchain, IoT, compilers,
vCISO services
- Previous: net, web, adversary sim, &c.
- Infosec philosopher, professional programming
language theorist, everyday agronomer, father.

WARNING: DEAF
WARNING: Noo Yawk
```

---

# in 2016 I gave this talk
![intro](intro.png)

<!--
probably one of my favorite talks ever;

Covered nihilism, security, everything that I saw as wrong in the IT/IS

page_number: true
footer: Return to the Hundred Acre Woods :: lojikil
-->

---

# this talk

- cover what I've seen going from traditional infosec to high(er) assurance work
- talk about application of formal techniques & cryptography
- why none of this will save you, I'm still Eeyore


![nVeeyore](nVeeyore-small.png) `=>` ![ToBeeyore-small.png](ToBeeyore-small.png)

---

<!--

talk about the areas I had covered previously, and lay out why they 
are still issues now
-->

# take aways

1. TINSTAAFL: formal tools & cryptography aren't panaceas 
2. There is no golden road to ~~arithmetic~~ security
3. Formally proven code fails, fancy crypto breaks

---

# me: 2016 vs 2019

## 2016
- OSINT, threat modeling, blackbox, web, net, lots of gov, finance

## 2019
- those + formalisms, PLT, more exposure to fancy crypto

---

![Nihilism then and now](nihilism.png)

<!-- as you can see, a lot has changed, even if not everything
has changed.

Life has more color now... even if it's meaningless...
-->

---

# formal tools won't save you

2016

- Java: Java Modeling Language (JML)
- C: Frama-C
- [fancy formal languages no one uses] : [fancy formal tools no one uses]
  - Eiffel, Sather, Lissac, any other DBC language there
  - TLA+, ACL2, &c were also alive
  - Ada has been around since forever

---

# formal tools won't save you

- tools were verbose
- often unused, difficult to use, or unknown

<!-- seriously, how many people *know* what JML is? -->

---

# a formal aside

- JML is > 20 years old (first specs & such from 1999)
- Multiple compiler support
- industry standard...
- ... with large, longitudinal case studies...
- ... virtually unused

---

# formal in 2019

- regularly interact with formal tooling
- since joining ToB, have written two, one for a client
- ease of use has gotten better
  - in Ethereum, there are *many* to chose from
- tend to lean towards ease of use vs specificity
  - lots of verifiers, less specifiers
  - more built in tests

<!--

- maybe talk about specification vs verification
- talk about the types of things we see tested...

-->

---

# fancy crypto won't save you

---

# no golden road to security

---

# even if you get those things right, you don't win

<!--

talk about

- breaks in formally proven code, due to either missing the correct formalisms, or w/e
- talk about misapplications of crypto vis-a-vis implementation complexity, incorrect application, &c.

-->

