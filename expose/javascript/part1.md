# Part 1

1. Line 9 prints "values added: 20"
2. Line 13 prints: "final result: 20"
3. We shoul dnot use **var** because it is a funciton scope. Therefore, using it can result in variables accessing outside the block its declared in. This can ultimately lead to naming conflicts and scoping issues. 
4. Line 9 prints "values added: 20"
5. An error is returned by line 13. On line 13, **result** was declared with **let** isnide the **if** block. This prevents it from being accessed outside of the block. 
6. An error is returned by line 9. On line 9, **result** was declared with a **const** and was later reassigned. However, constant variables are not allowed to be reassigned. 
7. Line 13 was never printed because there were already errors before reachign line 13. 
   
   

