# Oct 10 2017, Gates-Thomas 320

Present: Rohan, Sofie, Petter, Cristian (on Skype)

## Administrative

 - Cristian's code is at https://github.com/wasserfeder/gdtl-firm
 - We have a repo for tex at https://github.com/shaesaert/BeST


## Goals

 - Overall goal of project is a tight connection of discrete planning in belief space to low-level dynamics
 - Sofie interested in using the project as a case study, has ideas about how to formalize connection between discrete and continuous domain via simulation relations


## Problem definition

 - Three different "problems" are relevant at this point: a full-scale (intractable) problem, a scenario for the demo, and the problem we solve in the initial paper
 - Sofie has technical concerns about Lebesque measurability in the definition of the logic and suggests Borel measurability
 - Concern should be taken when dealing with infinite-time properties in probabilistic settings


## High-level side

 - Belief planning most relevant for uncertainty in the map. 
 - Will likey need abstraction of copter behavior to avoid planning on full model. Abstraction could be in form of LTL spec.
 - A way to decouple the problem is via assume-guarantee contracts. I.e. copter says: if #(grids to explore < 30) -> grids will be explored.
 

## Low-level side

 - Ames group (Andrew, Thomas, Petter) will meet tomorrow to purchase quadrotors. Initial objective is to set them up with A-B motion generation. 


## Software

 - There is more work required to get results for the paper. Cristian will polish the code a bit to make it easy to work with
 - It may be possible to make the code faster by using a C++-implementation of FIRM


## Next steps

 - Improve paper with a robotics venue in mind (All)
 - Prepare for partial handover of code next week, including installation instructions and list of things to be done (Cristian)
 - Write down different suggestions for problem definitions and demo scenarios (Petter)
