# highlight-simple

Highlights occurrences of the selected text.

![view](https://github.com/asiloisad/pulsar-highlight-simple/blob/master/assets/view.png?raw=true)

## Installation

To install `highlight-simple` search for [highlight-simple](https://web.pulsar-edit.dev/packages/highlight-simple) in the Install pane of the Pulsar settings or run `ppm install highlight-simple`. Alternatively, you can run `ppm install asiloisad/pulsar-highlight-simple` to install a package directly from the GitHub repository.

## Styling

Override the highlight style in your stylesheet:

```less
atom-text-editor .highlights {
  .highlight-simple .region {
    border: 1px solid @syntax-result-marker-color;
    background-color: @syntax-result-marker-color-selected;
    border-radius: 3px;
  }
}
```

# Contributing

Got ideas to make this package better, found a bug, or want to help add new features? Just drop your thoughts on GitHub — any feedback’s welcome!

# Credits

Fork of [highlight-selected](https://github.com/Pulsar-Edit-Highlights/selected).
