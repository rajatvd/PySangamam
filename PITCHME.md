
# Iteration
@ul
* Iteration is a type of control flow in which a set of statements are repeated. 
* We implement iteration using _loops_.
* Let's say we want the squares of natural numbers.
@ulend
---
```
def squares(n):
    i = 1  
    out = []  
    while i<=n:  
        out.append(i**2)  
        i+=1  
    return out 
```
@[1](test 1)
@[2,3](test 2,3)

<code class="fragment">
squares(10)
output: [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
</code>
