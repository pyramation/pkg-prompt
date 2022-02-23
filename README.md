# pkg-prompt

An interactive runner for a npm project `package.json` scripts, forked from [`npm-script-prompt`](https://github.com/bonham000/npm-script-prompt).

## Installation

Install globally:

```
npm i -g pkg-prompt
```

Or, run with npx: `npx pkg-prompt`.

## Usage

Install the package globally and then run `pkgscripts` in an npm project. Choose the npm script you want to run and hit enter!

Example output prompt for for this repo:

```sh
- 5 scripts found for pkg-prompt 📟

? Select an npm script to run (Use arrow keys)
❯ test            - node index.js
  command:one     - echo "Running an example command..."
  command:two     - echo "Running an example command..."
  command:three   - echo "Running an example command..."
  (quit-prompt)   - Quit the prompt and exit
```