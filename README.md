My first read me updated

```python
1 largest_palindrome = 0
  2 for i in range(100, 1000):
  3     for j in range(100, 1000):
  4         product = i * j
  5         if str(product) == str(product)[::-1] and product > largest_palindrome:
  6             largest_palindrome = product
  7
  8 # Save the result in the file "102-result"
  9 with open("102-result", "w") as file:
 10     file.write(str(largest_palindrome))
```
