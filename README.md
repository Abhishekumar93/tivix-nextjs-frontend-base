![Tivix Logo](https://www.tivix.com/wp-content/themes/tivix/svg/tivix-logo-dark.svg)

## Tivix Frontend Boilerplate

This is a boilerplate for NextJS Frontend.

### Tech Stack:

1. NextJS
2. TypeScript
3. Storybook
4. Tailwind CSS

### Setup

1. Install cookiecutter `pip3 install cookiecutter`
2. Go to the directory you want the project
3. Git clone and configure by running `cookiecutter git@github.com:Tivix/tivix-react-frontend-base.git`
4. After that, cookiecutter will make a few questions and based on that, your package will be builded.
5. If you will select both `use_storybook` and `use_tailwind` `True`, then add `import '../styles/tailwind.css'` in `.storybook/preview.js` file
6. Just run a `npm i` and after a `npm start`
7. Enjoy!
