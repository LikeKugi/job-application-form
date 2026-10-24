# Job Application Form

A "Build a Job Application Form" lab (freeCodeCamp) styled as a paper application from the
Maple Row Block Association, laid on a dark desk. Plain HTML + CSS, no JavaScript.

## View it

Open `index.html` in a browser (or serve the folder):

```sh
npx serve .
```

## What it demonstrates

- Semantic form controls: `input` (text / email / radio), `select`, `textarea`, `button[type=submit]`
- Every control associated with a `<label for>`
- `:focus` (border color + `outline: none`), `:hover`, `:invalid` (red), `:valid` (green)
- `:checked` on custom radio dots: border, background, box-shadow, plus the paired label's text color
- `:first-of-type` giving the name field a pill shape

The pseudo-classes are styled like grading ink: red = needs fixing, green = approved,
terracotta = the Association's stamp on focus and checked choices.
