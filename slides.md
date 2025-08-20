---
marp: true
theme: custom
paginate: true
_paginate: true
---

<!-- _theme: custom -->

<style>
section {
  font-family: "Segoe UI", sans-serif;
}
h1 {
  color: #0066cc;
}
footer {
  font-size: 12px;
  text-align: right;
  color: gray;
}
</style>

# Product Documentation

Prepared by  
**24f3003609@ds.study.iitm.ac.in**

---

# Overview

- Modern product documentation  
- Version-controlled (Git)  
- Exportable to PDF/HTML/PPTX  

---

# Algorithmic Complexity

The runtime complexity of our algorithm:

$$
T(n) = O(n \log n)
$$

---

# Code Example

```python
def search(data, key):
    for i, item in enumerate(data):
        if item == key:
            return i
    return -1
