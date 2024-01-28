# What are Linked Lists
- The first real DSA
- Its a node based structure
- Each node points to another node (NOT THE FRIGGIN RUNTIME)
- Singly = Can't go backwards
```
node<t>
    val: T
    next?: Node<T>
```
- Doubly = Can go backwards
```
node<t>
    val: T
    next?: Node<T>
    prev?: Node<T>
```
## Insertion and Deletion
- To insert or delete, it means to change the links, be it forward, be it backwards
- Insertion means adding a new node that will take a new space between nodes
- Deleting means changing the link between nodes to "ignore" the value to be deleted, thus, dorpping it to the GC
- Insertion or Deletion are constant time operations, thus O(1)

