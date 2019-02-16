# Bubble Sort

It's an comparison sort that repeatedly swaps adjacent element that are out of order.

* [Visual](https://visualgo.net/en/sorting)
* [Bubble-sort with Hungarian](https://www.youtube.com/watch?v=lyZQPjUT5B4)

## Pseudocode For Bubble Sort

```
  for i loop through 1 - length - 1 (analyzing algo) (n-1)
    for j loop 0 to length - 2 (n-1)
      if list[j] is greater than list [j + 1] (constant)
        swap list[j] to list[j+1] (constant)

  they are all nested so we will multiply them 
  F(n) = (n-1) * (n-1) * c
  F(n) = (n^2) - 2cn + 1
```