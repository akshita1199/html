# 📘 HTML Code Explanation — Beginner's Guide

> Written in simple language for complete beginners. Every single tag is explained!

---

## 📄 FILE 1 — Basic HTML Page with Heading, Span, and Link

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML tutorial</title>
</head>
<body>
    <h1 title="heading one">heading</h1>
    <h2>Heading<span> two </span></h2>
    <a href="http://google.com">google</a>
    a
</body>
</html>
```

---

### 🔖 Tag-by-Tag Explanation

---

#### `<!DOCTYPE html>`
- **What it is:** This is the very FIRST line of every HTML file.
- **What it does:** It tells the browser — *"Hey! This file is written in HTML5 (the latest version)."*
- **Simple meaning:** It's like a label on a box saying what's inside.
- **Example:** Without this, the browser might display your page incorrectly.

---

#### `<html lang="en">`
- **What it is:** The root (main wrapper) tag. Everything goes inside this.
- **What it does:** Wraps the entire webpage. The `lang="en"` part tells the browser the page is written in **English**.
- **Simple meaning:** Think of it as the outer cover of a book.
- **`lang="en"`** → language = English. You could use `lang="hi"` for Hindi, etc.

---

#### `<head>`
- **What it is:** A section that holds invisible information about the page.
- **What it does:** Contains settings for the page — title, character type, screen settings, etc.
- **Simple meaning:** It's like the settings page of your phone — you don't see it on screen, but it controls a lot.
- ⚠️ Things inside `<head>` are **NOT visible** on the webpage.

---

#### `<meta charset="UTF-8">`
- **What it is:** A settings tag inside `<head>`.
- **What it does:** Tells the browser to support **all characters** — English, Hindi, emojis, symbols, etc.
- **Simple meaning:** Without this, special characters like `é`, `ñ`, `₹`, or `😊` might show as broken symbols.
- **`UTF-8`** = a universal character encoding system that supports almost every language on Earth.

---

#### `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
- **What it is:** Another settings tag inside `<head>`.
- **What it does:** Makes your webpage **look good on mobile phones and tablets**, not just computers.
- **Simple meaning:** Without this, your website would look tiny and zoomed out on a phone.
- **`width=device-width`** → match the screen width of the device.
- **`initial-scale=1.0`** → start at normal zoom level (100%).

---

#### `<title>HTML tutorial</title>`
- **What it is:** Sets the name of the browser tab.
- **What it does:** Whatever you write here appears on the **browser tab** at the top.
- **Simple meaning:** Like the title on the cover of a book.
- **Example:** You see `HTML tutorial` written on the tab in your browser.

---

#### `</head>`
- **What it is:** Closing tag for `<head>`.
- **What it does:** Marks the END of the head section.
- **Simple meaning:** Every opening tag needs a closing tag. This closes `<head>`.

---

#### `<body>`
- **What it is:** The main content section of your webpage.
- **What it does:** Everything **visible on the webpage** goes inside here — text, images, buttons, links, etc.
- **Simple meaning:** If `<head>` is the settings, `<body>` is the actual room people walk into.

---

#### `<h1 title="heading one">heading</h1>`
- **What it is:** A heading tag — the **biggest and most important** heading.
- **What it does:** Displays the word "heading" in large bold text on the screen.
- **`title="heading one"`** → This is an **attribute**. When you hover your mouse over this text, a small tooltip appears saying *"heading one"*.
- **Simple meaning:** Like the main title of a newspaper.
- **Note:** `<h1>` to `<h6>` exist — h1 is biggest, h6 is smallest.

---

#### `<h2>Heading<span> two </span></h2>`
- **What it is:** A second-level heading (slightly smaller than h1).
- **What it does:** Displays "Heading two" on the screen.
- **Simple meaning:** Like a sub-title in a book.

##### Inside this — `<span> two </span>`
- **What it is:** An inline container tag.
- **What it does:** Wraps the word " two " without adding any visible change on its own.
- **Simple meaning:** It's used to **style a specific part** of text using CSS later. Like highlighting one word in a sentence.
- **Important:** `<span>` does NOT start a new line. It stays inline with surrounding text.

---

#### `<a href="http://google.com">google</a>`
- **What it is:** An anchor tag — used to create **clickable links**.
- **What it does:** Shows the word "google" on screen, and when clicked, it opens `http://google.com`.
- **`href="http://google.com"`** → `href` means *HyperText REFerence* — it's the URL/link where you want to go.
- **Simple meaning:** Like a hyperlink in a Word document.
- **Example:** Click "google" → browser opens Google.com.

---

#### `a` (plain text, not a tag)
- **What it is:** Just the letter "a" typed directly in the body — it is **NOT a tag**.
- **What it does:** Displays the letter "a" on the webpage.
- **Simple meaning:** Any text you type directly in `<body>` (without tags) appears as-is on screen.

---

#### `</body>` and `</html>`
- **What they are:** Closing tags.
- **What they do:** Mark the end of the body and the end of the entire HTML document.
- **Note:** In your code, there are **two `</body>` tags** — this is a mistake! Only one is needed.

---

> Note: `<!DOCTYPE html>`, `<html>`, `<head>`, `<meta>`, `<title>`, `<body>` are the same as explained above. Only new tags are explained below.

---

#### `<h1>` to `<h5>` — All Heading Levels

| Tag | Size | Use it for... |
|-----|------|---------------|
| `<h1>` | Biggest | Main title of the page |
| `<h2>` | Large | Section title |
| `<h3>` | Medium-large | Sub-section title |
| `<h4>` | Medium | Smaller sub-section |
| `<h5>` | Small | Minor heading |
| `<h6>` | Smallest | Rarely used, very small |

- **Simple meaning:** Like headings in a textbook — Chapter title (h1), Topic (h2), Sub-topic (h3), and so on.
- **Important:** There is also `<h6>` which is the smallest — not used in your code but it exists.

---

#### `<p>...</p>` — Paragraph Tag

- **What it is:** Used to write a paragraph of text.
- **What it does:** Wraps a block of text and adds space above and below it automatically.
- **Simple meaning:** Like pressing Enter twice in MS Word to start a new paragraph.
- **Example:** `<p>Hello World</p>` shows "Hello World" as a paragraph.

---

#### `<hr>` — Horizontal Rule (Line)

- **What it is:** A self-closing tag (no closing tag needed).
- **What it does:** Draws a **horizontal line** across the page.
- **Simple meaning:** Like drawing a straight line with a ruler across the page to separate sections.
- ⚠️ **Note:** Using `<hr>` inside `<p>` (like in your code) is technically incorrect — `<hr>` should be outside `<p>`. But browsers usually still display it.

---

#### `<br>` — Line Break

- **What it is:** A self-closing tag (no closing tag needed).
- **What it does:** Moves the next text to a **new line**.
- **Simple meaning:** Like pressing **Enter** once on your keyboard in MS Word.
- **Difference from `<p>`:** `<br>` just moves to next line. `<p>` creates a whole new paragraph with extra space.

---

#### `<pre>...</pre>` — Preformatted Text

- **What it is:** A tag that preserves spacing and line breaks exactly as you type them.
- **What it does:** Whatever spaces, tabs, and new lines you add inside `<pre>` — they show up **exactly** on screen.
- **Simple meaning:** Normally HTML ignores extra spaces and enters. `<pre>` keeps them all.
- **Uses:** Showing code, poetry, tables made with spaces, or anything where spacing matters.
- **Example:**
  ```
  line 1
      line 2   ← the spaces are preserved!
  ```
- ⚠️ **Bug in your code:** There is a stray `</i>` tag after `line 1` — `</i>` is a closing italic tag but there's no opening `<i>` tag. This is a mistake and should be removed.

---

## 🐛 Mistakes Found in Your Code

| # | Mistake | Where | Fix |
|---|---------|-------|-----|
| 1 | Two `</body>` closing tags | File 1 | Remove the extra `</body>` |
| 2 | `<hr>` placed inside `<p>` | File 2 | Move `<hr>` outside the `<p>` tag |
| 3 | Stray `</i>` tag with no opening `<i>` | File 2, inside `<pre>` | Remove `</i>` |

---

## 💡 Quick Summary — All Tags at a Glance

| Tag | What it does | Simple meaning |
|-----|-------------|----------------|
| `<!DOCTYPE html>` | Declares HTML5 | "This is HTML!" label |
| `<html>` | Root wrapper | The whole book |
| `<head>` | Invisible settings | Phone settings page |
| `<meta charset>` | Supports all characters | Enables emojis & symbols |
| `<meta viewport>` | Mobile-friendly display | Fits on phone screen |
| `<title>` | Browser tab name | Tab label |
| `<body>` | Visible content area | The actual webpage |
| `<h1>` to `<h6>` | Headings (big to small) | Chapter titles |
| `<p>` | Paragraph | Text block |
| `<span>` | Inline wrapper | Highlight part of text |
| `<a href="">` | Clickable link | Hyperlink |
| `<hr>` | Horizontal line | Divider line |
| `<br>` | Line break | Press Enter once |
| `<pre>` | Preserves spacing | Keeps spaces as-is |

---

> ✅ **Tip for beginners:** Every opening tag `<tag>` needs a closing tag `</tag>` — except self-closing tags like `<br>`, `<hr>`, and `<meta>` which don't need a closing tag.