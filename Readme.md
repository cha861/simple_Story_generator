# Mad Libs Story Generator (Python)

This is a small Python project I built while learning Python through a YouTube tutorial. The goal of this project was to understand file handling, strings, loops, sets, and dictionaries in a practical way.

The program reads a story from a text file and turns it into a simple Mad Libs–style game by asking the user to fill in missing words.

---

## How It Works

* The story is stored in a file called `story.txt`.
* Words that need user input are wrapped inside angle brackets, like `<noun>` or `<adjective>`.
* The program scans the file and collects all such placeholders.
* It then asks the user to enter a word for each placeholder.
* Finally, it replaces the placeholders with the user’s input and prints the completed story.

---

## Example

If your `story.txt` contains:

```
Today I went to the <place> and bought a <adjective> <noun>.
```

The program will ask:

* Enter a word for `<place>`
* Enter a word for `<adjective>`
* Enter a word for `<noun>`

And then display the final story with your inputs.

---

## What I Learned

* Reading files using `open()`
* Looping through text character by character
* Using sets to avoid duplicate placeholders
* Using dictionaries to store user inputs
* Replacing text dynamically in Python

This project helped me understand how small concepts come together to build something interactive.

---

## How to Run

1. Make sure Python 3 is installed.
2. Create a `story.txt` file in the same folder as the Python script.
3. Add a story with placeholders inside `< >`.
4. Run the script:

```
python main.py
```

---

## Notes

* This project was built as part of my learning journey and is based on a YouTube tutorial.
* The focus was on understanding the logic rather than writing perfect or optimized code.

---

Thanks for checking it out!
