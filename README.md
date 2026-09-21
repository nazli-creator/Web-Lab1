# Paper Moon Books

A 4-page website built with only HTML5 (no CSS, no JavaScript) for Web Programming, Assignment 1.

Author: Nazlı Mutlu

## Theme

Paper Moon Books is a fictional independent bookstore and cafe. The website shows the books and the cafe, the services and events (book club, author reading, story hour, and more), and a contact form.

## File Organization

```
.
├── index.html      Home page (header, nav, 2 articles, footer)
├── about.html      About page (section, figure, aside, time, mark, blockquote, details)
├── services.html   Services page (table with thead, tbody, tfoot)
├── contact.html    Contact page (form with fieldset, inputs, select, textarea)
├── assets/
│   └── images/     bookshelf.svg, cafe.svg
└── README.md
```

All pages use the same `<nav>` and link to each other with relative paths.

## Challenges

- **No CSS:** The pages look plain, so the structure must be clear and correct only with HTML tags.
- **Semantic tags:** It was hard to choose the right tag for each part (for example `<aside>`, `<figure>`, `<details>`) and not just use `<div>`.
- **Consistent navigation:** The same `<nav>` has to be copied to every page and all the links must work.
- **Working form:** Without JavaScript or a server, the form uses a `mailto:` action, so it only opens the user's email app.
- **Images:** I drew the two images as SVG files so I did not need to download any picture.
