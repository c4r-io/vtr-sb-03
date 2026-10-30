# Source files

`index.html` at the repo root is the built page. It is produced by replacing the
`<!--SPRITE-->` marker in `run-the-survey.template.html` with the contents of
`sprite.html` (the inline SVG symbols for the raven faces, from the
curriculum_dashboard `graphics/svg/rr-face-*.svg` files and the monolith's
`raven-point-left.svg`), then wrapping the result in a standard HTML document.
