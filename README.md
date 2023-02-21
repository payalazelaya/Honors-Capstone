# IDMX 11ty Sass Starter

The set of development scripts in this starter is configured to watch and compile a simple Sass structure using 11ty.

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifiying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

## Installation

**`npm install`**

>Run this command once to install the needed node modules.

## Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and served at the url localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS.

Use this as the "Publish command" if needed by hosting services such as Netlify.

## Resources

<small>The starter was inspired by [11ty Sass Skeleton](https://github.com/5t3ph/11ty-sass-skeleton) by [@5t3ph](https://twitter.com/5t3ph)</small>

[Teachers use of new technologies in Latin America](https://www.oecd-ilibrary.org/sites/e1c0a802-en/index.html?itemId=/content/component/e1c0a802-en)

[The digital transformation for all](https://www.oecd-ilibrary.org/sites/e7a00fd6-en/index.html?itemId=/content/component/e7a00fd6-en#sect-70)

[Bootcamp: How Latin America is teaching girls to code](https://www.weforum.org/agenda/2017/03/these-latin-american-bootcamps-are-teaching-girls-to-code)

[Education Technology in Latin America and the Caribbean](https://www.holoniq.com/notes/education-technology-in-latin-america-and-the-caribbean)

[Interactive Learning: Making it Work in Latin America](https://blogs.iadb.org/ideas-matter/en/interactive-learning-making-it-work-in-latin-america-and-the-caribbean/)