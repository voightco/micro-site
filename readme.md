# micro-site

Opinionated micro front-end that can be used to start a one-page site. It's built with static site generator [Eleventy (11ty)][11ty] and [Tailwind CSS][tailwind].

## Features ✨

* Inlines and minifies CSS using `clean-css`
* Inlines and minifies JavaScript using `terser`
* Includes a `metadata.json` global data file
* Includes a `base.njk` base template
* Includes a `passtrough copy file` for static files

> This is 


## Install

Follow these steps to get started:

1. Clone the project

```
$ git clone https://github.com/dandevri/micro-site.git
```

2. Then do the
```
npm run dev
```

to start the live-reloadzz on a local development server.

## Project Structure

```
micro-site/
├── _site/                // output folder of 11ty
├── _includes/
│   ├── style.css         // minified and inlined
│   ├── script.js         // minified and inlined
│   └── base.njk          // base layout
└── .eleventy.js          // 11ty configurations
```

## Usage

1. Update the `metadata.json` file with your own site details
## License

[MIT][license] © [Danny de Vries][author]

[11ty]: https://www.11ty.io/]
[postcss]: https://postcss.org/
[nunjucks]: https://mozilla.github.io/nunjucks/
[autoprefixer]: https://github.com/postcss/autoprefixer
[author]: https://github.com/dandevri
[license]: license

[tailwind]: https://tailwindcss.com/
