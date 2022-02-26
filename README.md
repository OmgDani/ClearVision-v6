[release-badge]: https://img.shields.io/github/release-pre/OmgDani/ClearVision-v6.svg?style=flat-square
[release-link]: https://github.com/OmgDani/ClearVision-v6/releases
[license-badge]: https://img.shields.io/github/license/OmgDani/ClearVision-v6.svg?style=flat-square
[license-link]: https://github.com/OmgDani/ClearVision-v6/blob/master/LICENSE
[issues-badge]: https://img.shields.io/github/issues/OmgDani/ClearVision-v6.svg?style=flat-square
[issues-link]: https://github.com/OmgDani/ClearVision-v6/issues
[prs-badge]: https://img.shields.io/github/issues-pr/OmgDani/ClearVision-v6.svg?style=flat-square
[prs-link]: https://github.com/OmgDani/ClearVision-v6/pulls

<div align="center">

# ClearVision v6

[![Releases][release-badge]][release-link]
[![License][license-badge]][license-link]
[![Issues][issues-badge]][issues-link]
[![Pull Requests][prs-badge]][prs-link]

![v6 Sapphire](https://github.com/Zerthox/ClearVision/raw/master/screenshots/v6.png)

</div>

## About
This fork of ClearVision aims to preserve and bring back some older features and styles of ClearVision and Discord.

Any issues with this fork should be reported [here][issues-link] and not ClearVision's repository or Discord.

## Installing
Download the theme file and move it into your [BetterDiscord](https://betterdiscord.net) themes folder:

>[ClearVision_v6.theme.css](https://omgdani.github.io/ClearVision-v6/dist/ClearVision_v6.theme.css)

## Building from source
In order build the theme from source you'll need [Sass](https://sass-lang.com) & [PostCSS Autoprefixer](https://github.com/postcss/autoprefixer).  
With [npm](https://npmjs.org/get-npm) installed you can simply run `npm install` to install all missing dependencies and compile the theme into the `/public` folder via `npm run build`.

**Dependencies:**
- [node-sass](https://github.com/sass/node-sass)
- [PostCSS Autoprefixer](https://github.com/postcss/autoprefixer)
- [PostCSS CLI](https://github.com/postcss/postcss-cli)
- *[DiscordSelectors](https://github.com/zerthox/discordselectors) (included in the `/lib` folder)*
- *[rimraf](https://github.com/isaacs/rimraf) (for cleanup)*

## Contributing
In order to contribute you need to be able to compile [Sass](https://sass-lang.com).

If you use [Dart Sass](https://github.com/sass/dart-sass) via CLI, you can run:
```
sass main.scss:public/main.css --watch
```

This will compile the theme into the `/public` folder and watch changes.