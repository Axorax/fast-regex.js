# 🙌 Fast regex contributing guideline

## → Add a new regex

To add a new regex to the library at first, fork the repository.

Then, navigate to the `regex.js` file.

All changes must happen in the `regex.js` file.

After going to the file, you can add a name for your regex along with the regex code. Like this:

```js
'myCoolRegex': '[a-z]',
```

You can add a flag to the regex too like this:

```js
'myCoolRegexWithFlag': '[a-z]', 'g',
```