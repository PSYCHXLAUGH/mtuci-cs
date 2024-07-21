# [Introduction](https://drive.google.com/file/d/1MhcU5B1OFkIR8pKaWp18bNiRYea3iB8N/view)

# What is a search?
- Finding a specific value among a regular set or a multiset using a “search key” for this purpose
# What is multiset?
- A regular set, but elements may repeat two or more times in a given set (may contain duplicates)

```python
from collections import Counter

multiset = Counter([1, 2, 2, 3, 3, 3])
print(multiset)
# Output: Counter({3: 3, 2: 2, 1: 1})
```

#### What problem do search algorithms solve?
- Suppose we have a dataset of N items Each N elements contains a record, which is the main “record” and a “key” which is used for searching This key is called - “search key”
- The task of the search is to select all elements from the set for which the keys are equal to our search key. k=K
#### What are the requirements for item keys so that the search task is applicable to them?
- There must be an equivalence relation for the set of “keys”, which is denoted by the tilde sign
#### The following conditions must be met for any keys
1. Reflexivity 
```python
R = {(1, 1), (2, 2), (3, 3)}
#  (a, a) ∈ R
```
2. Symmetry
3. Transitivity
