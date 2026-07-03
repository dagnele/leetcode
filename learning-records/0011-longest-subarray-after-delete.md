# Longest subarray after deleting one solved

The user solved LeetCode 1493 by adapting the variable-size sliding window from Max Consecutive Ones III: keep at most one zero in the window, then score each valid window as `window length - 1` because exactly one element must be deleted. This confirms pattern transfer to a near-neighbor problem.
