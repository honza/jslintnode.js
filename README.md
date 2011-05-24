JSLintNode.js
=============

Run your javascript files through the [JSLint][jslint] tool from the comfort of your
command prompt.

The file contains the original, unmodified `fulljslint.js` written by
Douglas Crockford. The revision used is the following SHA1:

8d035d3c1f9499e13c1246cdbc67910860641281 (Mar 31 2011)

The repository is hosted on [Github][jslintrepo].

The node.js specific code is found at the bottom of the file. This utility
takes a single argument - the file you wish to scan.

    $ jslintnode.js yourfile.js

This utility simply reads the file (if found) and prints out the errors it
encounters. It prints nothing if your file is OK.

You can install this utility by symlinking this file to `/usr/bin` or similar.

### Dependencies

The only dependency is [Node.js][node].

JSLintNode.js is licensed under the terms of the BSD license.

[jslint]: http://www.jslint.com
[jslintrepo]: http://github.com/douglascrockford/JSLint
[node]: http://nodejs.org
