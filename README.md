# Rohaan Ahmad portfolio

A personal portfolio site for Rohaan Ahmad, a software engineering student at NUST SEECS. It has seven pages: home, projects, research, skills, hobbies, a photo gallery, and contact.

Built for CS344 Web Engineering (Lab 2 content, restructured in Lab 3).

## Structure

```
portfolio/
├── index.html      home page (entry point)
├── projects.html
├── research.html
├── skills.html
├── hobbies.html
├── gallery.html
├── contact.html
├── css/
│   └── style.css   the only stylesheet, shared by every page
├── images/         all photographs and screenshots
└── README.md
```

## Technology

HTML and CSS only. There's no JavaScript, no CSS framework, no CDN, and no external library. The gallery's full-screen view uses the CSS `:target` selector.

## Viewing

Open `index.html` in a browser, or publish the folder with GitHub Pages. Pages serves `index.html` at the repository's root URL.
