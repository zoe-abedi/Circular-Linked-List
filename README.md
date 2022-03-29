# Circular-Linked-List
<!-- Python program to Search an Element in a Circular Linked List -->
<!-- A linked list is a kind of linear data structure where each node has a data part and an address part which points to the next node. -->
<!-- A circular linked list is a type of linked list where the last node points to the first one, making a circle of nodes. -->
<!-- Example:

Input: CList = 6->5->4->3->2, find = 3
Output: Element is present
 
Input: CList = 6->5->4->3->2, find = 1
Output: Element is not present -->
<!-- Search an Element in a Circular Linked List -->
<!-- For example, if the key to be searched is 30 and the linked list is 5->4->3->2, then the function should return false. If the key to be searched is 4, then the function should return true.  -->
<!-- Approach: 
Initialize a node pointer, temp = head.
Initialize a counter f=0 (to check if the element is present in a linked list or not).
If the head is null then the print list is empty.
Else start traversing the Linked List and if element found in Linked List increment in f.
If the counter is zero, then the print element is not found.
Else print element is present. -->
<!-- Output:

element is present
element is not present -->
