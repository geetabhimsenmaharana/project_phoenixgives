# PhoenixGives

A small, personal initiative: every Saturday, give something away — clothes, food, books, or anything still useful — wrapped with a handwritten note and offered freely.

This repository contains the source code for the PhoenixGives website.

## About

PhoenixGives is rooted in the idea of **seva** — service offered without attachment or expectation. It's currently run by one person, with one Instagram page, and a stack of old newspapers used to wrap each week's gift.

> "This is yours. Take it freely. You deserve this."
> — PhoenixGives

## Pages

| File | Description |
|---|---|
| `index.html` | Home page — mission, the Saturday ritual, and an Instagram preview |
| `stories.html` | Stories from past Saturdays — real (or sample) entries of what's been given |
| `connect.html` | How to follow along, ask for help, or get involved |
| `style.css` | Shared styling for all pages (colors, fonts, layout) |

## Editing the site

This is a static site — no build tools, no dependencies. To make changes:

1. Open any `.html` file in a text editor.
2. Edit the text directly inside the relevant tags.
3. To add or change photos, replace the `src="..."` link inside an `<img>` tag with a link to your own image (or a local file path if you upload images to this repo).
4. Save, then commit and push to GitHub.

### Updating the Instagram link

Search for `instagram.com` in each HTML file and replace it with your real Instagram profile URL.

### Adding a new story

Open `stories.html` and copy one of the existing `<article class="story">...</article>` blocks, then edit the text, image, and date inside it.

## Hosting

This site can be hosted for free using **GitHub Pages**:

1. Go to your repo's **Settings** tab.
2. Click **Pages** in the sidebar.
3. Under "Source," select your main branch and `/ (root)` folder.
4. Save — GitHub will give you a live URL (usually `https://yourusername.github.io/PhoenixGives/`).

## License

This project is personal and non-commercial. Feel free to fork it if you want to start something similar where you are.
