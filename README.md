# silicon-elements

A set of web-components for compiler, reverse engineering, binary analysis, and other low-level technologies.

Current elements:

* `<silicon-disassembler>` - a disassembler for x86 and ARM
* `<silicon-hex-table>` - a hex table/hex editor
* `<silicon-image>` - a binary image rasterizer/offset tracker
* `<silicon-instructions>` - an assembly instruction syntax highlighter and list
* `<silicon-upload>` - a binary upload drag & drop widget
* `<silicon-symbols>` - a list of symbols

## Roadmap

Any help would be much appreciated!

### Elements in progress

* [silicon-image](https://github.com/m4b/silicon-image) needs a linear, non-rasterized implementation; also needs to have a sane zoom implementation, specifically when the binaries are huge.
* [silicon-instructions](http://github.com/m4b/silicon-instructions) require some more tweaking, specifically with iron-list, etc.
* [silicon-upload](http://github.com/m4b/silicon-upload) needs a json upload version with base64 encoding of the binary

### Documentation and Tests

Need to add more documentation (specifically for CSS variables), more demos, and definitely `wct` tests.

### Elements planned

* `<silicon-functions>` - Or something to this effect. Specifically, wrapping something like `stringview.js` would be nice.

For now, focusing on tweaking the existing suite.  If you have any ideas, don't hestitate to send a PR!
