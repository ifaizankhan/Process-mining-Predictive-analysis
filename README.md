### Predictive Analysis based on the event log

The inputs needed for this part are:

  - The BPIC2017 event log: https://data.4tu.nl/articles/BPI_Challenge_2017/12696884
  - The process model
  
During the execution of process models, it can become interesting to predict future behavior of the currently running process instance. For example: „How long will it take until this instance finishes?“, „Can any delays be expected?“. In this case study, we will focus on task prediction, i.e., which task will probably happen next?

To this aim, your task is to build a prediction system (predictor). The general input for your predictor is a currently running (i.e. incomplete) process instance (i.e., an incomplete trace).

