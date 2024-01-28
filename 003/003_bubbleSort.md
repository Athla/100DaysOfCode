# What is sort
- To organize something in a given logical order
- Definition of sorted:
    - X_i <= X_i+1
## What the hell is bubble sort?
- The most simple algo
- Yet hard to see it
- if X_i > X_i+1, X_i+1 = X_i;
    - In the first iteration the largest item is in the end of the array
    - A single iteration puts the largest value at the end
    - Exclude the last value, because it is already sorted
    - Should be implementated without coping the array once more
- What would be the running time?
    - First time is N Checks
    - Second is N - 1;
    - Then Nth iteration +1 == N - (nth +1)

```typescript

```
