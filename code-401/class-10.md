# Read: Class 10 (Stacks & Queues)

## What is a Stack

- A stack is a data structure that consists of Nodes. Each Node references the next Node in the stack, but does not reference its previous.

- FILO (First In Last Out)
  - This means that the first item in the queue will be the first item out of the queue.

- LIFO (Last In First Out)
  -This means that the last item in the queue will be the last item out of the queue.

- When you `push` something to the stack, it becomes the new `top`.
- When you `pop` something from the stack, you pop the `current top` and set the next top as `top.next`.
- Pushing a Node onto a stack will always be an `O(1)` operation.

#### Pseudocode to push a value onto a stack

```
ALOGORITHM push(value)
// INPUT <-- value to add, wrapped in Node internally
// OUTPUT <-- none
   node = new Node(value)
   node.next <-- Top
   top <-- Node
```

#### the pseudocode for a pop

```
ALGORITHM pop()
// INPUT <-- No input
// OUTPUT <-- value of top Node in stack
// EXCEPTION if stack is empty

   Node temp <-- top
   top <-- top.next
   temp.next <-- null
   return temp.value
```

## What is a Queue

- `Enqueue` - Nodes or items that are added to the queue at the end of the node.This is done with an `O(1)` operation in time.

- `Dequeue` - Nodes or items that are removed from the queue.you are always just removing the front Node of the queue. This is done with an `O(1)` operation in time.
- When conducting a `peek`, you will only be inspecting the front Node of the queue.This is done with an `O(1)` operation in time.
