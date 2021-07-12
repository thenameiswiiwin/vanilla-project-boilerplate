# Welcome !!! 👋

## Intro

Boilerplate for HTML, CSS, JavaScript projects.

## Dev Dependencies

```
- Prettier
- ESLint (AirBnb-base)
- StyleLint (Order, Rational-Order)
- NPM Run All
```

## Getting Started

```bash
# Clone Repo
$ git clone https://github.com/thenameiswiiwin/vanilla-project-boilerplate.git

# Install Dependencies
$ npm install
```

## Scripts

```bash
# Run StyleLint
$ npm run lint:css

# Run ESLint
$ npm run lint:js

# Run ESLint & StyleLint
$ npm run lint

# Prettier
$ npm run format

```

## Architecture

```
.
│
├── public/
│ ├── index.html
│
├── src/
│ ├── assets/
│ │ ├── images/
│
│ ├── scripts
│   ├── app.js
│
│ ├── styles
│ │ ├── 1-resets
│ │ │   ├── \_normalized.css
│ │ ├── 2-global
│ │ │   ├── \_global.css
│ │ │   ├── \_typography.css
│ │ ├── 3-variables
│ │ │   ├── \__custom-variables.css
│ │ ├── 4-utilities
│ │ │   ├── \_utility-classes.css
│ │ ├── 5-components
│ │ ├── 6-queries
│ │ │   ├── \_media-queries.css
│ │ ├── main.css
│
├── .eslintrc.js
├── .gitignore
├── .prettierrc
├── .stylelintrc.json
├── package-lock.json
├── package.json
└── README.md
```
