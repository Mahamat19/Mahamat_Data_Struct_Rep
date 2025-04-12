```yaml
site_name: Array Class Docs
theme:
  name: material

nav:
  - Home: index.md
```

---

### 📄 `docs/index.md`

```markdown
# Array Class Documentation

This is a custom implementation of a dynamic array in Python.

---

## Class: `Array`

### Constructor

```python
Array(cap=5)
```

Initializes the array with a given capacity (default is 5).

- **Parameters:**
  - `cap` *(int)*: Initial capacity of the array. Default is 5.

---

### Method: `append(value)`

Adds a new value at the end of the array.

```python
array.append(value)
```

- Automatically resizes the array if capacity is exceeded.

---

### Method: `pop()`

Removes and returns the last item.

```python
value = array.pop()
```

- Raises `IndexError` if the array is empty.

---

### Method: `get(index)`

Returns the element at the given index.

```python
value = array.get(index)
```

- Raises `IndexError` if the index is out of bounds.

---

### Method: `last()`

Returns the last item without removing it.

```python
value = array.last()
```

- Returns `None` if the array is empty.

---

### Method: `is_empty()`

Checks if the array is empty.

```python
array.is_empty()
```

- Returns `True` if empty, otherwise `False`.

---

### Internal Method: `_resize()`

Doubles the array's capacity. Used internally by `append`.

---

### Magic Method: `__str__()`

Returns a string representation of the array (up to current size).

```python
print(array)
```

---

### 🔍 Example Usage

```python
arr = Array()
arr.append(1)
arr.append(2)
print(arr.get(1))      # 2
print(arr.pop())       # 2
print(arr.is_empty())  # False
print(arr)             # [1]
```
```

---

Let me know if you want:
- A downloadable ZIP of this project
- It hosted on GitHub Pages
- To add extra pages (like tests or implementation notes)