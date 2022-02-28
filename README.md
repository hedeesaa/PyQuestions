# PyQuestions

It started to post some Python Questions on my [Instagram](https://www.instagram.com/hedeesaa) stories, just for fun! But as I saw people's enthusiasm for answering questions, I decided to gather these questions here too, with their solutions.

It's just for fun, good luck! 🍷

**PS**: I got the idea from [Lydia Hallie](https://github.com/lydiahallie/javascript-questions), you should definitly check her repo if you are a JS fan! ❤️

---

## Questions

#### 1. What's the output?

```python
def hello_world():
    return "Hello", "World!"

def good(s1, s2):
    return f"{s1} Good {s2}"

print(good(hello_world()))
```

- A: `Error`
- B: `"Hello Good World"`

<details><summary><b>Answer</b></summary>
<p>

#### Answer: A

Python returns objects in Tuple!  
So the output of the `hello_world()` is the Tuple of `("Hello","World")`.
When we use it as a input for `good()` function, it will act as the first argument of the function which means `s1`.

</p>
</details>

---

#### 2. What's the output? If user types "Hedeesaa".

```python
print(len(input("What is your name?")))
```

- A: `Error`
- B: `0`
- C: `18`
- D: `8`

<details><summary><b>Answer</b></summary>
<p>

#### Answer: D

Python executes functions from inner to outter!  
So `input("What is your name?")` will be run first, then user enters "Hedeesaa".  
After that method `len()` will be run over `"Hedeesaa"`. So `len()` will show the length of `"Hedeesaa"` which is `8` :)

</p>
</details>

---
