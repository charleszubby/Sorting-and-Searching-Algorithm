Step 1
line 2-4, Variable Declaration:

arr: Stores the array of integers to be sorted.
i: Loop counter for the outer loop.
j: Loop counter for the inner loop.
key: Stores the element to be inserted into the sorted part.

Step 2
line 7
Read the Array:
Reads the input array from the user and stores it in arr.

Step 3;
line 9-19
Insertion Sort:
Outer loop (FOR i FROM 1 TO LENGTH(arr) - 1): Iterates through each element in the array starting from the second element (index 1).
key: Stores the current element (arr[i]) to be inserted.
j: Initializes j to i - 1, which is the index of the last element in the sorted part.

Inner loop (WHILE (j >= 0 AND arr[j] > key)): Iterates as long as j is within the bounds of the array and the element at index j is greater than the key.
Shifts the element at index j one position to the right (arr[j + 1] := arr[j]).
Decrements j to move to the previous element in the sorted part.
After the inner loop, the correct position for the key is found.
arr[j + 1] := key: Inserts the key element into its sorted position.

Step 4;
line 21
Write the Sorted Array:
Outputs the sorted array (arr) after completing the insertion sort process.
