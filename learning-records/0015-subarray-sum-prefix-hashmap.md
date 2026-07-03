# Subarray Sum Equals K solved with prefix hashmap

The user solved LeetCode 560 after clarifying why sliding window fails with negative numbers and why the needed previous prefix is `currentPrefix - k`. Future lessons can assume the user understands `prefixCounts[0] = 1`, counting prior prefixes, and using prefix differences to identify subarrays ending at the current index.
