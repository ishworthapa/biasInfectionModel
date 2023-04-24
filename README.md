# biasInfectionModel
## WHAT IS IT?

This is a simple model with Mosquito and Human as agents. It includes two aspects of viral propagation in vector borne diseases, viz. the mosquito's attractiveness to human in general and further preferential attractiveness to infected hosts. 

## HOW IT WORKS
In every tick, the mosquitoes and humans can move one step. Human agents can move in any direction randomly, while the direction of mosquito depend on attractiveness and bias ( preferential attractiveness to infected hosts) parameter values. When an uninfected mosquito share a patch with an infected host, the mosquito is inoculated with the virus and its state changes to incubation stage. After incubation time is finished, the mosquito will change to a carrier state and can infect an uninfected human. The mosquito remains to be in carrier state for its lifetime and after its lifetime (given by average carrier time), the mosquito changes to initial uninfected state, representing replacement of previous mosquito by a newly born one. When a human agent is infected by biting of carrier mosquito, its state converts to infected stage and is sick for a period of time. After the sick time is over, the individual can no longer transmit the virus to another mosquito and can not get re-infected for a period of time. 

## HOW TO USE IT

Set the num-of-mosquitoes, number-of-individuals and %-of-infected-at-start. The 'human-attractiveness' and 'bias' parameters can be set between 0 to 1. 

Click on the SETUP button to set up the world with Mosquito and Human. Click on GO to start the model. The human and mosquitoes can wrap around the world as they move across the boundaries. 

## THINGS TO TRY
Set num-of-individuals = 100, num-of-mosquitoes = 100 and %-of-infected-at-start = 10

Set different values for attractiveness and bias and RUN the model. Try out with human-attractiveness = 0.2 or 0.6 or 1.0​ and bias = 0.0 or 0.2 or 0.6 or 1.0​.


## CREDITS AND REFERENCES

https://github.com/ishworthapa/biasInfectionModel
