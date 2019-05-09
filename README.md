<img align="left" width="96px" height="96px" src="https://hexalang.github.io/favicon/favicon-96x96.png" />

# Hexa

`Her name is [geksa]`

[![Join the Gitter chat](https://badges.gitter.im/hexalang/hexalang.svg)](https://gitter.im/hexalang?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Telegram chatroom](https://img.shields.io/badge/chat-on%20telegram-blue.svg)](https://t.me/hexalang)
[![GitHub Feed](https://img.shields.io/badge/github-feed-green.svg)](https://t.me/hexalang_github)
[![Twitter](https://img.shields.io/badge/twitter-@hexalang-blue.svg)](https://twitter.com/hexalang)
[![Blog](https://img.shields.io/badge/read-blog-CC317C.svg)](https://hexalang.github.io/blog/)
[![Book](https://img.shields.io/badge/learn-book-5F5FFB.svg)](https://hexalang.github.io/book/)
[![Build status](https://ci.appveyor.com/api/projects/status/gi6cm17w4r0l3ahj/branch/master?svg=true)](https://ci.appveyor.com/project/PeyTy/hexa/branch/master)
[![Website](https://img.shields.io/badge/home-hexalang.github.io-3fa5bf.svg)](https://hexalang.github.io)

Hexa is a programming language in an early stage of development. Inspired by [Haxe](https://haxe.org).

![Screenshot](preview.png?raw=true)

[![AUR GIT](https://img.shields.io/badge/archlinux--aur-hexa--git-0088CC.svg)](https://aur.archlinux.org/packages/hexa-git)
[![DOCs and TODOs](https://img.shields.io/badge/compiler-docs%20and%20TODOs-yellow.svg)](https://hexalang.github.io/hexa/)
[![Donate](https://img.shields.io/badge/donate-crypto%20and%20$-gold.svg)](https://hexalang.github.io/donate/)

## Download

#### Stable

`Coming Soon`

#### Latest

- [Build from source](https://github.com/hexalang/hexa#build)
- [Install with Arch Linux AUR](https://aur.archlinux.org/packages/hexa-git)

### Tools & IDE

- [Sublime Text 3](https://packagecontrol.io/packages/Hexa) — [hexalang/hexa-sublime-bundle](https://github.com/hexalang/hexa-sublime-bundle)
- [Visual Studio Code / VSCode](https://marketplace.visualstudio.com/items?itemName=PeyTy.vshexa) — [hexalang/hexa-vscode-bundle](https://github.com/hexalang/hexa-vscode-bundle)
- [Atom](https://github.com/hexalang/hexa-atom-bundle#install) — [hexalang/hexa-atom-bundle](https://github.com/hexalang/hexa-atom-bundle)

## Enjoy!

While compiler is in dev, here's some cool music to listen :headphones:

* [Home Cooked](https://www.youtube.com/watch?v=EyLlOio4bUU)
* [Drip](https://www.youtube.com/watch?v=Bm-q0v0ZYf4)
* [Stay Here Tonight](https://soundcloud.com/just-portals/stay-here-tonight)
* [Standing Over Here](https://soundcloud.com/just-portals/standing-over-herexx)
* [Paranoid](https://soundcloud.com/pistutm/dansette-junior-paranoid-official-video)
* [Gifted](https://soundcloud.com/josecfmarques/n-a-s-a-feat-kanye-west)

## Study

- [Follow 0.1 progress](https://github.com/orgs/hexalang/projects/1?fullscreen=true)
- [Sources of inspiration](https://hexalang.github.io/blog/Syntax-and-Inspiration.html)
- [Getting started guide for beginners](https://hexalang.github.io/book/Hello.html)
- [Some code examples](https://hexalang.github.io/book/Examples.html)
- [Comparison with other languages for experienced developers](https://hexalang.github.io/book/Comparison.html)
- [Why Hexa?](https://hexalang.github.io/book/Profit.html)

## Build

You need to download latest long-term [Node.js LTS](https://nodejs.org/).
The Hexa Compiler is written in Hexa itself. Pre-built compiler (bootstrapper) already included in the repo.

```sh
cd hexa
node bootstrap.js hexa.json
# This results in a `hexa.js` file in the root of the repo
# Call `node hexa.js project.json` to build your projects
```

Optionally to build .exe and add icon:

```sh
npm i -g nexe
nexe-build.bat
```

[Learn more about compiler development](https://hexalang.github.io/hexa/)

## License

See LICENSE files for full license texts and headers of each file
(files in same directory may use different licensing models).

If license is not mentioned in header then LICENSE file in upper directory level to be considered.

**TL;DR**

Compiler and some tools are under Lesser GPL 2.1 (feel free to include as a library in closed source projects),
standard libraries are under MIT.

### Lesser GPL 2.1 with linking exception (to make it compatible with iOS apps)

Linking this library statically or dynamically with other modules is making a combined work based on this library. Thus, the terms and conditions of the GNU General Public License cover the whole combination.

As a special exception, the copyright holders of this library give you permission to link this library with independent modules to produce an executable, regardless of the license terms of these independent modules, and to copy and distribute the resulting executable under terms of your choice, provided that you also meet, for each linked independent module, the terms and conditions of the license of that module. An independent module is a module which is not derived from or based on this library. If you modify this library, you may extend this exception to your version of the library, but you are not obligated to do so. If you do not wish to do so, delete this exception statement from your version.
