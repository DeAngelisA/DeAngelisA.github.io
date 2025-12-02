# Updating the Website

This document provides instructions on how to update the content of your academic website.

## 1. Adding News Posts
To add a new blog post or update:
1.  Create a new folder in `posts/` (e.g., `posts/my-new-post/`).
2.  Create an `index.qmd` file inside that folder.
3.  Add the YAML header:
    ```yaml
    ---
    title: "My New Post"
    date: "2024-12-02"
    categories: [news, research]
    ---
    ```
4.  Write your content below the header.

## 2. Updating Research
To add a new publication to `research.qmd`:
1.  Copy an existing `::: {.pub-card}` block.
2.  Paste it at the top of the list.
3.  Update the title, authors, journal, and link.
4.  To add a badge, use the span syntax: `[Badge Text]{.badge-custom .badge-gold}` (or `.badge-blue`).

## 3. Updating Teaching
To update courses in `teaching.qmd`:
1.  Edit the text inside the `::: {.course-card}` blocks.
2.  To change the image, replace the file in `files/` (e.g., `files/course-causal.png`) or update the CSS `style="background-image: url(...)"` path.

## 4. Updating CV
Simply replace the `files/CV_DeAngelis.pdf` file with your new PDF. Ensure the filename remains exactly the same to avoid breaking links.

## 5. Previewing Changes
Always preview your changes before deploying:
```bash
quarto preview
```
