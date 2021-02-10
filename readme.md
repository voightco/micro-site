![Microsite GitHub Banner](/assets/banner.jpg)

Opinionated micro front-end that can be used to _create a one-pager_.  Great for landing pages or sign-up pages. It uses the static site generator [Eleventy (11ty)][11ty] under the hood and sets _common 11ty defaults_.

## Features ✨

* Inlines and minifies CSS using `clean-css`
* Inlines and minifies JavaScript using `terser`
* Includes a `metadata.json` global data file
* Includes a `base.njk` layout template
* Includes a `assets folder` for static files (images, fonts etc.)

> This is a _*skeleton project_ so it doesn't include any components or basic styling. It's a _*bring your own_ front-end.

## Usage

1. Update the `metadata.json` file with your own site details
2. Edit the `index.njk` file and start coding your website!


## Install

> Requires node.js and npm

Follow these steps to get started:

1. Clone the project

```
$ git clone https://github.com/systemdes/micro-site.git
```

2. Install the dependencies for this projects

```
npm i
```

3. Then do
```
npm run dev
```

to start the live-reloadzz on a local development server.

## Project Structure

```
micro-site/
├── _site/                // output folder of 11ty
├── _data/
│   └── metadata.json     // metadata for the website
├── _includes/
│   ├── style.css         // minified and inlined
│   ├── script.js         // minified and inlined
│   └── base.njk          // base layout
├── assets/               // passtrough copy
├── index.njk/            // landing page
└── .eleventy.js          // 11ty configurations
```
## License

[MIT][license] © [Danny de Vries][author]

[11ty]: https://www.11ty.io/]
[postcss]: https://postcss.org/
[nunjucks]: https://mozilla.github.io/nunjucks/
[autoprefixer]: https://github.com/postcss/autoprefixer
[author]: https://github.com/dandevri
[license]: license

[tailwind]: https://tailwindcss.com/
