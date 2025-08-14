# Odin Recipes

## Phase 1 – Original Project (HTML-only)

This is the recipe project from TOP to close the basics of HTML and move onto the basics of CSS.

In this project, I set up the landing page by using the name `index.html`, which automatically tells the browser that it is the landing page. I also made another directory within the directory where `index.html` sits, named `recipes`, which contains other HTML files with different recipes I can link to from the landing page using a relative link.

Boilerplate at this point is memorised, but it's much easier to just type `!` then **Tab** to get the template, then change the title and add stuff to it.

The index page is very bare — it only consists of the boilerplate, an `<h1>` element, an unordered list, and the relative links to the 3 recipe pages.

The mango sorbet page was first and also used the `!` and Tab for the boilerplate. I followed the instructions on TOP for how it should look and created a template out of it, which I then used for the other 2 recipe pages, just changing the visible content to match the recipe. The overall code didn’t change — just extra or fewer `<li>` elements.

There were 4 iterations of the website, and for each iteration I made sure to `git add .` and `git commit`, adding either just a title or a title and body depending on how many new things were added in that iteration.

Learning outcomes so far: basics of HTML (boilerplate, elements, absolute vs. relative links), basics of Git, and “learn to learn” skills.

---

## Phase 2 – Post-Overhaul (HTML + CSS)

After completing the initial HTML-only version, I came back and transformed it into a fully styled, modernized version with the following improvements:

- Created a **site-wide `styles.css`** for typography, layout, and reusable UI components.
- Redesigned navigation as **custom-styled buttons** with hover and active effects (all CSS, no JavaScript).
- Standardized the layout of all recipe pages with **containers, margins, and centered content**.
- Added an **archive folder `/old`** containing the original HTML versions.
- Linked between the “new” and “old” pages with buttons for side-by-side comparison.
- Added a **hidden clickable “Odin” Easter egg** on the landing page that reveals the old index.
- Included **flavor text** on the landing page.
- Consolidated repeated styling into **reusable CSS classes**.

---

### Reflections
The original HTML version was a functional learning exercise. The CSS overhaul turned it into a polished site while keeping it pure HTML + CSS. The “old” archive is a fun comparison tool and a reminder of how far the project has come.
