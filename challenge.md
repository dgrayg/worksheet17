6. Is the function below tail-recursive? Why/Why not?
    ```java
    int factorial(int n, int product) {
        if (n == 1) {
            // DRAW MEMORY HERE FOR C8
            return product;
        } else {
            return factorial(n - 1, product * n);
        }
    }
    ```
   
7.  a. How would you call the above function if you wanted to find the factorial of 4?     
    b. Draw what memory looks like at the indicated location in the `factorial()` function, when computing the factorial of 4.


