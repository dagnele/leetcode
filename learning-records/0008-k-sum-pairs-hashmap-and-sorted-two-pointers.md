# K-sum pairs with hashmap and sorted two pointers

The user solved LeetCode 1679 with a hashmap of unused seen numbers and understood the alternative sorted two-pointer rule: if the current sum is too small, moving the right pointer would only make it smaller, so move the left pointer to increase the sum. Future pair-sum work can assume this directional reasoning is available.
