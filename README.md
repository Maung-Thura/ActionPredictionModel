# TOONtology 
## Team CM37124: Aria Puri, Hannah Simmons, Maung Thu Ra
Knowledge Representation and Reasoning Project

## Goal
We are studying how the possible actions of selected cartoon characters can be predicted through reasoning given a comprehensive representation of their identifiable characteristics and traits. To do this, we will utilize the Companion FIRE reasoner and encode the characters in a Companion knowledge base. This study can be used as a foundation model for predicting regular and possible actions based on the knowledge of characteristics and traits.

### Knowledge Representation Files (.krf) to be uploaded to Companions in ascending order.
1. traits.krf
2. behaviors.krf
3. looney-tunes-characters.krf
4. actions-rules.krf

# Micro-Theory hierarchy in ascending order
1. ReasoningActionsMt
2. TraitsMt
3. BehaviorsMt
4. ActionsMt

### Example FIRE queries
(possibleActionFor TasmanianDevil Frighten-TheWord)\
(possibleActionFor TasmanianDevil (Consume-TheWord (MeatFn Duck)))\
(possibleActionFor TasmanianDevil Spin-TheWord)\
(possibleActionFor TasmanianDevil (Chase-TheWord Tweety))\
(not (possibleActionFor TasmanianDevil Fly-TheWord))\
(not (possibleActionFor TasmanianDevil Befriend-TheWord))\
(possibleActionFor TasmanianDevil Survive-TheWord)\
(not (possibleActionFor BugsBunny Frighten-TheWord))\
(possibleActionFor BugsBunny (Consume-TheWord Carrot-Foodstuff))\
(possibleActionFor BugsBunny Talk-TheWord)\
(possibleActionFor BugsBunny Charm-TheWord)\
(not (possibleActionFor BugsBunny Fly-TheWord))\
(possibleActionFor BugsBunny (Avoid-TheWord TasmanianDevil))\ 
(possibleActionFor BugsBunny (Trick-TheWord TasmanianDevil))\
(possibleActionFor BugsBunny Harm-TheWord)\
(not (possibleActionFor BugsBunny Befriend-TheWord))\
(possibleActionFor BugsBunny Survive-TheWord)\
(possibleActionFor DaffyDuck (Consume-TheWord Pea-Foodstuff))\
(possibleActionFor DaffyDuck Talk-TheWord)\
(not (possibleActionFor DaffyDuck Spin-TheWord))\
(possibleActionFor DaffyDuck Swim-TheWord)\
(not (possibleActionFor DaffyDuck Harm-TheWord))\
(not (possibleActionFor Tweety Frighten-TheWord))\
(possibleActionFor Tweety (Consume-TheWord Soybean-Foodstuff))\
(possibleActionFor Tweety Fly-TheWord)\
(possibleActionFor Tweety (Trick-TheWord Sylvester))\
(possibleActionFor Tweety Harm-TheWord)\
(not (possibleActionFor Tweety Befriend-TheWord))\
(possibleActionFor Sylvester (Consume-TheWord (MeatFn BirdOfPrey)))\
(possibleActionFor Sylvester Talk-TheWord)\
(not (possibleActionFor Sylvester Fly-TheWord))\
(possibleActionFor Sylvester Worry-TheWord)\
(possibleActionFor Sylvester Survive-TheWord)

# The output screenshots of the above FIRE queries can be referred in our final project report in 
https://nuwildcat.sharepoint.com/:f:/r/teams/Course_2024wi_msai_371_0_sec20_and_comp_sci_371_0_-vsP8h4rBcUpqh/Shared%20Documents/Projects/CM37124?csf=1&web=1&e=cb7b2E
