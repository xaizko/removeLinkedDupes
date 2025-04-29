# removeLinkedDupes
My solution for LeetCode's "83. Remove Duplicates from Sorted List"
This problem was simple but fun, as well as my first ever usage of a linked list.  

The approach is simple, never lose track of the beginning of the list by creating another node that points to the same start of the list.  

Next, check if the adjacent value is the same or not because it is sorted. If it is, change the current node's pointer to the node after the adjacent node.  

This was able to be done with a single for loop because the the end of a linked list leads to a pointer of NULL so you just have to check that condition in order to traverse through the list. 
