# Contiguous Array solved with diff first-seen index

The user solved LeetCode 525 after first deriving a brute-force count of zeros and ones, then optimizing by tracking `diff = zeros - ones` and remembering the earliest index where each diff appeared. Future lessons can assume understanding that repeated diff values imply a balanced subarray between those moments, that earliest index gives maximum length, and that `{0: -1}` represents the empty prefix for subarrays starting at index 0.

Coaching note: avoid giving the target pattern, data structure, or key transformation during active attempts unless explicitly asked. The user wants guided discovery and reacts strongly to spoilers.
