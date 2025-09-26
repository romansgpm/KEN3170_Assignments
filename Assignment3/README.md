# Assignment 3

Coding: Paul
Questions: Iva

Description of Assignment 3

Which mutation is most dangerous and why? Provide quantitative evidence.

p53 loss-of-function and MYC amplification are equally the most dangerous 
they are the most dangerous because they eliminate the apoptosis attractor and collapse the system into a single pro growth point with a 100% basin 

Explain the role of feedback loops (e.g., MYC → MDM2 → p53)

It forms a mutual inhibition between p53 and MYC which is effectively a positive feedback loop.
When p53 rises it activates p21 and suppresses MYC/CDK2, which reduces MDM2, therby releasing p53 from inhibition. 
So the network exhibits bistability under DNA damage.


What are the limitations of this Boolean network model? Discuss 3 specific limitations.

1. Binary states and synchronous updates
  All nodes update at the same time. Real biology is noisy and not syncronised. Different update schemes can change attractors and basins.
2. Oversimplified rule structure collapses dynamics
  Many nodes collapse to p53 which makes p53 the single effective driver, underestimating parallel signaling  and context dependence.
3. No kinetics, threshold or delays
  The model lacks time delays, dose effects and rate differences. These features can critically determine whether a cell repairs, pauses, dies or proliferates.
   

Generative AI usage:
generative ai has been used to solve problems regarding copy creation of the "network" object to create mutation A,B,C and D, and used to formulate the answers to some questions
