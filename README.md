# Cigale

Quick and effective UX simple black and white CSS design.

## Install

```
npm install cigale
```

## Usage

### CSS

```
@import "../node_modules/cigale/css/cigale.css";
```

### SCSS

```
@import "../node_modules/cigale/scss/cigale.scss";
```

## Syntax

Cigale is designed to have almost nothing to add. See the `test` directory to have examples.

### Layout

```html
<body class="layout">
  <section class="header">
    <header>
      <a href="index.html">
        <img src="assets/cigale.svg" alt="Logo" />
        <span>Cigale</span>
      </a>
      <button>Help</button>
    </header>
  </section>
  <section class="main">
    <main>
      <div class="tagline">
        <p>Cigale song is "csscsscss"</p>
        <a href="form.html">
          <button class="primary" autofocus>Get started</button>
        </a>
      </div>
    </main>
  </section>
  <section class="footer">
    <footer>
      <a href="legal.html">Legal stuff</a>
    </footer>
  </section>
</body>
```

### Button

Button have been decorated in flat design. They can have primary class.

### Forms

Form should be a list of labels ending with a submit button.

Each `label` is composed of a `div` for the label text and `input`, `textarea` or `select` for the field, and optionaly a `div.error` box for error messaging.

### Tables

Just add a parent wrapper with class `table`.
Table is composed of a navigation with buttons and the table itself.

```html
<div class="table">
  <nav>
    <button>...</button>
    ...
  </nav>
  <table>
    ...
  </table>
</div>
```

## Why Cigale?

Cigale, in english Cicada. It is an kind of insect that lives in the south of France, and who does 'ksssksssksss'... or 'csscsscss'... yes this play on word sucks... :smiley:

## Motivations

HTML default settings sucks:

- buttons design too old. Not minimalist. Not flat
- radio button and check button too small
- input type=text should be homogen with buttons.
- No concept of primary button.
- No choice of color palette.
- Form should often be the same things.
- Mobile first : vertical layout.
- Responsive menu.
- Header = site-id + primary menu + utilities

## Prerequisites

Use normalize.css

## SCSS

The code is written is SCSS. So you can directly use the SCSS or the CSS compiled version.

## Author

Jean-Louis GUENEGO <jlguenego@gmail.com>
