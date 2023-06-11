# Matrix transposition on shared memory
## Aim:
To compare the performance of different matrix transposition implementations using CUDA.

## Procedure:
1. The code implements various matrix transposition techniques using shared memory in CUDA.
2. The different implementations include:
3. setRowReadRow: Transpose matrix using row-major ordering for both read and write operations.
4. setColReadCol: Transpose matrix using column-major ordering for both read and write operations.
5. setColReadCol2: Transpose matrix using column-major ordering for write operation and row-major ordering for read operation.
6. setRowReadCol: Transpose matrix using row-major ordering for write operation and column-major ordering for read operation.
7. setRowReadColDyn: Transpose matrix using dynamic shared memory and row-major ordering for write operation and column-major ordering for read operation.
8. setRowReadColPad: Transpose matrix using row-major ordering for write operation and column major ordering for read operation, with padding.
9. setRowReadColDynPad: Transpose matrix using dynamic shared memory, row-major ordering for write operation, column-major ordering for read operation, with padding.
10.  The code measures the execution time of each implementation using CUDA events.
11. The results of the matrix transposition are verified by comparing the output with the expected result.
12. The performance of each implementation is compared based on their execution times.
## Output:
![image](https://github.com/Kavya-Bollineni22/PCA-Demonstrate-Matrix-transposition-on-shared-memory/assets/75235813/47a550f9-189a-4248-8ba9-0e5552f0b395)

## Result:
Thus, the comparison of the performance of different matrix transposition techniques using shared memory in CUDA. By measuring the execution time of each implementation, we can identify the most efficient technique for matrix transposition.
