# 🌐 Complete HTML Course for Beginners

> **Learn HTML from absolute zero and build your first complete website from scratch.**

Welcome to this beginner-friendly HTML course.

This course is designed for students who have **never written HTML before**. You don't need previous programming knowledge.

The course follows a simple rule:

> **Learn → Understand → Type → Experiment → Practice → Build**

By the end of this course, you should be able to open a blank HTML file and build a basic multi-page website **without copying someone else's code**.

---

# 📚 Table of Contents

1. [What is HTML?](#1-what-is-html)
2. [How Websites Work](#2-how-websites-work)
3. [Setting Up Your Environment](#3-setting-up-your-environment)
4. [Your First HTML Page](#4-your-first-html-page)
5. [HTML Tags and Elements](#5-html-tags-and-elements)
6. [HTML Document Structure](#6-html-document-structure)
7. [Headings and Paragraphs](#7-headings-and-paragraphs)
8. [Line Breaks and Horizontal Rules](#8-line-breaks-and-horizontal-rules)
9. [Text Formatting](#9-text-formatting)
10. [HTML Comments](#10-html-comments)
11. [Links](#11-links)
12. [Images](#12-images)
13. [Lists](#13-lists)
14. [Tables](#14-tables)
15. [HTML Attributes](#15-html-attributes)
16. [Div and Span](#16-div-and-span)
17. [File Paths](#17-file-paths)
18. [Forms](#18-forms)
19. [Input Types](#19-input-types)
20. [Form Controls](#20-form-controls)
21. [HTML Validation](#21-html-validation)
22. [Audio](#22-audio)
23. [Video](#23-video)
24. [Iframe](#24-iframe)
25. [Semantic HTML](#25-semantic-html)
26. [HTML5 Structure](#26-html5-structure)
27. [The Head Section](#27-the-head-section)
28. [Meta Tags](#28-meta-tags)
29. [HTML Entities](#29-html-entities)
30. [Accessibility](#30-accessibility)
31. [Best Practices](#31-best-practices)
32. [Common Mistakes](#32-common-mistakes)
33. [Debugging HTML](#33-debugging-html)
34. [Mini Projects](#34-mini-projects)
35. [Final Project](#35-final-project)
36. [HTML Cheat Sheet](#36-html-cheat-sheet)
37. [Final Assessment](#37-final-assessment)
38. [What to Learn After HTML](#38-what-to-learn-after-html)

---

# 1. What is HTML?

## What does HTML mean?

**HTML = HyperText Markup Language**

HTML is the standard language used to create the **structure and content of webpages**.

HTML is **not a programming language**.

It is a **markup language**.

---

## Think of a Website Like a House

Imagine building a house.

```text
HTML       → Structure
CSS        → Design
JavaScript → Behaviour
```

For example:

```text
HTML
 ├── Heading
 ├── Paragraph
 ├── Image
 ├── Button
 └── Form

CSS
 ├── Colors
 ├── Fonts
 ├── Size
 └── Layout

JavaScript
 ├── Click actions
 ├── Calculations
 ├── Animations
 └── Dynamic behaviour
```

We will focus on **HTML first**.

---

# 2. How Websites Work

When you open a website:

```text
You
 ↓
Browser
 ↓
Website files
 ↓
HTML
 ↓
Browser understands HTML
 ↓
Webpage appears
```

Common browsers:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

HTML files normally use:

```text
.html
```

Example:

```text
index.html
about.html
contact.html
```

---

# 3. Setting Up Your Environment

You need:

### 1. A browser

Chrome, Edge, Firefox, etc.

### 2. A code editor

Recommended:

**Visual Studio Code**

You can also use:

* Notepad
* Notepad++
* Sublime Text
* Any online HTML editor

---

# 4. Your First HTML Page

Create a file:

```text
index.html
```

Write:

```html
<!DOCTYPE html>

<html>

<head>
    <title>My First Website</title>
</head>

<body>

    <h1>Hello World!</h1>

    <p>This is my first webpage.</p>

</body>

</html>
```

Save it.

Then open `index.html` in your browser.

Congratulations!

You created your first webpage.

---

# 5. HTML Tags and Elements

HTML uses **tags**.

Example:

```html
<p>Hello World</p>
```

Here:

```text
<p>          Opening tag
Hello World  Content
</p>         Closing tag
```

Together they form an HTML element.

---

## Another Example

```html
<h1>My Website</h1>
```

`h1` is the heading element.

---

## Some Elements Don't Need Closing Tags

Example:

```html
<br>
```

```html
<img src="photo.jpg" alt="My photo">
```

These are called **void elements**.

Important void elements include:

```text
<br>
<hr>
<img>
<input>
<meta>
<link>
<source>
<area>
<base>
<embed>
<param>
<wbr>
```

You don't need to memorize all of them immediately.

---

# 6. HTML Document Structure

The standard basic structure is:

```html
<!DOCTYPE html>

<html>

<head>

    <title>Page Title</title>

</head>

<body>

    <!-- Visible content goes here -->

</body>

</html>
```

Understand this properly.

### `<!DOCTYPE html>`

Tells the browser that the document uses modern HTML.

### `<html>`

The root element.

### `<head>`

Contains information about the webpage.

### `<title>`

The title displayed in the browser tab.

### `<body>`

Contains the visible webpage content.

---

# 7. Headings and Paragraphs

HTML provides six heading levels.

```html
<h1>Main Heading</h1>

<h2>Second Heading</h2>

<h3>Third Heading</h3>

<h4>Fourth Heading</h4>

<h5>Fifth Heading</h5>

<h6>Sixth Heading</h6>
```

Usually:

```text
h1 → Main page heading
h2 → Major section
h3 → Subsection
h4 → Smaller subsection
```

---

## Paragraph

```html
<p>This is a paragraph.</p>
```

Example:

```html
<h1>About Me</h1>

<p>
    My name is Rahul. I am an 8th class student.
    I enjoy learning computers.
</p>
```

### Practice

Create a page about yourself containing:

* Your name
* Your school
* Your class
* Your hobbies
* Your favourite subject

---

# 8. Line Breaks and Horizontal Rules

## Line Break

```html
<p>Hello<br>World</p>
```

`<br>` moves content to the next line.

---

## Horizontal Rule

```html
<hr>
```

Example:

```html
<h1>My Website</h1>

<hr>

<p>Welcome to my website.</p>
```

---

# 9. Text Formatting

HTML provides several elements for giving meaning or emphasis to text.

---

## Bold

```html
<b>This is bold text.</b>
```

## Strong

```html
<strong>This is important.</strong>
```

`<strong>` has semantic meaning.

---

## Italic

```html
<i>This is italic text.</i>
```

## Emphasis

```html
<em>This text is emphasized.</em>
```

---

## Highlight

```html
<mark>Important text</mark>
```

---

## Small Text

```html
<small>This is small text.</small>
```

---

## Deleted Text

```html
<del>Old price: ₹500</del>
```

---

## Inserted Text

```html
<ins>New price: ₹400</ins>
```

---

## Subscript

```html
H<sub>2</sub>O
```

Output:

```text
H₂O
```

---

## Superscript

```html
x<sup>2</sup>
```

Output:

```text
x²
```

---

## Combining Formatting

```html
<p>
    I am learning
    <strong>HTML</strong>
    and I really <em>enjoy</em> it.
</p>
```

---

# 10. HTML Comments

Comments are not displayed on the webpage.

```html
<!-- This is a comment -->
```

Example:

```html
<!-- Website header starts here -->

<h1>My Website</h1>
```

Comments are useful for organizing large HTML files.

---

# 11. Links

Links are created using `<a>`.

```html
<a href="https://www.google.com">
    Google
</a>
```

---

## Open Link in New Tab

```html
<a href="https://www.google.com" target="_blank">
    Open Google
</a>
```

---

## Email Link

```html
<a href="mailto:example@gmail.com">
    Send Email
</a>
```

---

## Phone Link

```html
<a href="tel:+911234567890">
    Call Us
</a>
```

---

## Internal Link

Suppose you have:

```text
index.html
about.html
```

Then:

```html
<a href="about.html">
    About Me
</a>
```

---

## Link to a Section

```html
<a href="#contact">
    Contact
</a>

<section id="contact">

    <h2>Contact Me</h2>

</section>
```

---

# 12. Images

Use:

```html
<img src="photo.jpg" alt="My photo">
```

### Important attributes

```text
src → image location
alt → alternative text
```

---

## Image Size

```html
<img
    src="photo.jpg"
    alt="Mountain"
    width="400"
    height="300"
>
```

---

## Image Folder

Suppose:

```text
website/
│
├── index.html
│
└── images/
    └── mountain.jpg
```

Use:

```html
<img
    src="images/mountain.jpg"
    alt="Mountain"
>
```

---

## Important Rule

Always try to provide useful `alt` text.

Good:

```html
<img src="dog.jpg" alt="Brown dog sitting in a garden">
```

Bad:

```html
<img src="dog.jpg">
```

---

# 13. Lists

## Unordered List

```html
<ul>

    <li>Apple</li>
    <li>Mango</li>
    <li>Banana</li>

</ul>
```

---

## Ordered List

```html
<ol>

    <li>Wake up</li>
    <li>Go to school</li>
    <li>Study</li>

</ol>
```

---

## Nested List

```html
<ul>

    <li>
        Programming

        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
        </ul>

    </li>

</ul>
```

---

## Description List

HTML also supports:

```html
<dl>

    <dt>HTML</dt>
    <dd>Markup language used to structure webpages.</dd>

    <dt>CSS</dt>
    <dd>Language used to style webpages.</dd>

</dl>
```

Important elements:

```text
<dl> → Description list
<dt> → Term
<dd> → Description
```

---

# 14. Tables

Basic table:

```html
<table border="1">

    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>Class</th>
    </tr>

    <tr>
        <td>Rahul</td>
        <td>13</td>
        <td>8</td>
    </tr>

    <tr>
        <td>Aman</td>
        <td>14</td>
        <td>8</td>
    </tr>

</table>
```

---

## Table Elements

```text
<table> → Table
<tr>    → Table row
<th>    → Table heading
<td>    → Table data
```

---

## Colspan

```html
<table border="1">

    <tr>
        <th>Name</th>
        <th>Marks</th>
    </tr>

    <tr>
        <td colspan="2">Total Students: 20</td>
    </tr>

</table>
```

---

## Rowspan

```html
<table border="1">

    <tr>
        <th rowspan="2">Class 8</th>
        <td>Rahul</td>
    </tr>

    <tr>
        <td>Aman</td>
    </tr>

</table>
```

---

## Better Table Structure

HTML also supports:

```html
<table>

    <caption>Student Marks</caption>

    <thead>
        <tr>
            <th>Name</th>
            <th>Math</th>
            <th>Science</th>
        </tr>
    </thead>

    <tbody>

        <tr>
            <td>Rahul</td>
            <td>90</td>
            <td>85</td>
        </tr>

    </tbody>

    <tfoot>

        <tr>
            <td colspan="3">End of table</td>
        </tr>

    </tfoot>

</table>
```

---

# 15. HTML Attributes

Attributes provide additional information about an element.

Example:

```html
<a href="https://google.com" target="_blank">
    Google
</a>
```

Here:

```text
href   → Attribute
target → Attribute
```

---

## Common Attributes

Important attributes to know:

```text
id
class
title
style
href
src
alt
width
height
name
value
placeholder
required
disabled
readonly
checked
selected
min
max
minlength
maxlength
```

---

## ID

```html
<h1 id="main-title">
    My Website
</h1>
```

An `id` should identify a specific element.

---

## Class

```html
<p class="important">
    This is important.
</p>
```

Classes are commonly used by CSS and JavaScript.

---

## Title

```html
<p title="This is additional information">
    Hover over me.
</p>
```

---

# 16. Div and Span

## `<div>`

`div` is a general-purpose block container.

```html
<div>

    <h2>About Me</h2>

    <p>
        I am a student.
    </p>

</div>
```

---

## `<span>`

`span` is an inline container.

```html
<p>
    My favourite color is
    <span>blue</span>.
</p>
```

Remember:

```text
div   → Block-level container
span  → Inline container
```

---

# 17. File Paths

Understanding file paths is essential.

Suppose:

```text
website/
│
├── index.html
│
├── about.html
│
└── images/
    └── photo.jpg
```

From `index.html`:

```html
<img src="images/photo.jpg">
```

---

## Subfolder

```html
<a href="pages/about.html">
    About
</a>
```

---

## Parent Folder

Suppose:

```text
website/
│
├── index.html
│
└── pages/
    └── about.html
```

From `about.html`:

```html
<a href="../index.html">
    Home
</a>
```

`..` means:

> Go to the parent directory.

---

# 18. Forms

Forms collect information from users.

Basic form:

```html
<form>

    <label>Name:</label>

    <input type="text">

    <br><br>

    <label>Email:</label>

    <input type="email">

    <br><br>

    <input type="submit">

</form>
```

---

# 19. Input Types

HTML provides many input types.

## Text

```html
<input type="text">
```

## Password

```html
<input type="password">
```

## Email

```html
<input type="email">
```

## Number

```html
<input type="number">
```

## Date

```html
<input type="date">
```

## Time

```html
<input type="time">
```

## File

```html
<input type="file">
```

## Checkbox

```html
<input type="checkbox">
```

## Radio

```html
<input type="radio">
```

## Color

```html
<input type="color">
```

## Range

```html
<input type="range">
```

## Search

```html
<input type="search">
```

## URL

```html
<input type="url">
```

## Telephone

```html
<input type="tel">
```

## Submit

```html
<input type="submit">
```

## Reset

```html
<input type="reset">
```

---

# 20. Form Controls

## Label

Correct form structure:

```html
<label for="name">
    Name:
</label>

<input
    type="text"
    id="name"
>
```

The `for` value connects with the input's `id`.

---

## Placeholder

```html
<input
    type="text"
    placeholder="Enter your name"
>
```

---

## Radio Buttons

```html
<p>Select your gender:</p>

<label>
    <input type="radio" name="gender" value="male">
    Male
</label>

<label>
    <input type="radio" name="gender" value="female">
    Female
</label>
```

The same `name` groups the radio buttons.

---

## Checkboxes

```html
<p>Select your hobbies:</p>

<label>
    <input type="checkbox" name="hobby">
    Cricket
</label>

<label>
    <input type="checkbox" name="hobby">
    Gaming
</label>

<label>
    <input type="checkbox" name="hobby">
    Reading
</label>
```

---

## Dropdown

```html
<label for="city">
    Choose your city:
</label>

<select id="city">

    <option>Delhi</option>
    <option>Kolkata</option>
    <option>Mumbai</option>
    <option>Patna</option>

</select>
```

---

## Textarea

```html
<label for="message">
    Message:
</label>

<textarea
    id="message"
    rows="5"
    cols="30"
></textarea>
```

---

## Button

```html
<button type="button">
    Click Me
</button>
```

Submit:

```html
<button type="submit">
    Submit
</button>
```

Reset:

```html
<button type="reset">
    Reset
</button>
```

---

# 21. HTML Validation

HTML can perform basic form validation.

## Required

```html
<input type="text" required>
```

The user cannot submit the form without filling it.

---

## Email

```html
<input type="email" required>
```

---

## Minimum and Maximum

```html
<input
    type="number"
    min="1"
    max="100"
>
```

---

## Minimum Length

```html
<input
    type="text"
    minlength="3"
>
```

---

## Maximum Length

```html
<input
    type="text"
    maxlength="20"
>
```

---

## Pattern

HTML can also use patterns:

```html
<input
    type="text"
    pattern="[A-Za-z]+"
>
```

---

# 22. Audio

```html
<audio controls>

    <source
        src="music.mp3"
        type="audio/mpeg"
    >

    Your browser does not support audio.

</audio>
```

Useful attributes:

```text
controls
autoplay
loop
muted
```

---

# 23. Video

```html
<video
    width="500"
    controls
>

    <source
        src="video.mp4"
        type="video/mp4"
    >

    Your browser does not support video.

</video>
```

Useful attributes:

```text
controls
autoplay
loop
muted
poster
width
height
```

---

# 24. Iframe

An iframe embeds another document or supported external content.

Example:

```html
<iframe
    src="https://example.com"
    width="600"
    height="400">
</iframe>
```

You may also encounter iframes when embedding:

* YouTube videos
* Maps
* Other external content

---

# 25. Semantic HTML

Semantic elements tell us what different parts of a webpage mean.

Important semantic elements:

```text
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
<figure>
<figcaption>
<address>
<time>
```

---

## Example

```html
<body>

    <header>

        <h1>My Website</h1>

    </header>

    <nav>

        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>

    </nav>

    <main>

        <section>

            <h2>About Me</h2>

            <p>
                I am an 8th class student.
            </p>

        </section>

        <section>

            <h2>My Hobbies</h2>

            <p>
                I enjoy cricket and programming.
            </p>

        </section>

    </main>

    <footer>

        <p>© 2026 My Website</p>

    </footer>

</body>
```

---

# 26. HTML5 Structure

A complete modern HTML page can look like this:

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>My Website</title>

</head>

<body>

    <header>

        <h1>My Website</h1>

    </header>

    <nav>

        <a href="index.html">Home</a>
        <a href="about.html">About</a>

    </nav>

    <main>

        <section>

            <h2>Welcome</h2>

            <p>
                Welcome to my website.
            </p>

        </section>

    </main>

    <footer>

        <p>© 2026 My Website</p>

    </footer>

</body>

</html>
```

---

# 27. The `<head>` Section

The `<head>` contains information about the document.

Common elements:

```html
<head>

    <title>My Website</title>

    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <meta
        name="description"
        content="My personal website"
    >

</head>
```

Later, CSS and external resources are also commonly connected here.

---

# 28. Meta Tags

## Character Encoding

```html
<meta charset="UTF-8">
```

This allows the browser to correctly interpret many characters.

---

## Responsive Viewport

```html
<meta
    name="viewport"
    content="width=device-width, initial-scale=1.0"
>
```

This is important for mobile-friendly webpages.

---

## Description

```html
<meta
    name="description"
    content="A personal website created using HTML."
>
```

---

# 29. HTML Entities

Sometimes special characters need to be represented using entities.

```text
&lt;     <
&gt;     >
&amp;    &
&nbsp;   space
&quot;   "
&apos;   '
&copy;   ©
&reg;    ®
```

Example:

```html
<p>
    Copyright &copy; 2026
</p>
```

---

# 30. Accessibility

A good webpage should be usable by as many people as possible.

## Use meaningful headings

Good:

```html
<h1>My School</h1>

<h2>About Our School</h2>

<h2>Our Teachers</h2>
```

Don't randomly use headings just because they look large.

---

## Use `alt`

```html
<img
    src="school.jpg"
    alt="Front view of our school building"
>
```

---

## Use labels

Good:

```html
<label for="email">
    Email:
</label>

<input
    type="email"
    id="email"
>
```

---

## Use semantic HTML

Prefer:

```html
<header>
<nav>
<main>
<section>
<footer>
```

when those elements accurately describe the content.

---

# 31. Best Practices

Follow these rules.

### 1. Use lowercase tags

Prefer:

```html
<h1>Hello</h1>
```

Instead of:

```html
<H1>Hello</H1>
```

---

### 2. Indent your code

Bad:

```html
<body><h1>Hello</h1><p>Hello World</p></body>
```

Good:

```html
<body>

    <h1>Hello</h1>

    <p>
        Hello World
    </p>

</body>
```

---

### 3. Use meaningful names

Good:

```html
<section id="about">
```

Bad:

```html
<section id="x1">
```

---

### 4. Always close normal elements

Good:

```html
<p>Hello</p>
```

---

### 5. Don't use HTML for styling everything

HTML provides structure.

CSS should handle most visual styling.

---

# 32. Common Mistakes

## Mistake 1

Forgetting closing tags:

```html
<p>Hello
```

Better:

```html
<p>Hello</p>
```

---

## Mistake 2

Wrong nesting:

Bad:

```html
<p>
    <strong>Hello
</p>
</strong>
```

Good:

```html
<p>
    <strong>Hello</strong>
</p>
```

---

## Mistake 3

Wrong image path

```html
<img src="photo.jpg">
```

when the image is actually:

```text
images/photo.jpg
```

Correct:

```html
<img src="images/photo.jpg">
```

---

## Mistake 4

Forgetting quotes around attributes

Bad:

```html
<a href=https://google.com>
```

Good:

```html
<a href="https://google.com">
```

---

## Mistake 5

Using `<br>` everywhere to create spacing

Don't use:

```html
<br><br><br><br><br>
```

for layout.

CSS should handle spacing.

---

# 33. Debugging HTML

Errors are normal.

When something doesn't work:

### Step 1

Read your code carefully.

### Step 2

Check:

* Closing tags
* Quotes
* File names
* Folder names
* Image paths
* Link paths
* Attribute spelling

### Step 3

Open browser developer tools.

Usually:

```text
Right Click → Inspect
```

Then look at:

```text
Console
Elements
```

---

## Debugging Challenge

Take:

```html
<h1>My Website</h1>

<p>This is my website.

<img src="photo.png" alt="My photo">

<a href="about.html">About Me</a>
```

Find what is wrong.

Answer:

The paragraph is not closed.

Correct:

```html
<h1>My Website</h1>

<p>
    This is my website.
</p>

<img
    src="photo.png"
    alt="My photo"
>

<a href="about.html">
    About Me
</a>
```

---

# 34. Mini Projects

Don't move forward without practicing.

---

## 🟢 Project 1 — My Introduction

Create:

```text
my-introduction/
└── index.html
```

Must contain:

* Your name
* Your class
* Your school
* A paragraph about yourself
* Favourite subject
* Hobbies

---

## 🟢 Project 2 — Favourite Things

Create a webpage containing:

* Favourite food
* Favourite sport
* Favourite game
* Favourite movie
* Favourite subject

Use:

* Headings
* Paragraphs
* Lists
* Images
* Links

---

## 🟡 Project 3 — Student Marks Table

Create:

```text
student-marks/
└── index.html
```

Table should contain:

```text
Name
English
Math
Science
Computer
Total
```

---

## 🟡 Project 4 — Registration Form

Create:

```text
registration-form/
└── index.html
```

Include:

* Name
* Email
* Password
* Phone
* Date of birth
* Gender
* Hobbies
* Class
* City
* Address
* Submit
* Reset

Use validation wherever appropriate.

---

## 🔵 Project 5 — Personal Profile

Create:

```text
profile/
│
├── index.html
└── images/
    └── profile.jpg
```

Include:

* Profile image
* Name
* Introduction
* Education
* Hobbies
* Skills
* Favourite subjects
* Contact information

---

## 🔵 Project 6 — School Website

Create:

```text
school-website/
│
├── index.html
├── about.html
├── teachers.html
├── students.html
├── contact.html
└── images/
```

Every page should have navigation.

---

# 35. FINAL PROJECT — Complete Personal Website

This is the final HTML challenge.

The student must build the entire project independently.

## Project Structure

```text
my-personal-website/
│
├── index.html
├── about.html
├── hobbies.html
├── gallery.html
├── contact.html
│
├── images/
│   ├── profile.jpg
│   ├── hobby.jpg
│   └── gallery1.jpg
│
└── media/
    ├── video.mp4
    └── music.mp3
```

---

# Home Page

`index.html`

Must contain:

* Header
* Website title
* Navigation
* Introduction
* Profile image
* About section
* Hobbies section
* Link to other pages
* Footer

Example structure:

```html
<header>

    <h1>My Personal Website</h1>

    <nav>

        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="hobbies.html">Hobbies</a>
        <a href="gallery.html">Gallery</a>
        <a href="contact.html">Contact</a>

    </nav>

</header>

<main>

    <section>

        <h2>Hello!</h2>

        <p>
            Welcome to my personal website.
        </p>

        <img
            src="images/profile.jpg"
            alt="My profile photo"
            width="250"
        >

    </section>

</main>

<footer>

    <p>© 2026 My Website</p>

</footer>
```

---

# About Page

`about.html`

Include:

* About yourself
* Education
* Goals
* Favourite subjects
* Skills

---

# Hobbies Page

`hobbies.html`

Include:

* Favourite hobbies
* Ordered/unordered lists
* Images
* Descriptions

---

# Gallery Page

`gallery.html`

Include:

* At least 6 images
* Meaningful `alt` text
* Image captions

Example:

```html
<figure>

    <img
        src="images/gallery1.jpg"
        alt="Mountain landscape"
        width="300"
    >

    <figcaption>
        My favourite mountain view
    </figcaption>

</figure>
```

---

# Contact Page

`contact.html`

Create a complete form:

```html
<form>

    <label for="name">
        Name:
    </label>

    <input
        type="text"
        id="name"
        name="name"
        required
    >

    <br><br>

    <label for="email">
        Email:
    </label>

    <input
        type="email"
        id="email"
        name="email"
        required
    >

    <br><br>

    <label for="message">
        Message:
    </label>

    <textarea
        id="message"
        name="message"
        rows="5"
        required
    ></textarea>

    <br><br>

    <button type="submit">
        Send
    </button>

</form>
```

---

# 36. HTML Cheat Sheet

## Document

```html
<!DOCTYPE html>
<html>
<head>
<title>
</title>
</head>
<body>
</body>
</html>
```

---

## Text

```html
<h1>
<h2>
<h3>
<h4>
<h5>
<h6>

<p>
<br>
<hr>

<b>
<strong>
<i>
<em>
<mark>
<small>
<del>
<ins>
<sub>
<sup>
```

---

## Links

```html
<a>
```

Important attributes:

```text
href
target
download
```

---

## Images

```html
<img>
```

Important attributes:

```text
src
alt
width
height
```

---

## Lists

```html
<ul>
<ol>
<li>

<dl>
<dt>
<dd>
```

---

## Tables

```html
<table>
<caption>
<thead>
<tbody>
<tfoot>
<tr>
<th>
<td>
```

Important attributes:

```text
colspan
rowspan
```

---

## Containers

```html
<div>
<span>
```

---

## Semantic HTML

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
<figure>
<figcaption>
<address>
<time>
```

---

## Forms

```html
<form>
<label>
<input>
<textarea>
<select>
<option>
<button>
<fieldset>
<legend>
<datalist>
<output>
```

---

## Media

```html
<audio>
<video>
<source>
<track>
<iframe>
```

---

## Head

```html
<head>
<title>
<meta>
<link>
<style>
<base>
```

---

# 37. Final Assessment

Before saying:

> "I have completed HTML."

You should be able to answer **YES** to all of these.

## Basic Understanding

* [ ] I know what HTML is.
* [ ] I know the difference between HTML, CSS and JavaScript.
* [ ] I understand tags and elements.
* [ ] I understand opening and closing tags.
* [ ] I understand the basic HTML document structure.

## Text

* [ ] I can create headings.
* [ ] I can create paragraphs.
* [ ] I can format text.
* [ ] I can use lists.
* [ ] I can use comments.

## Links and Images

* [ ] I can create links.
* [ ] I can link different HTML pages.
* [ ] I can open a link in another tab.
* [ ] I can add images.
* [ ] I understand `src` and `alt`.

## Tables

* [ ] I can create tables.
* [ ] I understand rows and columns.
* [ ] I can use `thead`, `tbody` and `tfoot`.
* [ ] I understand `colspan`.
* [ ] I understand `rowspan`.

## Forms

* [ ] I can create forms.
* [ ] I can create text inputs.
* [ ] I can create email inputs.
* [ ] I can create password inputs.
* [ ] I can create radio buttons.
* [ ] I can create checkboxes.
* [ ] I can create dropdowns.
* [ ] I can create textareas.
* [ ] I can create submit/reset buttons.
* [ ] I understand `label`.
* [ ] I can use basic HTML validation.

## Structure

* [ ] I understand `div`.
* [ ] I understand `span`.
* [ ] I understand semantic HTML.
* [ ] I can create a header.
* [ ] I can create navigation.
* [ ] I can create sections.
* [ ] I can create a footer.

## Media

* [ ] I can add audio.
* [ ] I can add video.
* [ ] I understand iframe.

## Files

* [ ] I understand folders.
* [ ] I understand relative paths.
* [ ] I can connect multiple HTML pages.
* [ ] I can organize images and media.

## Accessibility

* [ ] I use meaningful `alt` text.
* [ ] I use labels for forms.
* [ ] I use headings logically.
* [ ] I understand why semantic HTML matters.

## Independent Building

Most importantly:

* [ ] I can create a webpage without following a tutorial.
* [ ] I can find and fix basic HTML errors.
* [ ] I can build a multi-page website independently.
* [ ] I can explain what my HTML code does.

---

# 🧠 The Golden Rule

Don't learn HTML by memorizing tags.

Learn HTML by asking:

> **"What does this content mean?"**

For example:

If you need a main heading:

```html
<h1>My School</h1>
```

If you need a paragraph:

```html
<p>My school is a wonderful place.</p>
```

If you need a navigation link:

```html
<a href="about.html">About</a>
```

If you need an image:

```html
<img src="school.jpg" alt="Our school">
```

If you need a list:

```html
<ul>
    <li>Math</li>
    <li>Science</li>
    <li>Computer</li>
</ul>
```

HTML becomes much easier when you think about **meaning instead of memorization**.

---

# 🚫 Don't Copy-Paste Everything

Copying code can make a webpage appear to work while teaching you almost nothing.

For every example:

1. Read it.
2. Understand it.
3. Type it yourself.
4. Change something.
5. Break something intentionally.
6. Fix it.
7. Build your own version.

If you can only build the webpage while looking at the tutorial, **you haven't learned it yet.**

---

# 🎯 The Real Goal

The final goal isn't:

> "I know 100 HTML tags."

The final goal is:

> **Give me a blank folder and a blank HTML file, and I can create a working website myself.**

Once you can do that, you're ready for the next stage:

```text
HTML
  ↓
CSS
  ↓
Responsive Design
  ↓
JavaScript
  ↓
Git & GitHub
  ↓
Real Projects
```

---

# 🚀 What Comes After HTML?

After completing this course, start learning:

## 1. CSS

Learn:

* Colors
* Fonts
* Borders
* Margins
* Padding
* Box model
* Flexbox
* Grid
* Positioning
* Responsive design
* Animations
* Media queries

## 2. JavaScript

Learn:

* Variables
* Data types
* Conditions
* Loops
* Functions
* Arrays
* Objects
* DOM
* Events
* Forms
* APIs

## 3. Git & GitHub

Learn:

* Repository
* Commit
* Push
* Pull
* Branch
* GitHub Pages

Then start building real projects.

---

# 👨‍💻 Learning Philosophy

This repository is designed around one idea:

> **Don't just consume tutorials. Build things.**

Every topic should eventually become a project.

Every project should eventually become something you can show someone.

And every mistake should become something you understand.

---

## ⭐ Final Challenge

Close this README.

Open VS Code.

Create:

```text
index.html
```

Don't search for a template.

Don't copy the final project.

Don't ask someone for the code.

Start with:

```html
<!DOCTYPE html>
```

and build your own website.

If you can do that successfully, **you have actually learned HTML.**

---

## 📌 Course Status

```text
HTML Beginner → Intermediate

Progress:
[ ] Not Started
[ ] Basics
[ ] Content
[ ] Forms
[ ] Media
[ ] Semantic HTML
[ ] Accessibility
[ ] Mini Projects
[ ] Final Project
[ ] Independent Website
```

---

## 👨‍🏫 Created for Learning

**HTML Learning Repository**

Built to make HTML understandable for beginners and practical enough to create real websites.

**Learn → Practice → Build → Break → Fix → Repeat.**
