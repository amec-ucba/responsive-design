# 📄 Responsive Design

Turn a fixed desktop page into a responsive layout that adapts to desktop, tablet, and phone
screens using CSS media queries.

**Points:** 20

## 🎯 Overview

Your visitors use screens of every size, from wide desktop monitors to small phones. A
**responsive** page rearranges itself to fit the screen it's on, instead of forcing phone
users to pinch and zoom around a desktop layout.

In this coding exercise, you start with a simple page: a header, three content boxes, and a
gallery of four images. First you build the **desktop layout**. Then you add **media
queries**, CSS rules that only apply at certain screen widths, and use them to create a
**tablet layout** and a **phone layout** for the same HTML.

You won't change much HTML in this exercise. Almost all of your work happens in
`styles.css`, and the starter file already has commented sections waiting for each layout.

> [!IMPORTANT]
> **The companion videos for this exercise are in Canvas**, on the assignment page. They
> walk you through every step, so watch them there instead of working from this file
> alone.

## 📋 Requirements

1. **Keep `index.html` in the root folder of this repo.** It's already there. GitHub Pages
   only serves `index.html` at your site's root URL, so don't rename or move it.
2. **Complete Part 1** by following the *Desktop Layout* video to style the page for large
   screens.
3. **Complete Part 2** by following the *Media Queries* video to set up the media queries
   in `styles.css`.
4. **Complete Part 3** by following the *Tablet Layout* video to rearrange the page for
   medium screens.
5. **Complete Part 4** by following the *Phone Layout* video to rearrange the page for
   small screens.
6. **Publish and submit** your page as described in the [README](README.md).

## 🧠 What You Will Learn

By completing this exercise, you will practice how to:

- Explain what responsive design is and why it matters
- Explain what the `viewport` meta tag does and why responsive pages need it
- Build a desktop layout with a centered wrapper, content boxes, and an image gallery
- Write a CSS media query with `@media` and a width condition
- Override desktop styles inside a media query for a tablet layout
- Override styles again for a phone layout, where content stacks in a single column
- Keep images inside their containers as the screen gets narrower
- Test a responsive page by resizing the browser window or using your browser's developer
  tools

## 🎬 Watch the Videos in Canvas and Follow Along

The screencast videos are on this assignment's page in **Canvas**, not in this repo. Watch
them **in order** and follow along in Visual Studio Code. Pause whenever you need time to
finish a step. It is normal to pause, rewind, and rewatch parts of a coding demonstration.

Each video builds on the previous one, so please don't skip ahead.

| Video | What you will do |
| --- | --- |
| **Introduction & Overview** | See what responsive design is, tour the starter files, and preview the desktop, tablet, and phone layouts you'll build. |
| **Part 1 — Desktop Layout** | Style the page for large screens in the *DESKTOP Layout* section of `styles.css`: the wrapper, the three content boxes in `main`, and the image gallery. |
| **Part 2 — Media Queries** | Learn how media queries work and add the `@media` rules for tablet and phone screens under the *TABLET* and *PHONE* comments in `styles.css`. |
| **Part 3 — Tablet Layout** | Inside the tablet media query, override the desktop styles so the boxes and gallery rearrange to fit a medium-width screen. |
| **Part 4 — Phone Layout** | Inside the phone media query, override the styles again so the content stacks into a single column that fits a small screen. |

> [!IMPORTANT]
> **A few steps in this repo are different from the videos.** Follow the videos for the
> CSS, and follow this repo for getting your files and submitting:
>
> - **Getting the starter files:** don't download `responsive start.zip`. Create your own
>   repo from this template and open it with GitHub Desktop, as described in the
>   [README](README.md#-getting-started). The starter files are already in the repo's
>   root folder, so there is no `responsive` folder to unzip.
> - **Naming your file:** keep the page named **`index.html`**, whatever name the video
>   uses. GitHub Pages only serves `index.html` at your site's root URL; any other name
>   gives you a 404.
> - **Submitting:** don't zip your folder or upload a file. Publish your page to GitHub
>   Pages and submit a pull request URL in Canvas, as described in the
>   [README](README.md#-submitting-the-assignment).

> [!IMPORTANT]
> Open the entire repo **folder** in VS Code, not a single HTML file. Keep `index.html`,
> `reset.css`, `styles.css`, and the `images` folder together in the root folder so the
> stylesheets and gallery images load.

## 📂 Starter Files

| File / Folder | Purpose |
| --- | --- |
| `index.html` | The page: a header, three `.box` sections inside `main`, and a `.gallery` of four images. It already includes the `viewport` meta tag and links both stylesheets. |
| `reset.css` | Removes the browser's default styles. **Don't edit this file.** |
| `styles.css` | Your stylesheet. It has starter styles plus three commented sections — *DESKTOP Layout*, *TABLET Media Query*, and *PHONE Media Query* — where your work goes. |
| `images/` | `stock01.png` through `stock04.png`, the gallery images. |

## 🧮 Grading Rubric

| Criteria | Full credit looks like | Points |
| --- | --- | --- |
| **Files & Setup** | `index.html`, `reset.css`, `styles.css`, and `images/` are in the root folder. Both stylesheets load on the live page, `reset.css` is unchanged, and the `viewport` meta tag is still in the `head`. | 2 |
| **Desktop Layout** | On a wide screen, the page matches the *Desktop Layout* video: the wrapper is centered with a sensible width, the three boxes sit side by side in `main`, and the four gallery images sit in a row. | 5 |
| **Media Queries** | `styles.css` has a working tablet media query and phone media query, written with correct `@media` syntax and the breakpoints from the *Media Queries* video. They come **after** the desktop styles, so they can override them. | 3 |
| **Tablet Layout** | At tablet widths, the boxes and gallery rearrange as shown in the *Tablet Layout* video. Nothing overflows the screen or requires horizontal scrolling. | 4 |
| **Phone Layout** | At phone widths, the boxes and gallery stack into a single column as shown in the *Phone Layout* video. Text stays readable and images fit inside the screen. | 4 |
| **Published & Submitted** | The page is live on GitHub Pages, and the pull request into `main` has every section of its template filled in. | 2 |
| | **Total** | **20** |

Each criterion is graded on the live GitHub Pages site, at desktop, tablet, and phone
widths. It earns its full points when it matches the *Full credit looks like* column.
Partial credit may be given for work that is close but not quite right, such as a tablet
layout that works but a phone layout that still overflows the screen.

## ✅ Before You Submit

Resize your browser window from wide to narrow (or use your browser's device toolbar) and
check the following:

- [ ] `index.html`, `reset.css`, `styles.css`, and `images/` are all in the root folder of
      the repo
- [ ] `reset.css` hasn't been edited
- [ ] Your styles are written in `styles.css`, not inline in the HTML
- [ ] **Desktop:** the wrapper is centered, the three boxes sit side by side, and the
      gallery images sit in a row
- [ ] `styles.css` has a tablet media query and a phone media query, below the desktop
      styles
- [ ] **Tablet:** the layout changes when the window narrows to tablet width
- [ ] **Phone:** the content stacks into one column, and nothing scrolls sideways
- [ ] All four gallery images load at every width
- [ ] You saved `styles.css` (and `index.html`, if you changed it)
- [ ] The page is live on GitHub Pages and the URL is in your pull request

## 🛠️ Troubleshooting

If something is not working, check these common issues first:

- Did you save `styles.css`? Reload the browser after every save.
- Is the layout not changing at all? Check that the media query's width condition matches
  the video, and that the window really is narrower than the breakpoint.
- Are your media queries **below** the desktop styles? Later rules win when selectors are
  equally specific, so a media query placed above the desktop styles gets overridden.
- Does every `@media` rule have its own pair of curly braces wrapped around the rules
  inside it? A media query has an outer `{` and `}` around all of its rules, and each rule
  inside has its own `{` and `}`.
- Is there a space between `and` and the parentheses, as in `@media (max-width: 800px)` or
  `@media screen and (max-width: 800px)`?
- Does every class name in your CSS match your HTML exactly? Class selectors start with a
  `.`.
- Are images spilling out of their boxes on small screens? Check that the gallery images
  have a `max-width` so they can shrink.
- Is the phone layout still zoomed out on a real phone? Make sure the `viewport` meta tag
  is still in the `head` of `index.html`.

**Having problems with the videos?**

- **Getting a warning about third-party cookies?** Try using Chrome. Safari's default
  security settings may prevent embedded Canvas videos from playing unless those settings
  are changed.
- **Getting an "Access Denied" error?** Refresh your browser. In many cases, the videos
  will load correctly after the page reloads.

## 📚 Resources

- [MDN — Responsive web design](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Responsive_Design)
- [MDN — Beginner's guide to media queries](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Media_queries)
- [MDN — Using the viewport meta element](https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Viewport_meta_element)
- [Chrome DevTools — Simulate mobile devices with device mode](https://developer.chrome.com/docs/devtools/device-mode)
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input) —
  paste your CSS in to catch missing braces and semicolons

---

The AI policy and submission instructions are in the [README](README.md).
