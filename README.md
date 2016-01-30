# unix-pty

> Opens Pseudo Terminal Pairs on Unix-like systems. 

This is a fork of [pty.js](https://github.com/chjj/pty.js) that only supports Unix-like systems.
`pty.js` supports Windows and Unix-like systems, but Windows has no native concept of Pseudo
Terminals so `pty.js` uses [winpty](https://github.com/peters/winpty) to emulate them. The problem
is `winpty` adds additional complexity when building `pty.js` on Windows, and you really don't
want to waste time dealing with the build errors when you have no intention of actually using the
emulated Pseudo Terminals on Windows.

## License
MIT
