# Linked-Lists

# 📘 Linked Lists in C++

## Theory of Linked Lists

A **linked list** is a linear data structure where elements (called **nodes**) are connected using **pointers**.  
Unlike arrays, linked lists are **not stored in contiguous memory**; instead, each node contains:

1. **Data** – the value stored in the node.
2. **Pointer (next)** – a reference to the next node in the list.

### Key Characteristics:
- **Dynamic size**: Can grow or shrink during execution.
- **Efficient insertions/deletions**: No shifting required like arrays.
- **Sequential access only**: Random access is not possible.
- **Types of Linked Lists**:
  - **Singly Linked List** – Each node points to the next.
  - **Doubly Linked List** – Each node points to both next and previous.
  - **Circular Linked List** – The last node points back to the first.

---

## Algorithm for Code 1 (Insert at Head and Display)


// Steps
1. Define a class `Link` with `data` and `next` pointer.
2. Create a function `insert_head(head, data)`:
   - Allocate new node with given data.
   - Point new node’s next to current head.
   - Update head to new node.
3. Create a function `disp(head)`:
   - Traverse nodes from head.
   - Print data followed by " --> ".
   - End with "NULL".
4. In `main`:
   - Initialize head as NULL.
   - Insert nodes one by one at head.
   - Display the list after each insertion.

## CODE 2
// Steps
1. Define a class `Node` with `val` and `next`.
2. Create three nodes dynamically: n1(11), n2(04), n3(6).
3. Link them:
   - n1 -> next = n2
   - n2 -> next = n3
   - n3 -> next = NULL (default).
4. Initialize a pointer `temp` to head (n1).
5. While temp is not NULL:
   - Print temp -> val.
   - Move temp to temp -> next.
6. End traversal.

## CODE 3

// Steps
1. Define a class `Node` with `val` and `next`.
2. Create three nodes dynamically: n1(11), n2(04), n3(6).
3. Link them:
   - n1 -> next = n2
   - n2 -> next = n3
   - n3 -> next = NULL (default).
4. Initialize a pointer `temp` to head (n1).
5. While temp is not NULL:
   - Print temp -> val.
   - Move temp to temp -> next.
6. End traversal.

## CONCLUSION

## Conclusion

- Linked lists are an important **dynamic data structure** where memory is allocated at runtime.  
- They allow **fast insertions and deletions**, especially at the head or middle of the list.  
- **Drawback**: Traversal is sequential, so searching or accessing by index is slower compared to arrays.  
- **Code 1** demonstrates insertion at the head and dynamic traversal.  
- **Code 2 and Code 3** show manual creation and linking of nodes, followed by traversal.  
- Together, these examples illustrate the **fundamental operations of creating, linking, inserting, and displaying a linked list in C++**.



