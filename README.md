# Boilerplate for Next JS 13+, Tailwind CSS 3.2, TypeScript and WordPress

π Boilerplate and Starter for Next.js, Tailwind CSS, TypeScript and WordPress 
β‘οΈ Made with developer experience first: Next.js, TypeScript, ESLint, Prettier, Husky, Lint-Staged, Jest, Testing Library, Commitlint, VSCode, Netlify, PostCSS, Tailwind CSS.

### Attribution

Based on [this Nextjs-Boilerplate](https://github.com/ixartz/Next-js-Boilerplate) and [this Nextjs-with-Wordpress and Apollo example](https://github.com/vercel/next.js/tree/canary/examples/cms-wordpress) and [this Next-wordpress-starter](https://github.com/colbyfayock/next-wordpress-starter)

Some elements from [Tailwind UI](https://tailwindui.com/)

### Features

Developer experience first:

- β‘ [Next.js](https://nextjs.org) for Static Site Generator
- π₯ Type checking [TypeScript](https://www.typescriptlang.org)
- π Integrate with [Tailwind CSS](https://tailwindcss.com)
- β Strict Mode for TypeScript and React 18
- π Linter with [ESLint](https://eslint.org) (default NextJS, NextJS Core Web Vitals, Tailwind CSS and Airbnb configuration)
- π Code Formatter with [Prettier](https://prettier.io)
- π¦ Husky for Git Hooks
- π« Lint-staged for running linters on Git staged files
- π Lint git commit with Commitlint
- π Write standard compliant commit messages with Commitizen
- π¦Ί Unit Testing with Jest and React Testing Library
- π§ͺ E2E Testing with Cypress
- π· Run tests on pull request with GitHub Actions
- π Automatic changelog generation with Semantic Release
- π Visual testing with Percy (Optional)
- π‘ Absolute Imports using `@` prefix
- π VSCode configuration: Debug, Settings, Tasks and extension for PostCSS, ESLint, Prettier, TypeScript, Jest
- π€ SEO metadata, JSON-LD and Open Graph tags with Next SEO
- πΊοΈ Sitemap.xml and robots.txt with next-sitemap
- βοΈ [Bundler Analyzer](https://www.npmjs.com/package/@next/bundle-analyzer)
- π― Maximize lighthouse score
- βοΈ Blogposts with headless Wordpress
- β Live editing of Tailwind CSS classes with [Impulse](https://impulse.dev)
- π Analytics with selfhosted [Plausible](https://plausible.io) or [Umami](https://umami.is)

Built-in feature from Next.js:

- β Minify HTML & CSS
- π¨ Live reload
- β Cache busting

### Philosophy

- Minimal code
- SEO-friendly
- π Production-ready

### Requirements

- Node.js 14+ and npm
- WordPress CMS with GraphQL endpoint

### Commit Message Format

The project enforces [Conventional Commits](https://www.conventionalcommits.org/) specification. This means that all your commit messages must be formatted according to the specification. To help you write commit messages, the project uses [Commitizen](https://github.com/commitizen/cz-cli), an interactive CLI that guides you through the commit process. To use it, run the following command:

```shell
npm run commit
```

One of the benefits of using Conventional Commits is that it allows us to automatically generate a `CHANGELOG` file. It also allows us to automatically determine the next version number based on the types of commits that are included in a release.

### Deploy to production

You can see the results locally in production mode with:

```shell
$ npm run build
$ npm run start
```

The generated HTML and CSS files are minified (built-in feature from Next js). It will also removed unused CSS from [Tailwind CSS](https://tailwindcss.com).

You can create an optimized production build with:

```shell
npm run build-prod
```

Now, your blog is ready to be deployed. All generated files are located at `out` folder, which you can deploy with any hosting service.

### Testing

All tests are colocated with the source code inside the same directory. So, it makes it easier to find them. Unfortunately, it is not possible with the `pages` folder which is used by Next.js for routing. So, what is why we have a `pages.test` folder to write tests from files located in `pages` folder.

### VSCode information (optional)

If you are VSCode users, you can have a better integration with VSCode by installing the suggested extension in `.vscode/extension.json`. The starter code comes up with Settings for a seamless integration with VSCode. The Debug configuration is also provided for frontend and backend debugging experience.

With the plugins installed on your VSCode, ESLint and Prettier can automatically fix the code and show you the errors. Same goes for testing, you can install VSCode Jest extension to automatically run your tests and it also show the code coverage in context.

Pro tips: if you need a project wide type checking with TypeScript, you can run a build with <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>B</kbd> on Mac.

### Contributions

Everyone is welcome to contribute to this project. Feel free to open an issue if you have question or found a bug.  Totally open to any suggestions and improvements.

---
