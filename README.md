# remap

Map each regular-expression match with the result of a command.

This script was written for MacOS,
but should work on any POSIX system with `perl` installed.

It's just a wrapper for a _perl_ one-liner
that I can't remember when I need it.

This script used to named `sde`,
likely a play on "sed",
but I couldn't remember why I named it that,
so I renamed it to `remap`, which makes more sense.

## Usage

```shell
remap <REGEX> [<COMMAND-STATEMENT>]
```

## Installation

This is just a script, just put it on your PATH.
Alternatively, you can copy the perl one-liner it wraps
into a function in one of your startup files.

## License

Shared under the MIT license.

It works on my machine. Use at your own risk.

If you do find any problems, please open an issue
or email me directly—my address is in the source.
