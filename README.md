# goit-markup-hw-03

WebStudio landing page markup and styles for Homework #3. This project continues the page from Homework #2 and adds layout work: the box model, a reusable content container, and element positioning with Flexbox — while keeping the same semantic HTML, separated CSS files, and assets from the mockup.

**Project overview**

- **Purpose:** practice the box model and building responsive-ready layouts with Flexbox, based on the provided design.
- **Scope:** a static WebStudio page with header, hero, features, team, portfolio, and footer sections.
- **Assets:** images, favicon, and all text content are taken from the mockup.

**HTML and CSS structure**

- **index.html** links only to `css/main.css`.
- **main.css** contains only imports of the other style files.
- **CSS files** are split by page parts: `common.css`, `header.css`, `hero.css`, `features.css`, `team.css`, `portfolio.css`, and `footer.css`.
- **Import paths** in `main.css` start with `./`.
- **Common styles** and global rules (`box-sizing`, resets, `.container`, `.section`, `.sr-only`, CSS custom properties) are placed in `common.css`.

**Project requirements covered**

- The project has an `images` folder for graphics and a `css` folder for styles.
- File names use only English letters, numbers, and hyphens where needed.
- The code is formatted with Prettier.
- `modern-normalize` is connected in its minified version.
- The layout follows the Code Guide and uses class selectors for styling — no `!important`.
- Interactive elements have hover and focus states that match the design guide.

**Page sections**

- **Header:** logo, navigation links, and contact information in a single container with a bottom border.
- **Hero:** main headline and call-to-action button.
- **Features:** a visually hidden title and a list of four feature items.
- **Team:** team member cards with photos, names, and roles on a light background.
- **Portfolio:** a section with the `portfolio` id and a grid of project cards.
- **Footer:** logo and short business description.

**Notes**

- The dominant font is `Roboto`, with `Raleway` used for the logo. Both are connected with a single Google Fonts link.
- Colors and reusable values (radii, shadows) are stored as CSS custom properties in `common.css`.
- Images in the portfolio and team sections include size attributes in the HTML.
- All content is static and intended for practice with the box model, Flexbox, and CSS organization.
