---
sidebar_position: 1
---

# Introduction

<h1 align="center">
  <img src="img/md/icon.png" width="128" />
  <br/>
  Lanaya
  <br/>
</h1>

<h3 align="center">
A clipboard management with easy to use.
</h3>

Lanaya comes from Templar Assassin in Dota2, which is a clipboard management software with convenient and simple interaction.

## Features

- Search by keywords.
- All shortcut to manage.
- Setting history record range.
- Multi-language.
- Auto updater.
- Input `f:xxx` to search favorite records.

## Todos

- [x] add `taildwind` to manage css.
- [x] add copy image history.
- [ ] add theme.
- [x] add favorite.
- [ ] add `Windows`,`Linux` support.
- [x] use `Rust` to implement clipboard listener.
- [x] use `Rust` to implement `Sqlite` database operation.

## Download

Download from [release](https://github.com/ChurchTao/Lanaya/releases).

## Development

You should install Rust and Nodejs, see [here](https://tauri.app/v1/guides/getting-started/prerequisites) for more details. Then install Nodejs packages.

```shell
npm install
```

Then run

```shell
cargo install tauri-cli # output with [no such subcommand: `tauri`] please install first

cargo tauri dev
```

Or you can build it

```shell
cargo tauri build
```

## Screenshots

<div align="center">
  <img src="img/md/demo1.png" alt="demo1" width="80%" />
  <img src="img/md/demo2.png" alt="demo2" width="80%" />
  <img src="img/md/demo3.png" alt="demo3" width="80%" />
  <img src="img/md/demo4.png" alt="demo4" width="80%" />
  <img src="img/md/demo5.png" alt="demo4" width="80%" />
</div>

## Contributions

Issue and PR welcome!

## Acknowledgement

Lanaya was based on or inspired by these projects and so on:

- [tauri-apps/tauri](https://github.com/tauri-apps/tauri): Build smaller, faster, and more secure desktop applications with a web frontend.
- [vitejs/vite](https://github.com/vitejs/vite): Next generation frontend tooling. It's fast!
- [vue3](https://github.com/vuejs/core): An approachable, performant and versatile framework for building web user interfaces.
- [tailwindlabs](https://github.com/tailwindlabs) Creators of Tailwind CSS and Headless UI, and authors of Refactoring UI.

## License

Apache-2.0 license. See [License here](https://github.com/ChurchTao/Lanaya/blob/master/LICENSE) for details.
