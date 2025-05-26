# Monte-Carlo-Simulation
A self-coded project which finds the area of a circle using Monte Carlo methods to better understand how they work. Completed before formally learning about Monte Carlo methods in my degree.

## Getting started

To get started, run the following command in your preferred terminal:

```console
foo@bar:~$ git clone https://github.com/EA-Mante/Monte-Carlo-Simulations.git
```
This clones the repo to your computer, then run the notebook and enjoy! You will notice that the top half of the notebook contains the original code, and the bottom half the streamlined version.

## Edit (made after formally learning about Monte Carlo methods in my degree):

Monte Carlo methods can be applied in many different ways, the example I coded in the notebook back in spring 2023 is similar to the first one shown in this video: [Monte Carlo Simulation, MarbleScience](https://www.youtube.com/watch?v=7ESK5SaP-bc). At the end of this video, he gives another use case in Monte Carlo path tracing.

Monte Carlo methods can also be used to find the equilibrium state of a chemical system. The flowchart I have constructed below is for a Metropolis algorithm. Note that in 4.2.1 a number is chosen in the interval [0,1) and compared to the exponential term to take the magnitude of the energy difference into account. I.e. the higher the energy of the new state compared to the old state, the less likely it (the new state) is to be accepted.

***

![image](https://github.com/user-attachments/assets/3be552b2-93f5-45a0-b295-cfafbaa04300)

***

The interested reader can learn more about Monte Carlo methods in chemistry here: [Computational Chemistry 3.11 – Metropolis Monte Carlo, TMP Chem](https://www.youtube.com/watch?v=xVvUFB5Hk-g).
