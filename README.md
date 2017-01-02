# SASS Stylesheets for GitBook

**Note:
  This plugin is just a temporary fix for the original plugin:
  https://www.npmjs.com/package/gitbook-plugin-styles-sass !
  The only thing I did was to raise the node-sass version,
  when the original version works again I will most likely delete this package again!** 

This plugin makes it easy to use SASS custom stylesheets instead of CSS for your book.

Add it to your `book.json`, with some custom stylesheets:

```js
{
    "plugins": ["styles-sass"],
    "styles": {
        "pdf": "./styles/pdf.sass"
    }
}
```

