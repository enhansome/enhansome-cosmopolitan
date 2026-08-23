# Awesome Cosmopolitan with stars

<img align="left" src="images/cool-honeybadger-smaller.png">

This is a list of Cosmopolitan projects and resources. If you notice anything missing, please open a pull request or simply [make a suggestion](https://github.com/shmup/awesome-cosmopolitan/discussions/new?category=suggestion) ⭐ 314 | 🐛 1 | 📅 2025-12-28.

***

## Table of contents

* [Cosmopolitan](#cosmopolitan-)
  * [Programs](#programs)
  * [Projects](#projects)
  * [Ports](#ports)
  * [Blog Posts](#blog-posts)
* [Redbean](#redbean-)
  * [Projects](#projects-1)
  * [Blog Posts](#blog-posts-1)
* [Fullmoon](#fullmoon-)

***

## Cosmopolitan

> <img align="left" src="images/honeybadger_smaller.png"> *Cosmopolitan Libc makes C a build-once run-anywhere language, like Java, except it doesn't need an interpreter or virtual machine. Instead, it reconfigures stock GCC and Clang to output a POSIX-approved polyglot format that runs natively on Linux + Mac + Windows + FreeBSD + OpenBSD + NetBSD + BIOS with the best possible performance and the tiniest footprint imaginable.*
>
> ![image operating systems](images/operatingsystems.png "operating systems")

* [Cosmopolitan](https://github.com/jart/cosmopolitan) ⭐ 21,254 | 🐛 222 | 🌐 C | 📅 2026-07-20 - Build-once-run-anywhere for C
* [API Docs](https://justine.lol/cosmopolitan/documentation.html) - Thorough documentation for Cosmopolitan Libc
* [HN discussions](https://hn.algolia.com/?query=cosmoplitan+libc) - Algolia list of Cosmopolitan submissions

### Programs

* [actually portable awk](https://justine.lol/awk/) - The One True \[Portable] [Awk](https://github.com/onetrueawk/awk) ⭐ 2,221 | 🐛 15 | 🌐 C | 📅 2026-08-19
* [bob](https://github.com/dinosaure/bob) ⭐ 143 | 🐛 19 | 🌐 OCaml | 📅 2025-05-12 - A peer-to-peer file-transfer tool in OCaml with Cosmopolitan
* [ffl](https://github.com/nuwainfo/ffl) ⭐ 101 | 🐛 4 | 🌐 Python | 📅 2026-08-18 - Turns any file or folder into a secure HTTPS link, allowing two computers to simply and securely transfer files using real peer-to-peer (WebRTC) connections
* [apelife.com](https://justine.lol/apelife/index.html) - tui for conway's game of life with xterm mouse integration
* [blinkenlights](https://justine.lol/blinkenlights/) - Command line debugger that focuses on visualizing how software changes memory
* [braille dump](https://justine.lol/braille/) - drop in replacement for hexdump -C that uses unicode braille characters to display hex code
* [memzoom.com](https://justine.lol/memzoom/index.html) - view/monitor the raw memory of processes/files in your UTF-8 terminal
* [nesemu1.com](https://justine.lol/nesemu1.html) - nes emulator in a terminal
* [printimage.com](https://justine.lol/printimage.html) - png/jpg/gif in terminals
* [printvideo.com](https://justine.lol/printvideo.html) - mpeg in terminals

### Projects

* [microwindows](https://github.com/ghaerr/microwindows) ⭐ 854 | 🐛 24 | 🌐 C | 📅 2026-08-22 - The Nano-X Window System ([demo](https://github.com/jart/cosmopolitan/issues/35#issuecomment-1098659862) ⭐ 21,254 | 🐛 222 | 🌐 C | 📅 2026-07-20)
* [cosmofy](https://github.com/metaist/cosmofy) ⭐ 107 | 🐛 3 | 🌐 Python | 📅 2026-01-13 - Bundle Python projects into a single-file Cosmopolitan Python executable
* [cosmo-include](https://github.com/fabriziobertocci/cosmo-include) ⭐ 33 | 🐛 0 | 🌐 C | 📅 2023-03-24 - Set of very empty header files that can be used when building apps with Cosmopolitan
* [cosmosocks](https://github.com/bannsec/cosmosocks) ⭐ 23 | 🐛 16 | 🌐 C | 📅 2022-09-09 - Socks server written in Cosmopolitan libc

### Tilting at Windmills

Here are our most ambitious community projects, which would require perishing the greatest demons, but if it could be done, would yield some great rewards.

* [cosmogfx](https://github.com/jacereda/cosmogfx) ⭐ 97 | 🐛 1 | 🌐 C | 📅 2022-09-25 - Build-once run-anywhere OpenGL application

### Ports

Note: Some ports are experimental. The most battle-tested code is in the [Cosmopolitan repo](https://github.com/jart/cosmopolitan) ⭐ 21,254 | 🐛 222 | 🌐 C | 📅 2026-07-20. Ports are often a stepping stone for what we put in the monorepo.

* [wasm3](https://github.com/wasm3/wasm3/blob/main/docs/Installation.md#cosmopolitan--actually-portable-executable) ⭐ 7,992 | 🐛 40 | 🌐 C | 📅 2026-08-23 - APE of wasm3
* [mruby](https://github.com/mruby/mruby) ⭐ 5,601 | 🐛 1 | 🌐 C | 📅 2026-08-23 - mruby [supports cosmo](https://github.com/mruby/mruby/pull/6681) ⭐ 5,601 | 🐛 1 | 🌐 C | 📅 2026-08-23 as a build target
* [rust ape example](https://github.com/ahgamut/rust-ape-example) ⭐ 216 | 🐛 3 | 🌐 Rust | 📅 2026-05-07 - Rust APE Example
* [esperanto](https://github.com/dinosaure/esperanto) ⭐ 144 | 🐛 2 | 🌐 C | 📅 2026-02-17 - build-once run-anywhere OCaml programs
* [nim](https://github.com/gnu-enjoyer/ActuallyPortableNim) ⭐ 71 | 🐛 0 | 🌐 Nim | 📅 2023-05-05 - Turns Nim into a build once run anywhere language
* [cpython311](https://github.com/ahgamut/cpython/tree/cosmo_py311) ⭐ 36 | 🐛 3 | 🌐 Python | 📅 2025-11-29 - Port of python 3.11 (see also [3.9](https://github.com/ahgamut/cpython/tree/cosmo_py39) ⭐ 36 | 🐛 3 | 🌐 Python | 📅 2025-11-29, [3.6](https://github.com/ahgamut/cpython/tree/cosmo_py36) ⭐ 36 | 🐛 3 | 🌐 Python | 📅 2025-11-29, and [2.7](https://github.com/ahgamut/cpython/tree/cosmo_py27) ⭐ 36 | 🐛 3 | 🌐 Python | 📅 2025-11-29)
* [ripgrep](https://github.com/ahgamut/ripgrep) ⭐ 22 | 🐛 0 | 🌐 Rust | 📅 2023-10-10 - Port of ripgrep
* [scalajs ape example](https://github.com/lolgab/cosmopolitan-scalajs-example) ⭐ 22 | 🐛 0 | 🌐 Scala | 📅 2022-08-21 - Scala.js APE Example
* [luajit](https://github.com/ahgamut/LuaJIT-cosmo) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2021-09-24 - Port of Lua JIT
* [make](https://github.com/ahgamut/gnu-make-cosmopolitan) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2021-08-06 - Port of GNU Make
* [tcl](https://github.com/ahgamut/tcl/tree/cosmopolitan) ⭐ 8 | 🐛 0 | 📅 2022-06-14 - Port of TCL
* [lua](https://github.com/ahgamut/lua/tree/cosmopolitan) ⭐ 6 | 🐛 0 | 📅 2021-03-09 - Port of Lua
* [janet](https://github.com/ahgamut/janet/tree/cosmopolitan) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2024-04-21 - Port of Janet
* [blis](https://github.com/ahgamut/blis/tree/cosmopolitan) ⭐ 4 | 🐛 0 | 📅 2022-05-07 - Port of BLIS
* [php73](https://github.com/ahgamut/php-src/tree/cosmo_php73) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2022-12-15 - Port of PHP 7.3
* [php81](https://github.com/ahgamut/php-src/tree/cosmo_php81) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2022-12-15 - Port of PHP 8.1
* [sqlite](https://github.com/ahgamut/sqlite/tree/cosmopolitan) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2021-05-04 - Port of SQLite
* [cosmonim](https://github.com/Yardanico/cosmonim) - Simple example to show how cosmopolitan libc can be used with Nim
* [perl](https://computoid.com/APPerl/) - Port of Perl

### Blog Posts

* [Perl is Actually Portable](https://computoid.com/posts/Perl-is-Actually-Portable.html) - Nov 14th, 2022
* [Getting Started with Cosmopolitan Libc](https://jeskin.net/blog/getting-started-with-cosmopolitan-libc/) - Sep 4th, 2022
* [αcτµαlly pδrταblε εxεcµταblε](https://justine.lol/ape.html) - Aug 24th, 2020
* [Using Landlock to Sandbox GNU Make](https://justine.lol/make/) - Aug 7th, 2022
* [Porting OpenBSD pledge() to Linux](https://justine.lol/pledge/) - July 13th, 2022
* [Ape Loader](https://justine.lol/apeloader/) - June 11th, 2022
* [Size Optimization Tricks](https://justine.lol/sizetricks/) - June 10th, 2022
* [Logging C Functions](https://justine.lol/ftrace/) - May 19th, 2022

## Redbean

> <img align="left" src="images/redbean.png"> *redbean is an open source webserver in a zip executable that runs on six operating systems. The basic idea is if you want to build a web app that runs anywhere, then you download the redbean.com file, put your .html and .lua files inside it using the zip command, and then you've got a hermetic app you can deploy and share.*

* [API Docs](https://redbean.dev/)
* [redbean-template](https://github.com/ProducerMatt/redbean-template) ⚠️ Archived - Starting template to create your own redbean project
* [HN discussions](https://hn.algolia.com/?query=redbean) - Algolia list of redbean submissions

### Projects

* [redbean-docker](https://github.com/kissgyorgy/redbean-docker) ⭐ 352 | 🐛 0 | 🌐 just | 📅 2022-12-15 - The smallest possible web server in Docker!
* [turfwar](https://github.com/shamblesides/turfwar) ⭐ 71 | 🐛 0 | 🌐 HTML | 📅 2023-06-14 - IPv4 address turf war!
* [tiddly-bean](https://github.com/amreus/tiddly-bean) ⭐ 32 | 🐛 0 | 🌐 Lua | 📅 2023-01-28 - Experiments with a redbean TiddlyWiki server
* [redbean-jwt](https://github.com/w13b3/redbean-jwt) ⭐ 25 | 🐛 1 | 🌐 Lua | 📅 2024-07-03 - JSON Web Token for redbean
* [action-static-redbean](https://github.com/TimonLukas/action-static-redbean) ⭐ 19 | 🐛 0 | 📅 2023-12-05 - GitHub action that creates a redbean
* [rig](https://github.com/cdrubin/rig) ⭐ 17 | 🐛 2 | 🌐 JavaScript | 📅 2021-05-27 - redbean interactive grapher
* [soakbean](https://github.com/coderofsalvation/soakbean) ⭐ 17 | 🐛 0 | 🌐 Lua | 📅 2026-07-21 write serverlogic using beautiful reactive (nodejs) express-like middleware.
* [redbean-calcpad](https://github.com/shmup/redbean-calcpad) ⭐ 15 | 🐛 0 | 🌐 Makefile | 📅 2022-08-18 - Alternative take on a calculator
* [redbean-cardgames](https://github.com/shmup/redbean-cardgames) ⭐ 9 | 🐛 1 | 🌐 JavaScript | 📅 2022-08-29 - Upcoming collection of cardgames playable in a browser

### Blog Posts

* [Debugging with ZeroBrane Studio](https://news.ycombinator.com/item?id=32484206) - Aug 10th, 2022
* [Redbean on Fly](https://til.simonwillison.net/fly/redbean-on-fly) - July 24th 2022, Recipe for deploying a dockerized redbean to fly
* [Color Us Impressed: Redbean Runs A Web Server On Six Operating Systems](https://hackaday.com/2022/07/22/color-us-impressed-redbean-runs-a-web-server-on-six-operating-systems/) - July 22nd, 2022
* [Unbelievably clever: Redbean 2 – a single-file web server that runs on six OSes](https://www.theregister.com/2022/06/20/redbean_2_a_singlefile_web/) - June 20th, 2022
* [redbean 2.0](https://justine.lol/redbean2/) - June 16th, 2022

## Fullmoon

> <img align="left" src="images/fullmoon.png"> *Fullmoon is a fast and minimalistic web framework based on Redbean -- a portable, single-file distributable web server.*

* [Fullmoon](https://github.com/pkulchenko/fullmoon) ⭐ 755 | 🐛 8 | 🌐 Lua | 📅 2024-08-05 - Fast and minimalistic web framework
* [HN discussions](https://hn.algolia.com/?query=fullmoon+framework) - Algolia list of Fullmoon submissions

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-23._
