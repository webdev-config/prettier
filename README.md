# webdev-configs

Configurations to be shared across repositories.

# prettier

Add `"prettier": "webdev-configs"` to your `package.json`. Be sure to include your own `.prettierignore`.

To write changes to your source, add `"format:all": "prettier --write .",` to your `package.json` `scripts`.

Use `npm run format:all` in your project folder.
