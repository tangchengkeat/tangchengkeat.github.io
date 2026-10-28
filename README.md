# tangchengkeat.github.io

Personal academic website of Cheng Keat Tang, published with GitHub Pages at https://tangchengkeat.github.io.

## Structure

| File | Page |
| --- | --- |
| `index.html` | Home |
| `research.html` | Research |
| `cv.html` | CV |
| `teaching.html` | Teaching |
| `css/style.css` | Shared stylesheet |

The site is plain HTML and CSS. It needs no build step.

## Updating a page

1. Open the file on GitHub and select the pencil icon (Edit).
2. Copy an existing entry, paste it in the right place and change the text and links.
3. Select **Commit changes**. The live site updates within one to two minutes.

A paper entry on the Research page follows this pattern:

```html
<li>
  <a class="pub-title" href="LINK-TO-JOURNAL">Paper Title</a>.
  <span class="pub-authors">With Co-author (Institution).</span>
  <span class="pub-venue">Journal Name Volume, Article (Year)</span>
  <span class="pub-links"><a href="LINK">Ungated version</a></span>
</li>
```

For a paper without a journal link, replace `<a class="pub-title" href="...">...</a>` with `<span class="pub-title">...</span>`. For a status label such as "Submitted", add `<span class="pub-status">Submitted</span>`.
