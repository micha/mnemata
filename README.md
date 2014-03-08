# mnemata

A Hoplon project with Foundation for CSS (and its friends Bower and Grunt to compile the SCSS)

## Dependencies

- java 1.7+
- [boot][1]
- [leiningen][2]
- bower, grunt-cli

## Usage

You'll probably want to have two (or more) terminals open in your project's
directory.

1. Start the auto-compiler.

```bash
$ boot watch hoplon
```

2. Compile the scss if you haven't yet:

```bash
$ grunt
```

2. Open the compiled html file.

```bash
$ open resources/public/index.html
```

3. You're already done.

## License

Copyright © 2014, **Matt Gauger**

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.

---


[1]: https://github.com/tailrecursion/boot
[2]: https://github.com/technomancy/leiningen
