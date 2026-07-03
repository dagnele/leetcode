# In-place read/write invariant

The user correctly identified that after processing the first group in String Compression, `chars[0:write]` should contain the compressed prefix such as `['a', '2']`. Future lessons can assume the read/write pointer model is understandable and should reinforce it through implementation practice rather than re-explaining from scratch.
