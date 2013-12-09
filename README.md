AttentionalModulationTask
=========================

Fall 2013 PIN rotation with David Cox

## Experimental Design

Sequence of events expressed during a single trial: head poke/no poke —> display target (A/B) or distractor (O) —> animal lick/no lick —>reward/neutral/punishment. Trials are embeded in sessions. There is one session per day, one hour per session. We vary the amount of reward associated with A or B across sessions, while maintaining the total amount of reward delivered for A or B constant overtime.

**TRAINING**

**Phase 0:**  Manually train the animal to poke its head out of the behavior box and lick the water spout mounted on a 10ml syringe. Two sessions seems sufficient.

**Phase I:**  A/B/O are shown with equal probabilities. Equal amount of reward is delivered for A/B when animal licks. Licking on O triggers the punishment loop. As a function of average performance, distractor contrast is increased from 0 to 1 whilst reward amount is decreased from 0.05 to 0.03. 

**Phase II:**  A/B/O are shown in full contrast with equal probabilities. On any given session, a fixed, asymmetrical amount of reward is delivered for A/B when animal licks. Licking on O still triggers the punishment loop. Reward amount is decided at the start of each session, a random number *randReward* between -0.02 and +0.02 is drawn. We then set *RewardA* = 0.03 + *randReward* and *RewardB* = 0.03 - *randReward*. The magnitude of *randReward* can be regarded as a proxy for how much the animal should pay attention to the dimension along which A and B varies.


