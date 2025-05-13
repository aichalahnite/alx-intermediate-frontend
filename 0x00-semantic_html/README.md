# Semantic HTML Project

## Directory: `0x00-semantic_html`
This project is part of the **ALX Intermediate Frontend Program**. It focuses on building strong foundations in **Semantic HTML**, emphasizing **accessibility**, **SEO optimization**, and the use of **ARIA roles**.

---

## 📚 Learning Objectives

- Structure web pages using semantic HTML elements like `<header>`, `<main>`, `<article>`, `<section>`, and `<footer>`.
- Improve SEO using appropriate meta tags and document structure.
- Enhance accessibility using ARIA roles and attributes.
- Follow best practices in form design and accessibility.
- Apply incremental development by building on previous tasks.

---

## ✅ Tasks Breakdown

### 0. **Creating a Structured HTML Document Using Semantic Elements**
- File: `0-index.html`
- Create a base HTML structure using semantic tags.
- Include:
  - `<header>` with a `<nav>` and 3 links
  - `<main>` with an `<article>`, `<h1>` and `<section>`
  - `<footer>` with copyright

---

### 1. **Enhancing HTML Document with Meta Tags and Title**
- File: `1-index.html`
- Copy from `0-index.html`
- Add inside `<head>`:
  - `<meta charset="utf-8">`
  - Description, keywords, author, viewport meta tags
  - `<title>` tag: `Semantic Html Blog Post`

---

### 2. **Creating a Blog Post Layout Using Semantic HTML Elements**
- File: `2-index.html`
- Copy from `1-index.html`
- Update `<header>` to include:
  - Blog title (`<h1>My Blog</h1>`)
  - `<nav>` with `<ul>` and 3 links
- Inside `<main><article>`:
  - Blog header with title and publish date
  - Three `<section>` blocks:
    - Introduction
    - Main content (includes `<figure>`, `<img>`, `<figcaption>`)
    - Conclusion
  - Article-specific `<footer>` with author and publication date

---

### 3. **Enhancing Form Accessibility with ARIA Roles and Attributes**
- File: `3-index.html`
- Copy from `2-index.html`
- Add a new `<section>` inside `<main>`:
  - Create a `<form>` with:
    - ARIA attributes (`aria-labelledby`, `aria-required`, etc.)
    - `<label>` and `<input>` for name and email
    - `<button>` with `aria-label`
    - `<div>` with `aria-live="polite"` and `role="alert"`

---

### 4. **Manual QA Review**
- Ensure all HTML code is:
  - Validated
  - Semantically structured
  - Accessible
- Push all files to the correct GitHub repo and request manual review

---

## 📁 Repository Structure
```
alx-intermediate-frontend/
└── 0x00-semantic_html/
├── 0-index.html
├── 1-index.html
├── 2-index.html
├── 3-index.html
└── README.md
```

---

## 📌 Notes

- Always validate your HTML using [W3C Validator](https://validator.w3.org/)
- Follow accessibility best practices
- Ensure all tags are properly closed
- Commit and push changes regularly

---

## 🧑‍💻 Author

- **Aicha Lahnite**
- Project from **ALX Africa Software Engineering Program**