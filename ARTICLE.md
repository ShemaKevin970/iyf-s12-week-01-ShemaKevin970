# Semantic HTML & Accessibility: What I Learned and Fixed

## Introduction
For Task 2.5, I reviewed my portfolio website (ShemaKevin970-portfolio) to improve its structure and accessibility. I realized I was using too many non-semantic `<div>` tags.

## Problems I Found Before

1.  Used `<div class="navbar">` instead of `<nav>`
2.  Used `<div class="header">` for the top section
3.  Used `<div>` to create buttons instead of `<button>` or `<a>`
4.  Images had no `alt` attributes, e.g., `<img src="profile.jpg">`
5.  No `<main>`, `<section>`, `<footer>` tags - everything was in divs
6.  Form inputs had no `<label>` linked to them

## What I Fixed

### 1. Semantic Structure
**Before:**
```html
<div class="header">
  <div class="nav">...</div>
</div>
