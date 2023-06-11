# AGTB
Agt participatory budgeting
Approval Based Budgeting method
1.1st I have seaparated project id and cost in a projectdet.csv
2.And voter id and votes in votesdet.csv
3.Then I have tried to extract the details from csv file in form of dict and also have calculated utility and max utility fitting under given budget
4.Then I have tried to apply the given 3rd satisfaction function 
which is as follows:
   f(Av, B) = if there is intersection(Av,B) then return 1 (as funded)
   else return 0 (as not funded)
 5.Then applying the 2nd Greedy rule:
 which is as follows:
   a.Start with empty B set 
   b.Then add an item a to B which maximizes the value Pv∈V f(Av, B∪{a})
 And then at end output the solution utility set which is miximized by above satisfaction and rule applied and fits under given budget.
