# Tabbed sections

If you have multiple options for the same section in a project, you can use the [Markdoc tabs tag](https://redocly.com/docs/learn-markdoc/tags/tabs) (try saying it three times fast) to provide that information to users.

{% admonition type="info" name="View source" %}
Read the raw markdown as well as the preview of this page to learn how to mark up text and see how it is displayed.
{% /admonition %}


Here's an example where the exact instructions are different depending on the programming language the user is using:

{% tabs %}
{% tab label="Python" %}

Add the following code to `main.py`:

```python
sentence = "I love coding with Python!"

# Split the sentence into words
words = sentence.split(" ")

# Print each word on a new line
for word in words:
    print(word)

```

Run it with the following command:

```bash
python main.py
```

{% /tab %}
{% tab label="NodeJS" %}

Add the following code to `index.js`:

```js
let sentence = "I love coding with JavaScript!";

// Split the sentence into words
let words = sentence.split(" ");

// Print each word on a new line
words.forEach(function(word) {
    console.log(word);
});
```

Run it with the following command:

```bash
node index.js
```

{% /tab %}
{% /tabs %}


