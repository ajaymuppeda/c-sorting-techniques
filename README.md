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
 After all the swaping completed the list of elements are shown like this [1,2,3,5,8,12,33]  


## Quick sort  
->Quick sort is a divide and conquer algorithm that sort an elements by selecting a 'pivot' element  
After selecting a pivot element we have to do partitioning the other elements    
partitioning elements are done by two array according to whether they are lesser than or greater than the pivot element ,than the sorting are listed.       
### How Quick sort works?   
1. #### Choose a pivot:  
selecting a pivot element from the list of array that can be done in selecting first array or the last array   or the random elements.     
2. #### Partition :   
Partition the array into two array, left and right    
left contains all elements which are less than pivot element    
right contains all elements which are greater than pivot element.    


After partition all the elements are arrange in the correct order with the pivot element.    
than the list of array are shown    
### Example   
Suppose we have some list of array  
[5,2,8,3,1,12,33]  
1. choose a pivot : like 5  
2. partition:  
left elements =[2,3,1]    
right elements =[12,8,33]  
3. Swaping   
left elements=[1,2,3]  
right elements=[8,12,33]  
After all elements are swap than the result is [1,2,3,5,8,12,33]    



## Selection Sort    
->Selection sort is a simple sorting algorithm that works by repeatedly selecting the smallest (or largest, depending on the sorting order) element from the unsorted portion of the array and moving it to the beginning (or end) of the sorted portion.   
### How Selection sort works?
Start with aunsorted array and an empty sprted porrtion than find the minumum unsorted portion to find the minumum element    
Swap the minumum element with the first element of the unsorted portion   
Repeat the same step until the list is sorted   
### Example   
Suppose we have some list of array
[64,25,12,22,11]   
Pass 1   
. find minumun element (11 is the minumum element)   
. Swap 11 with the first element (first element is 64)   
. than we have sorted portion [11]
. And unsorted portion [64,25,12,22]      
Pass 2
. Find minumum element (12 is the minumum element)   
. Swap 12 with the first element (first element is 64)   
. Than we have sorted portion [11,12]    
. And unsorted portion [64,25,22]   

repeat the same path with the all the elements    
the list of sorted elements are [11,12,22,25,64]     


## Insertion Sort     
Insertion sort is a simple sorting algorithm that works by passes through an array one element ata time , inserting each element into its proper postion of the array.    

### How Does Insertion sort work?     

1. Start with the second element of the array and sllect it as the key.   
2. Compare  the key with the previous element(reverse order) to find the correct postion.    
3. Shift elements greater than the key one position to the right to make space for the key.    
4. Insert the key into the correct position.   
5. Repeat all 4 steps until the list is sorted.   

### Example
Suppose we have some list of array
[12,24,13,5,6]
Pass 1:   
.Key element is 24     
.compare with previous element (12 is the element)
12<24  Donot shift the element

Pass 2:
.Key element is 13
.compare with previous element (12,24 )
. 24>13 , shift 13 to the right 
.insert 13(12,13)
  
  Pass 3:
.Key element is 5
. compare with pervious element (12,13,24)
24>5 , shift 5 to the right 
13>5 , than again shift to the right 
12>5 , than again shift to the right 
.insert 5(5,12,13)

  Pass 4:  
  .Key element is 6
. compare with pervious element (5,12,13,24)
24>6 , shift 6 to the right 
13>6 , than again shift to the right 
12>6 , than again shift to the right 
5<6 ,than no need of shift 
.insert 6(5,6,12,13)

The List is sorted (5,6,12,13,24)




 ## Project Maintainers & Contributors    
<table>
  <tr>
    <td align="center"><a href="https://ajaymuppeda.github.io/profile/"><img src="https://avatars.githubusercontent.com/u/170258834?v=4" width="100px;" alt=""/><br /><sub><b>Ajay Muppeda</b></sub></a></td>
  </tr>
</table>  