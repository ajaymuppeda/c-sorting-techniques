# C-Sorting-techniques
## Bubble sort
->Bubble sort is a simple algoritham that works on repeated number through a list of elements.  
->Bubble sort wil swap the adjacent elements if they are wrong order,It will swap until the order is in the correct order.   
->The algoritham work until the element need no to swaps are needed.  
### How Bubble sort work?
1. It start from the beginning of the list.  
2. It compare the first two elements in the list,If they are in the correct order
the first element is less than or equal to second element,than it moves to next element.  
3. If the first two elements are not in the correct order , than it swap the elements.  
4. The same process is done until the last element it reach.
5. If no swap were made done , than the list is sorted.

### Example
 Suppose we have a list of elements:  
 [5,2,8,3,1,12,33]  
 Now how Bubble sort works,  
 . Compare 5 and 2 (5 is greater than 2) than we need to swap them.  
 . Compare 2 and 8 (2 is lesser than 8) than we need  not to swap them.  
 . Compare 8 and 3 (8 is greater than 3) than we need to swap them.  
 . Compare 3 and 1 (3 is greater than 1) than we need to swap them.  
 . Compare 1 and 12 (1 is lesser than 12) than we need  not to swap them.  
 . Compare 12 and 33 (12 is lesser than 33) than we need  not to swap them.  
list after [2,5,1,3,8,12,33]  
 We have to do until all the element did not need swaping.   
 After all the swaping completed the list of elements are shown list this [1,2,3,5,8,12,33]
 