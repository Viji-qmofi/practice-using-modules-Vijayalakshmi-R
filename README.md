# Modules & Package Management

## Practice 4: Using Modules

To make use of someone else's module effectively, you should familiarize yourself with the functionality it provides and the creator's intentions before you can decide how it will fit your needs.

### Documentation

Visit each of the following:

- [npm yargs documentation](https://www.npmjs.com/package/yargs)
- [GitHub yargs documentation](https://github.com/yargs/yargs)
- [npm chalk documentation](https://www.npmjs.com/package/chalk)
- [Common JS modules vs ES modules](https://javascript.plainenglish.io/commonjs-vs-es-modules-why-both-matter-in-2025-b7edc1b29899)

/**
 *  Explanation:
 * - package.json: Keeps track of project metadata and dependencies.
 *   When you install modules (like yargs, chalk), they're listed under "dependencies".
 * - node_modules: Stores all the installed packages. It can become very large,
 *   so we never commit it to version control (like GitHub).
 * - .gitignore: Ensures node_modules (and other unnecessary files) are not pushed to git.
 * - npm install: Reads package.json and reinstalls dependencies into node_modules.
 *   This is critical in team projects—other developers just run `npm install`
 *   to get the same setup without having to manually install everything.
 */
