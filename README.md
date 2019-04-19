# cs3211-contract-signing
CS3211 Parallel & Concurrent Programming AY18/19 Sem 2 Project 1  
Project Members: Alvin Yan, Au Liang Jun, Michael Hu  
This project aims to formally verify the properties of the [Abuse-free Optimistic Contract Signing Protocol by G.Juan, J.Markus and M.Philip (1999)](http://markus-jakobsson.com/papers/jakobsson-crypto99.pdf) with the [Process Analysis Toolkit (PAT)](http://pat.comp.nus.edu.sg/), a model checking tool. Models in PAT are written in Communication Sequential Process (CSP) syntax and verified against Linear Time Temporal Logic (LTL) formulae. We found that the protocol was correct, complete, fair, optimistic and abusefree, but susceptible to a Dolev-Yao attacker.
