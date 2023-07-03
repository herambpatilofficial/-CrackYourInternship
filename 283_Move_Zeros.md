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
    def moveZeroes(self, nums: List[int]) -> None:
        """
        Do not return anything, modify nums in-place instead.
        """
        zeros = 0
        i = 0
        
        while i in range(len(nums)):
            if(i==len(nums)-zeros):
                break

            if nums[i] is 0:
                zeros = zeros + 1
                nums.append(nums.pop(i))


            
                
            else:
                i = i+1


        



        

               
```