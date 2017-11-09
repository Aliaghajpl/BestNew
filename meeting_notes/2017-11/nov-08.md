# Meeting 11/6

Present: Rohan, Kamak, Kyon Ali, Petter, Sofie

## Administrative
 - There is discontent with Overleaf: main latex file is global. Will move back to Sharelatex/Git
 - Will treat Sharelatex as main repo, thus git must follow this workflow:
 	- Push changes from Sharelatex to Github
 	- Pull changes from Github to local repo
 	- Make edits
 	- Push changes from local repo to Github
 	- Pull changes from Github to Sharelatex (x)
 - Argument for this is that potential merge conflicts will arise in step (x) and can then be handled on the git side  

## Report 1
 - Petter and Rohan working on policy generation (value iteration/LP) and simulation
 - Sofie comment about Syntactically Co-safe specifications
 	- Not syncosafe specifications don't translate to DFSA
 	- Can replace not syncosafe always specifications []S with S U T, where T is a target state
 	- T can be a safe stopping place that concludes the mission for the day
 	- There seems to be consensus to restrict LTL fragment to syntactically co-safe specifications
 - There are similarities between the procedure and statistical model checking that should be clarified
 - Sofie unsure whether an LP can solve the DynP problem

## Report 6
 - Kamak is comparing 20 methods across 10 features. He has all the papers but it's difficult to extract each feature since many papers don't touch on all features.