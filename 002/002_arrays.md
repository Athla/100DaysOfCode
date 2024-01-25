# Arrays, yes, them.
- Continuous memory allocation
- Most basic DS
- Array != List
- Cannot insert, push or pop, nor grow it.

## Insertion
- width $\times$ offset puts at the memory index
- technically overrides it;
- to expand, would be necessary to realloacate memory and then change it
- basically deal with malloc and mem mapping

## Deletion
- Technically does not delete, just override it to a value that should be ignored. E.G: Null, a way to represent nothing, because nothing is something

## Getting
- Same way as insertion, width $\times$ offset, returns the value

## Big O
- O(1)
***
# Algorithms
### Search Algorithms
- The first algo!
#### The most basic, Linear Search
```
func search (arr, v){
    for i in arr{
        if arr[i] == v
            return arr[i]
    
    return null
    }
}
```
- O(N) runtime, worst case scenario, grows linearly with the input
##### Binary Search
- Works if ordered
- Jump middle, check if arr(i) == value return true
- worst possible outcome, value at extremes positions