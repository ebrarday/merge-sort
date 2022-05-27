# Merge Sort Project Questions

[16,21,11,8,12,22] 
1.Merge Sort
  Merge Sort is a recursive algorithm that sequentially halves the array down to its smallest sub-arrays, then puts them in order and merges them. Lets do it!
   -> |16||21||11|  |8|12|22|
          -> 16,21,    11   |   8,12,     22
          -> 11,16,21       |   8,12,22
          -> 8,11,12,16,21,22
          
2.Big-O
O(n*(logn)) --> O(6*(log6))
