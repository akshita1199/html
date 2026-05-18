# 📘 HTML Formatting Tags — Beginner's Guide

> Only NEW tags are explained here. Tags already covered in previous files are skipped.

---

## `<strong>`
- Makes text **bold**.
- But it is not just about looks — it also tells the browser this text is **important**.
- Screen readers (used by blind people) will read this word with more emphasis.
- Simple meaning: Like highlighting a word in a textbook because it really matters.

---

## `<i>`
- Makes text *italic* (slanted/tilted).
- It is used for **visual styling only** — it does not say the text is important.
- Common uses: book titles, foreign words, technical terms.
- Simple meaning: Like writing a word in cursive to make it look different.

---

## `<em>`
- Also makes text *italic* — looks the same as `<i>` on screen.
- But it means **emphasis** — it tells the browser this word should be stressed.
- Screen readers will say this word with extra stress in their voice.
- Simple meaning: Like saying a word louder when you speak — *"This is IMPORTANT."*
- **Difference from `<i>`:** `<i>` is just visual styling. `<em>` means the word carries extra meaning.

---

## `<ul>`
- **Unordered List** — creates a list with bullet points (●).
- Used when the order of items does NOT matter.
- Simple meaning: Like a grocery shopping list — the order you buy items doesn't matter.
- All list items go inside `<ul>` using the `<li>` tag.

---

## `<li>`
- **List Item** — represents one item in a list.
- Always goes inside `<ul>` (bullet list) or `<ol>` (numbered list).
- Each `<li>` becomes one bullet point or one numbered item.
- Simple meaning: One line in your shopping list.

---

## `<sub>`
- **Subscript** — makes text appear **smaller and below** the normal text line.
- Common use: Chemical formulas like H₂O (water), CO₂ (carbon dioxide).
- Simple meaning: The small "2" written below in H₂O.
- Example in your code: `H<sub>2</sub>o` displays as H₂o.

---

## `<sup>`
- **Superscript** — makes text appear **smaller and above** the normal text line.
- Common use: Math powers like x², footnotes, ordinals like 1st, 2nd.
- Simple meaning: The small "2" written above in x².
- Example in your code: `H<sup>2</sup>o` displays as H²o.

---

## `<del>`
- Shows text with a **strikethrough line** through it (~~like this~~).
- Means the text has been **deleted or is no longer valid**.
- Common use: Showing old prices crossed out, corrections in documents.
- Simple meaning: Like crossing out a word with a pen.
- Example in your code: ~~thinking~~

---

## `<mark>`
- **Highlights** text with a yellow background (like a highlighter pen).
- Used to draw attention to important words or search results.
- Simple meaning: Like using a yellow marker on paper to highlight important words.
- Example in your code: the word "sales" will appear with a yellow background.

---

## `style="..."` — Inline Style Attribute
- **`style`** is an attribute that lets you add **CSS styling directly inside a tag**.
- You can change color, size, alignment, background, and more.
- In your code: `style="text-align: center; background-color: aqua;"`
  - **`text-align: center`** → moves the text to the center of the page.
  - **`background-color: aqua`** → sets the background color of that heading to aqua (light blue-green).
- Simple meaning: Like picking up a paintbrush and painting just that one line.
- ⚠️ Using `style` directly on tags works, but for bigger projects it is better to use a separate CSS file.

---

## 🐛 Mistake Found in Your Code

| # | Mistake | Where | Fix |
|---|---------|-------|-----|
| 1 | `<device-width>` wrapped in `< >` | `<meta viewport>` tag | It should be written as `device-width` not `<device-width>` |
| 2 | `<h1>` used 4 times | `<body>` | A page should ideally have only **one** `<h1>` tag |

---

## 📋 New Tags — Quick Reference

| Tag | Simple Meaning |
|-----|---------------|
| `<strong>` | Bold + marks text as important |
| `<i>` | Italic — visual styling only |
| `<em>` | Italic + marks text as emphasized |
| `<ul>` | Bullet point list |
| `<li>` | One item in a list |
| `<sub>` | Small text BELOW the line (H₂O) |
| `<sup>` | Small text ABOVE the line (x²) |
| `<del>` | Strikethrough text (~~deleted~~) |
| `<mark>` | Highlighted text (yellow background) |
| `style="..."` | Add CSS styling directly to a tag |

---

> ✅ **Tip:** `<strong>` and `<em>` are better than `<b>` and `<i>` because they carry **meaning**, not just looks. Search engines and screen readers understand them better.

# 📘 HTML Formatting Tags — Beginner's Guide

> Only NEW tags are explained here. Tags already covered in previous files are skipped.

---

## `<strong>`
- Makes text **bold**.
- But it is not just about looks — it also tells the browser this text is **important**.
- Screen readers (used by blind people) will read this word with more emphasis.
- Simple meaning: Like highlighting a word in a textbook because it really matters.

---

## `<i>`
- Makes text *italic* (slanted/tilted).
- It is used for **visual styling only** — it does not say the text is important.
- Common uses: book titles, foreign words, technical terms.
- Simple meaning: Like writing a word in cursive to make it look different.

---

## `<em>`
- Also makes text *italic* — looks the same as `<i>` on screen.
- But it means **emphasis** — it tells the browser this word should be stressed.
- Screen readers will say this word with extra stress in their voice.
- Simple meaning: Like saying a word louder when you speak — *"This is IMPORTANT."*
- **Difference from `<i>`:** `<i>` is just visual styling. `<em>` means the word carries extra meaning.

---

## `<ul>`
- **Unordered List** — creates a list with bullet points (●).
- Used when the order of items does NOT matter.
- Simple meaning: Like a grocery shopping list — the order you buy items doesn't matter.
- All list items go inside `<ul>` using the `<li>` tag.

---

## `<li>`
- **List Item** — represents one item in a list.
- Always goes inside `<ul>` (bullet list) or `<ol>` (numbered list).
- Each `<li>` becomes one bullet point or one numbered item.
- Simple meaning: One line in your shopping list.

---

## `<sub>`
- **Subscript** — makes text appear **smaller and below** the normal text line.
- Common use: Chemical formulas like H₂O (water), CO₂ (carbon dioxide).
- Simple meaning: The small "2" written below in H₂O.
- Example in your code: `H<sub>2</sub>o` displays as H₂o.

---

## `<sup>`
- **Superscript** — makes text appear **smaller and above** the normal text line.
- Common use: Math powers like x², footnotes, ordinals like 1st, 2nd.
- Simple meaning: The small "2" written above in x².
- Example in your code: `H<sup>2</sup>o` displays as H²o.

---

## `<del>`
- Shows text with a **strikethrough line** through it (~~like this~~).
- Means the text has been **deleted or is no longer valid**.
- Common use: Showing old prices crossed out, corrections in documents.
- Simple meaning: Like crossing out a word with a pen.
- Example in your code: ~~thinking~~

---

## `<mark>`
- **Highlights** text with a yellow background (like a highlighter pen).
- Used to draw attention to important words or search results.
- Simple meaning: Like using a yellow marker on paper to highlight important words.
- Example in your code: the word "sales" will appear with a yellow background.

---

## `style="..."` — Inline Style Attribute
- **`style`** is an attribute that lets you add **CSS styling directly inside a tag**.
- You can change color, size, alignment, background, and more.
- In your code: `style="text-align: center; background-color: aqua;"`
  - **`text-align: center`** → moves the text to the center of the page.
  - **`background-color: aqua`** → sets the background color of that heading to aqua (light blue-green).
- Simple meaning: Like picking up a paintbrush and painting just that one line.
- ⚠️ Using `style` directly on tags works, but for bigger projects it is better to use a separate CSS file.

---

## 🐛 Mistake Found in Your Code

| # | Mistake | Where | Fix |
|---|---------|-------|-----|
| 1 | `<device-width>` wrapped in `< >` | `<meta viewport>` tag | It should be written as `device-width` not `<device-width>` |
| 2 | `<h1>` used 4 times | `<body>` | A page should ideally have only **one** `<h1>` tag |

---

## 📋 New Tags — Quick Reference

| Tag | Simple Meaning |
|-----|---------------|
| `<strong>` | Bold + marks text as important |
| `<i>` | Italic — visual styling only |
| `<em>` | Italic + marks text as emphasized |
| `<ul>` | Bullet point list |
| `<li>` | One item in a list |
| `<sub>` | Small text BELOW the line (H₂O) |
| `<sup>` | Small text ABOVE the line (x²) |
| `<del>` | Strikethrough text (~~deleted~~) |
| `<mark>` | Highlighted text (yellow background) |
| `style="..."` | Add CSS styling directly to a tag |

---

> ✅ **Tip:** `<strong>` and `<em>` are better than `<b>` and `<i>` because they carry **meaning**, not just looks. Search engines and screen readers understand them better.
