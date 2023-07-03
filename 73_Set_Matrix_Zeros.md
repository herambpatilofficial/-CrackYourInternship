73. Set Matrix Zeroes
# 73. Set Matrix Zeroes

# Intuition
<!-- Describe your first thoughts on how to solve this problem. -->

# Approach
<!-- Describe your approach to solving the problem. -->

# Complexity
- Time complexity:
<!-- Add your time complexity here, e.g. $$O(n)$$ -->

- Space complexity:
<!-- Add your space complexity here, e.g. $$O(n)$$ -->

# Code
```
class Solution:
    def setZeroes(self, matrix: List[List[int]]) -> None:
        """
        Do not return anything, modify matrix in-place instead.
        """
        zerocol = []

        m = len(matrix)
        n = len(matrix[0])

        for i in range(m):
            if 0 in matrix[i]:
                for j in range(n):
                    

                    if matrix[i][j] is 0:
                        zerocol.append(j)


                    else:
                        matrix[i][j] = 0
        
       
        for v in range(m):
            for j in zerocol:
                
                matrix[v][j] = 0




        
```