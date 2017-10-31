# Answers
- What is the purpose of the various auxiliary methods `populateList`, `populateFifoList`, and 
`ReverseLines.printReverse`?  

- Why do these methods need to have arguments, and how does the argument change from one recursive call to 
the next?  
The methods need arguments to be able to store the new data found for the variables and update them. It changes 
from one recursive call to the next in how it stores the values used in the nodes and continues to grow. 

- What are the time and space complexity of each of the `populateList`, `populateFifoList` methods, as well 
as `ReverseLines.printReverse`?  
The complexity of `populateList` is O(n).  
The complexity of `populateFifoList` is O(n).  
The complexity of `ReverseLines.printReverse` is O(n). 

- Which of these methods can be implemented using `while` loops?  
Each of these methods, `populateList`, `populateFifoList`, and `ReverseLines.printReverse` could essentially
be implemented using `while` loops instead. 