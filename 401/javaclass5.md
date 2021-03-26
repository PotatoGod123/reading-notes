# Java

## Linked List

Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.

- Singly - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
- Doubly - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
- Node - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
- Next - Each node contains a property called Next. This property contains the reference to the next node.
- Head - The Head is a reference type of type Node to the first node in a linked list.
- Current - The Current reference is a reference type of type Node that is currently being looked at. This node is traditionally used when traversing through a full linked list. When traversing, you typically reset the current to the head to guarantee you are starting from the beginning of the linked list.  


So essetially you use a while loop to check if Next exist in the linked list to traverse and set up loging in the while loop to check whatever you are doing and if it does not match, set the current head to the next head.


The time efficiency of this transaction would be O(n) because we could be inserting the new node, worst case scenario, at the end. With n being the number of nodes possible, we would therefore have O(n) time efficiency.

Space efficiency would stay at an O(1) because, like before, no additional space is being used allocated outside of what is given to us on the input

[Click Here For more info and pictures!](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)  


[<==Back](../README.md)  
