# NOTE

This is not original package @types/express-session
I modified it to make Session class include 2 more properties as I'm using it while having fun with Discord's OAuth2
the 2 properties are:

* user
* guilds

Why did I do this?
so I do not have to type `//@ts-ignore` before every line where I use `req.session.user`
YES
I am lazy, feel free to be toxic about it

## Installation

`npm i @hakunek/express-session-discord`

## Summary

This package contains type definitions for [express-session](https://github.com/expressjs/session).

## Details

Files were exported from [@types/express-session](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/express-session).

### Additional Details

* Last updated: Mon, 26 Feb 2024 20:07:44 GMT
* Dependencies: [@types/express](https://npmjs.com/package/@types/express), [discord.js](https://npmjs.com/package/discord.js)

## Credits

These definitions were written by [Hiroki Horiuchi](https://github.com/horiuchi), [Jacob Bogers](https://github.com/jacobbogers), [Naoto Yokoyama](https://github.com/builtinnya), [Ryan Cannon](https://github.com/ry7n), [Tom Spencer](https://github.com/fiznool), [Piotr Błażejewicz](https://github.com/peterblazejewicz), and [Ravi van Rooijen](https://github.com/HoldYourWaffle).

modified by: [Mark Putowski](https://github.com/Hakunek)
