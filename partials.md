# Content reuse

Partials are the feature that enables content reuse or single-sourcing.

{% partial file="snippets/hi-im-a-partial.md" /%}

The admonition above comes from the file `snippets/hi-im-a-partial.md`.
It's included in this page with the following syntax:

`{% partial file="snippets/hi-im-a-partial.md" /%}`

By default, partials should be in a directory called `_partials/`.
To make this example work, additional configuration is added to `redocly.yaml` to add the `snippets/` directory.
You can see the configuration in the following example:

```yaml
markdown:
  partialsFolders:
    - snippets
```

**Read more** in the [documentation about content reuse](https://redocly.com/docs/realm/author/how-to/reuse-content).
