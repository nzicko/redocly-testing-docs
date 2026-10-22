# Code samples

Markdown code samples work on this platform as they do elsewhere.
There is also a Markdoc tag with more features.

{% admonition type="info" name="View source" %}
Read the raw markdown as well as the preview of this page to learn how to mark up text and see how it is displayed.
{% /admonition %}

You may already be familiar with using ``` to include code in documentation:

```javascript
let fruits = ["apple", "banana", "cherry"];
fruits.forEach(function(fruit) {
    console.log("I like " + fruit);
});
```

## Use the code snippet tag

You can also use our [code snippet Markdoc tag](https://redocly.com/docs/learn-markdoc/tags/code-snippet) for additional features in your documentation project:

- add a title to the block, such as to display the filename where the code belongs
- use code from external files, including all or part of the file
- add a comment prefix before the code
- wrap long lines

Here's the same example again using the `code-snippet` tag and the content from `snippets/fruits.js`:

{% code-snippet 
  file="./snippets/fruits.js" 
  language="javascript" 
  title="fruits.js" 
  prefix="// Iterate over an array\n"
/%}
