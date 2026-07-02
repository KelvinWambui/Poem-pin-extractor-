#Poem PIN Extractor

A beginner-friendly Python project that extracts hidden PIN codes from poems by selecting specific words from each line and counting their letters.

## 📖 How It Works

For each poem:

1. Split the poem into individual lines.
2. Select the word whose position matches the line number.
   - Line 1 → 1st word
   - Line 2 → 2nd word
   - Line 3 → 3rd word
   - and so on...
3. Count the number of letters in the selected word.
4. If a line doesn't contain the required word, use `0`.
5. Combine the numbers to create a secret PIN.

##Example

### Input

```python
poem = """Stars and the moon
shine in the sky
white and
until the end of the night"""
```

### Output

```python
['5202']
```

### Explanation

| Line | Selected Word | Length |
|------|---------------|-------:|
| Stars and the moon | Stars | 5 |
| shine in the sky | in | 2 |
| white and | Missing | 0 |
| until the end of the night | of | 2 |

PIN: **5202**

## 🚀 Technologies Used

- Python 3
- Functions
- Lists
- Loops
- String Manipulation
- Conditional Statements
- Indexing
- `enumerate()`

##Learning Objectives

This project helped me practice:

- Writing reusable functions
- Working with lists and strings
- Using loops efficiently
- Understanding indexing
- Applying conditional logic
- Building beginner-friendly algorithms


## 📄 License

This project is open source and available under the MIT License.

---
*Created as part of my Python learning journey.*
