# Glushak_Natalia-CA6-JS1-BIO

# CA6 – JS1: Bear Ninja Hunter (BIO)

A minimal JavaScript prototype for the **Bear–Ninja–Hunter** game built for CA6 (Basic In/Out).  
This version focuses on **input/output** only—no functions or game logic yet.

## What it does
- Prompts the player for their **name**.
- Greets the player with a personalized **alert**.
- Prompts the player for their **choice**: *Bear*, *Ninja*, or *Hunter*.
- Hard-codes the computer’s choice to **Bear** (per spec).
- Outputs the combined message **to the page** (DOM `innerHTML`) **and** the **console**.

## Run it
1. Open `index.html` in any modern browser **or** visit the deployed page:  
   **GH Pages:** `<(https://nataly5pt.github.io/LastnameFirstInitial-CA6-JS1-BIO/)>`
2. Follow the on-screen prompts.  
3. After the third prompt, check the result text on the page and open DevTools → **Console** to see the logged message.

## Project structure
/
├─ index.html
└─ css/
└─ style.css

## Tech & requirements covered
- `prompt()`, `alert()`, `console.log()`
- `document.getElementById(...).innerHTML`
- `let`/`const`, assignment `=`
- String concatenation with `+` and template literals `` `${}` ``
- Escaped apostrophe: `Let\'s`
- External CSS
- **No functions** (per assignment)
- Author meta tag:
```html
<meta name="author" content="[Your Name]">
