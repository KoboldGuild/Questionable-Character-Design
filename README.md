# Titt's Questionable Character Design Brief

A free fantasy character design prompt generator for artists.

## Editing the result lists

You **do not need to edit `index.html`** to add new generator results.

Open **`database.js`** in GitHub and click the pencil icon.

Every category has its own clearly labelled section, for example:

```js
fashion: [
  "Practical adventurer",
  "Romantic Gothic",
  "Corporate goth",
  "Your new fashion result"
],
```

To add a result:

1. Find the category.
2. Add a new line inside the square brackets.
3. Put the result inside quotation marks.
4. Make sure the previous line ends in a comma.
5. Commit the change.

`index.html` contains the generator layout and behaviour.
`database.js` contains the editable prompt lists.

## GitHub Pages

Keep `index.html` and `database.js` in the same repository folder.

For GitHub Pages:
**Settings → Pages → Deploy from a branch → main → /(root)**
