# heatmap

A heatmap generator for sixel-capable terminals.

<p align="center">
	<img src="https://user-images.githubusercontent.com/33803413/189885219-c3495527-2330-4cf1-a2b6-94355d633710.png" />
</p>

# Usage

```
heatmap [OPTIONS]
```
`heatmap` reads integers from `stdin` and generates a heatmap using sixel graphics, where each cell's color represents a corresponding input value.

## Options

Option | Meaning
--- | ---
<code>-c <i>n</i></code> | Set the size of each cell to <i>n</i> pixels.
<code>-m <i>n</i></code> | Set the size of gaps between cells to <i>n</i> pixels.
<code>-w <i>n</i></code> | Set the maximum number of columns to <i>n</i>.
<code>-o</code> | Enable the output data compression.
<code>-h</code> | Show help message and exit.

## License

[MIT](https://github.com/wadiim/heatmap/blob/master/LICENSE)
