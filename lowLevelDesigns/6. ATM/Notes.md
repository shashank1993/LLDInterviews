Could have created only enum for state but then
when we run onKeyPressed, we need to put if else check in 
Atm class 

Since the function works as per state so keep them with state
like in chess

canMove - keeping with piece to avoid if else check


Q How will state class use CashDispensor and display


 Missed
 - User will have card
 - Missed generic states like SelectOperationState
 - Missed Transaction class


Notes:
- We could also have AtmWorkFlowSteps that will decide which step to go to next, this will help us to
    not pollute states for workflow changes like we want to show options then homepage post transaction