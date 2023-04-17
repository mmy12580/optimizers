# Optimizers

Handy optimizers to use. 

**Lion vs. Adam**
  - Less memory consumed. Lion only keeps track of the momentum state, while Adam also keeps track of the squared gradient state. 
  - Faster computing since Lion has the same (Adam： different) magnitude for each parameter, calculated through the sign (Adam: division) operation. 
  - Lion's performance improves as the batch size increases.
  - Lion uses smaller learning rate so it has a larger norm of the update, which leads to faster convergence 


  
