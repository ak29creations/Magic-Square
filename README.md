# DOB Magic Square 🎲

This is a simple web-based application that generates a **Ramanujan-style Magic Square** based on a user’s **Date of Birth (DOB)**.

The magic square is a 4×4 grid of numbers arranged such that each row, column, and diagonal adds up to the same "magic constant".

---

## Features ✨
- Accepts **date of birth** as input (using a date picker).
- Generates a **4×4 magic square** instantly.
- Displays the **magic constant** (sum of each row/column/diagonal).
- Clean, responsive UI with minimal styling.

---

## Usage 🚀
1. Open the `index.html` file in any modern web browser.
2. Select your **Date of Birth** from the date picker.
3. Click **"Make Magic Square"**.
4. The 4×4 magic square will be displayed, along with the magic constant.

---

## File Structure 📂
```
dob-magic-square/
│── index.html   # Main application file
│── README.md    # Project documentation
```

---

## How It Works ⚙️
1. The user inputs their **DOB**.
2. The script extracts:
   - Day (DD)
   - Month (MM)
   - Year (YYYY → split into two parts: YY1 and YY2)
3. These values are combined in a mathematical pattern to form a **4×4 matrix**.
4. The UI then renders the matrix and computes the **magic constant**.

---

## Example 📅
If your date of birth is **14 August 1992**:
- Day = 14
- Month = 8
- Year = 1992 → split into (19, 92)

One possible generated magic square:

| 14 | 8  | 19 | 92 |
|----|----|----|----|
| 93 | 18 | 5  | 17 |
| 6  | 16 | 94 | 17 |
| 20 | 91 | 15 | 7  |

Magic Constant = **133**

---

## Requirements 🖥️
- Any modern browser (Chrome, Edge, Firefox, Safari).
- No external libraries required.

---

## Customization 🎨
- You can adjust styling in the `<style>` block of `index.html`.
- Modify the **`generateFromDate()`** function to experiment with different number arrangements.

---

## License 📜
This project is released under the **MIT License**. You are free to use, modify, and distribute it.
