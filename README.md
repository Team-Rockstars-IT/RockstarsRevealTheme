# Rockstars theme for Reveal-js presentations

An attempt to create a reusable theme for Reveal presentations.

## Getting started

Install sass

``` bash
npm install -g sass
```

Generate new theme

``` bash
sass theme/source/rockstars.scss theme/rockstars.css
```

Test the template

``` bash
docker run --rm -p 1948:1948 -p 35729:35729 -v $(pwd)/example:/slides -v $(pwd)/theme:/slides/theme webpronl/reveal-md:latest /slides --theme theme/rockstars.css --watch
```

## Ideas

- Add blocks from the website to create links
- Better tables
- Different color-schemes (She's a rockstar pink?)

## Sources

- [Creating Custom Presentation Themes for Reveal.js](https://webdesign.tutsplus.com/courses/creating-custom-presentation-themes-for-revealjs/lessons/welcome-to-the-course)
