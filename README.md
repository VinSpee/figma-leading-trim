# figma-leading-trim

Figma plugin for trimming text elements, removing space above capital letters and below the baseline.

If you want to achieve the same behaviour in a browser, check out [Capsize.](https://seek-oss.github.io/capsize)

## Development guide

### Pre-requisites

- [Node.js](https://nodejs.org)
- [pnpm](https://pnpm.io/)
- [Figma desktop app](https://figma.com/downloads/)

### Build the plugin

To build the plugin:

```bash
$ pnpm build
```

This will generate a [`manifest.json`](https://figma.com/plugin-docs/manifest/) file and a `build/` directory containing the JavaScript bundle(s) for the plugin.

To watch for code changes and rebuild the plugin automatically:

```bash
$ pnpm watch
```

### Install the plugin

1. In the Figma desktop app, open a Figma document.
2. Open the Quick Actions search bar (`Cmd + /`) and run `Import plugin from manifest…`
3. Select the `manifest.json` file that was generated by the build/watch script.

### Debugging

To open the developer console, search for and run `Open Console` via the Quick Actions search bar. Just like in a browser, you can use `console.log` statements to inspect values in your code.

## See also

- [Create Figma Plugin docs](https://yuanqing.github.io/create-figma-plugin/)
- [`yuanqing/figma-plugins`](https://github.com/yuanqing/figma-plugins#readme)

Official docs and code samples from Figma:

- [Plugin API docs](https://figma.com/plugin-docs/)
- [`figma/plugin-samples`](https://github.com/figma/plugin-samples#readme)

## Credit

- [Yuan Qing Lim](https://twitter.com/yuanqinglim) for [create-figma-plugin](https://github.com/yuanqing/create-figma-plugin)
- [Michael Taranto](https://twitter.com/michaeltaranto) for [Capsize](https://seek-oss.github.io/capsize)

## License

MIT.
