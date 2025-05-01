---
title: "Lecture Notes Template"
---

# Section Title

This is a paragraph under the top-level section.

## Subsection Title

You can organize content using subheadings like this.

### Subsubsection Title

And go even deeper if needed.

---

## Lists

### Unordered List

- First item
- Second item
  - Nested item
- Third item

### Ordered List

1. Step one
2. Step two  
   1. Sub-step
3. Step three

---

## Blockquotes

> This is a quote from the lecturer or slides.  
> Use it to emphasize key insights or comments.

---

## Equations with Numbering and References

Here's an important equation:

$$
E = mc^2 \tag{1}
$$

We can refer back to it like this: see $(1)$ for the mass–energy equivalence.

Another equation:

$$
F = ma \tag{2}
$$

According to $(2)$, force equals mass times acceleration.

---

## Links

- [Quarto Documentation](https://quarto.org/)
- [LaTeX Math Reference](https://katex.org/docs/supported.html)

---

## Figures with Width and Centering

You can insert and center images like this:

![Image](image.png){align="center" width="50%"}


or if you want to have it centered:
<p align="center">
  <img src="image.png" alt="An illustrative example" width="50%">
</p>


---

## Code Blocks

### Regular Code

```python
def greet(name):
    print(f"Hello, {name}!")

greet("Žiga")
```



### Pseudocode
```
Algorithm BubbleSort(A)
  for i = 1 to length(A)
    for j = 1 to length(A) - i
      if A[j] > A[j+1]
        swap A[j] and A[j+1]
```
