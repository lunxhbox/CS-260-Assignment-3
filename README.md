# CS-260-Assignment-3

Robbie Schatz
CS 260
2/24/24






					Linked Queue

3.	add(T value, int position):

•	Best case: O(1) - When adding an element at the beginning of the list (position = 0), the operation requires constant time since it only involves updating the head pointer.

•	Worst case: O(n) - When adding an element at the end of the list (position = size), the operation requires traversing the entire list to find the insertion point.

remove(int position):

•	Best case: O(1) - When removing the first element (position = 0), it requires constant time as it only involves updating the head pointer.

•	Worst case: O(n) - When removing the last element or an element from the middle of the list, it requires traversing the list to find the node to be removed.

get(int position):

•	Best case: O(1) - When retrieving the first element (position = 0), it requires constant time as it only involves accessing the head pointer.

•	Worst case: O(n) - When retrieving the last element or an element from the middle of the list, it requires traversing the list to find the node at the specified position.


 





 




 
