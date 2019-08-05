# Molly

A blog theme for zola, based on [Tufte CSS](https://edwardtufte.github.io/tufte-css/).

*This project is a work in progress.*:dog:

## TODO
- [x] Initial setup using Tufte.css
    - [x] Define base layout
    - [x] Support side notes and marginal notes
    - [x] Support sections
    - [x] Add post list
    - [x] Add internal links
- [ ] 2nd phase plan
    - [ ] Add CSS Grid layout for responsiveness
    - [ ] Make the theme more customizable
- [ ] 3rd phase plan
    - [ ] Enable discussion

## Credits
[Tufte CSS](https://edwardtufte.github.io/tufte-css/)

Gertjan van den Burg's [blog post](https://gertjanvandenburg.com/blog/how_i_made/)

ayekat's [blog post](http://ayekat.ch/blog/tufte-css) as well as site design

## Repo structure
``` bash
├── content
│   ├── about
│   ├── blog
│   ├── _index.md
├── sass
│   ├── _tufte.css
│   ├── molly.scss
├── static
│   │   ├── et-book
│   │   ├── img
│   ├── molly.css
├── templates
│   ├── shortcodes
│   ├── base.html
│   ├── index.html
│   ├── macros.html
│   ├── page.html
├── config.toml
├── README.md
├── theme.toml
└── .gitignore
```
