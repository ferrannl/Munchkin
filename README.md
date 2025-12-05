# Munchkin – Web Assignment

We have made this website as an assignment from **Avans Hogeschool** in ’s-Hertogenbosch.  
© 2017 Ferran Hendiks & Xia de Visser

> A small multi-page website themed around the **Munchkin** card game, built with HTML and CSS as part of a school project.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Pages](#pages)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Development Notes](#development-notes)
- [Credits](#credits)
- [Legal](#legal)

---

## Overview

This repository contains a **static website** (no backend) created as a web design / front-end assignment.  
The site presents the **Munchkin** card game, its world and rules, and includes supporting pages like an about page, gallery and contact form.

The code is intentionally kept simple and readable for educational purposes.

---

## Features

- 🃏 **Munchkin-themed layout**  
  Styling, imagery and content around the Munchkin card game.

- 📄 **Multiple content pages**
  - Landing / home page
  - About / background information
  - Gallery
  - Video page
  - Contact form
  - Additional sub-pages for more detailed content

- 🎨 **Custom styling with CSS**
  - Central `style.css` file
  - Layout, typography and colors tailored to the theme

- ✨ **Icon support with Font Awesome**
  - Includes **Font Awesome 4.7.0** for decorative and UI icons

- 🧭 **Sitemap**
  - `sitemap.html` gives an overview of the structure and navigation of the site

---

## Pages

The main HTML pages in this project are:

- **`index.html`**  
  Main entry point of the website. Typically contains the hero section and navigation to all other pages.

- **`aboutus.html`**  
  Background information about the project, the game and/or the creators.

- **`gallery.html`**  
  Visual overview of images (game artwork, cards, or related media).

- **`video.html`**  
  Page dedicated to embedded video content (e.g. trailer, explanation, gameplay).

- **`contact.html`**  
  Contact form / contact information page.

- **`page1.html`, `page2.html`, `page3.html`**  
  Extra content pages used in the assignment (for example: rules, expansions, FAQ or story pages).

- **`sitemap.html`**  
  Human-readable sitemap showing the structure and internal links of the site.

There may also be an **images directory** (`images/`) containing logos, illustrations and other assets used across the pages.

---

## Project Structure

A simplified overview of the repository:

```text
Munchkin/
├─ font-awesome-4.7.0/   # Local Font Awesome 4.7.0 files
├─ images/               # Image assets (logos, artwork, screenshots, etc.)
├─ aboutus.html          # About page
├─ contact.html          # Contact page
├─ gallery.html          # Gallery page
├─ index.html            # Landing / home page
├─ page1.html            # Extra content page 1
├─ page2.html            # Extra content page 2
├─ page3.html            # Extra content page 3
├─ sitemap.html          # Sitemap / structure overview
├─ video.html            # Video page
└─ style.css             # Global stylesheet
