# react-scripts

> ## This project is forked for [timeflies](https://github.com/Chnapy/timeflies)
>
> Diffs from the source repo:
>
> - Webpack config: do not inject JSON files in the bundle, they are loaded by the file-loader in `static/media/`. By importing them we get a path, like for images.
> - Typescript config: `resolveJSONModule` set to `false`, to get `string` as JSON import type. Also `tsconfig.json` is not written anymore on start, even if the config do not respect wanted values. Still have console logs.

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.
