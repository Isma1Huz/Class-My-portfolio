# Personal Profile

A responsive, single-page personal profile website for **Ismael Hussein**, a software engineer and graphic designer based in Nairobi, Kenya. Built with plain HTML and CSS, with no frameworks, JavaScript or build tools.

## Overview

The page introduces who I am, where I studied, what I can do and what I enjoy outside of work, and gives visitors a way to contact me.

## Sections

- **Header**: name, role and location
- **About Me**: a short introduction
- **Education**: Zetech University, Moringa School, Nairobits School and Ruaraka High School
- **Skills**: PHP, Laravel, React, Next.js, Python, WordPress, cloud deployment, design and more
- **Hobbies**: gaming, learning languages, digital art, side projects and more
- **Contact**: email link

## Features

- Modern gradient header and card-based layout
- Education shown as a timeline
- Skills and hobbies displayed as hoverable chips
- Fully responsive, from phones to desktops
- Everything in a single `index.html` file, so it is easy to read and edit

## Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure |
| CSS3 | Styling, gradients, responsive layout |
| Google Fonts (Poppins) | Typography |

## Project Structure

```
personal-profile/
├── index.html
└── README.md
```

## Run Locally

No installation needed.

```bash
git clone https://github.com/YOUR-USERNAME/personal-profile.git
cd personal-profile
```

Then open `index.html` in any browser. Alternatively, serve it locally:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Customise

Open `index.html` in any text editor and change the content directly in the HTML. For example, to add a skill, add a new line to the skills list:

```html
<ul class="chips">
  <li>PHP</li>
  <li>Laravel</li>
  <li>Your New Skill</li>
</ul>
```

Colours and fonts are defined at the top of the `<style>` block, so you can change the whole theme from there.

## Deploy (optional)

Host it free with GitHub Pages: go to **Settings → Pages**, choose the `main` branch and the root folder, then save.

## Contact

**Ismael Hussein**
Email: [ismaelhuz45@gmail.com](mailto:ismaelhuz45@gmail.com)
Location: Nairobi, Kenya

---

&copy; 2026 Ismael Hussein. All rights reserved.