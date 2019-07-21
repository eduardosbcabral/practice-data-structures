Dynamic Array:
  - Unlike static arrays, dynamic arrays can be resized.
  - Appending a new element to a dynamic array is often constant time, but can take O(n).
  - Some space is wasted.

Following operations:
  - Get(i): returns element at location i*
  - Set(i, val): sets element i to val*
  - Pushback(val): Adds val to the end.
    - When using pushback, checking if the array has empty spaces is required. When it does not have, it will be needed to create a new array with a bigger capacity and alocate all the values into the new array and change the pointer location. 