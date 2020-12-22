# Linked List

> **Definition**: A Linked List is a data structure that is ordered. Unlike an array that contains items with an indexed position. You can think of a Linked List like a train and you have start at the beginning and move to the next one. A Linked List consist of nodes and each node has a value and a pointer to another node.

![Linked List Diagram](https://miro.medium.com/max/970/1*f2oDQ0cdY54olxCFOIMIdQ.png)

### Types

- **_Singly_** - Means that the nodes is connected only in **_one_** direction.
- **_Doubly_** - Means that the nodes are connected **_bi-directional_** or **two ways** connected to the previous node.

### Terms

- **Node**: A node is the element that data structures consist of. Each Node in a linked list contains two pieces of information: A **_Value_** and a **_Pointer_** to the another node or null.

### Contains

- **Head**: Front of the list. From the head we can figure out the next item. _-example-_ If we wanted the second item of in the structure we can call on an index number we would need to start at the head and move to the next.
- **Tail**: End of the list.

### Methods

- Push

### LL key pointers

- **_Don't_** have indexes
- Random access is _not_ supported. _i.e_ you can't request an item by index you have to start at the head and work your way through the list.
- Connect using nodes with a next pointer.

### Good reason why LL are used

To better understand linked list and its dynamic nature, let's use the analogy of something we are all familiar with; contact list on our phone. Imagine will have five names in our phone contact which are implemented using a static data structure such as arrays like [Abby, Demi, Gina, Rita, Ursula]. In a structure such this, if another name 'Bobby' is to be inserted between Abby and Demi, it means the size of the structure has to be increased by one, and the data items from Demi has to be shifted one position to the right. While that may not seem like much work given the number of contacts in this case, imagine a case of 10,000 or 1,000,000 contacts, shifting and repositioning that much data would amount to enormous strain on the computer processing resources. That is where dynamic data structures such as **_linked list_** come in. [read more](https://study.com/academy/lesson/dynamically-linked-lists-in-c-programming-implementation-example.html 'Dynamically Linked Lists in C Programming: Implementation & Example| Study.com')

### Advantages of Linked List

- **Dynamic Data Structure** - Meaning the size of the structure in not fixed and can be modified during the operations performed on it. So it can grow and shrink at runtime by allocating and deallocating memeory. So there is no need to give initial size of linked list.

- **No Memory Wastage** - Since a LL can grow and shrink at runtime, unlike an array which is a static DS with a fixed memory allocation (which can be modified but without changing the memory space allocated to it) a Linked list memory is **_only_** allocated with what is _required_.

- **Insertion and Deletion** - When it comes to arrays if you need to insert or delete all the elements would need to shift. With LL it's extremely easier because all you would need to do is **_update the address present in next pointer of a node._**

### Disadvantages of Linked List

- **Traversal & Reverse Traversal** - This can get tricky with linked list because unlike arrays that have an advantage with indexes we have to travel through to get to what item we want starting at the head. An cool analogy I read about LL is like climbing stairs, you have to go one-by-one starting from the top or bottom (unless you can fly!).
- **Memeory usage** - LL will require a bit ***more memory than an array*** because remember, a node an a linked list consist on **two** elements (value, pointer) both of which requires memory allocation. 
