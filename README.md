<a id='top'></a>

# There are Two Projects Here

Project 1 has more to do with data visualziation and project 2 with a litle more optimization/hardcore machine learning

I think both have validity in the job market and are useful things to learn -- It just depends on what is of interest!

# Corian Project (these are mostly just notes): 

## Pots of Gold

1. here's your product wheel and the loss in transition sheets from your random
    production plan to one that is optimized. Potentially run through
    monte carlo
    * traveling salesman
    
## Hypotheses
* we have some anomalies in the data
    1. [unusual Next Color Code](#color)
    
* can we use the sequence of order numbers to isolate those for which we had failed transitions 
  (i.e. we gave up) and determine the relationship between transition attempts and fail rate?
    1. [fail rates](#fail)

    

    

* ### Transition Distributions
    1. [distributions](#dist) Let's fill in the cells in the matrix
    1. [fraction of transitions explained](#terminate)  When should we terminate a bad transition?
    3. [sorted boxplots](#sorted)
    2. are we learning as we do the transition more often? [median transition sheets vs number of transits](#transits)


[combined data](#combinations)

* if we combine with **family labels** what are the transition characteristics for (#2)
   
    1. inter-family transitions
    2. intra-family transitions
    3. inter-subfamily transitions
    4. intra-subfamily transitions
    5. where are we having the most operational upsets in terms of product/family/subfamily


* if we combine with **scheduling data**
    1. what transitions are being scheduled today and do we have transition data for them


* combined with **downtime data**
    1. what is the relationship between products on the line and downtime
    
  # Gendorf Project
  
  [app-site](#http://gendorf-dev.herokuapp.com/)
  
  -- more dataviz focused and less ML
  
  It's a current project we're working on -- up to ya'lls interest level
  
