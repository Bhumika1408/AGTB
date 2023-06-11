AGTB
Agt participatory budgeting
Approval Based Budgeting method

Method:
1.1st I have separated project id and cost in a projectdet.csv
2. And voter id and votes in votesdet.csv
3. Then I tried to extract the details from the CSV file in the form of a dictionary and also calculated utility and max utility fitting under a given budget
4. Then I tried to apply the given 3rd satisfaction function 
which is as follows:
   f(Av, B) = if there is intersection(Av,B) then return 1 (as funded)
   else return 0 (as not funded)
 5. Then apply the 2nd Greedy rule:
 which is as follows:
   a.Start with an empty B set 
   b.Then add an item a to B which maximizes the value Pv∈V f(Av, B∪{a})

 And then at the end output, the solution utility set is maximized by the above satisfaction and rule applied and fits under the given budget.


