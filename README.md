fakegit(1) -- Emulating "git clone" with other tools
=================

## SYNOPSIS

`fakegit clone <GitHub Repository URL> [<directory>]`

## DESCRIPTION

The `fakegit` command provides psuedo "git clone" command only for GitHub repository, which downloads files with svn, curl, or wget. This is useful for environments which is difficult to installing git command.

To install fakegit, type as follows:

    $ mkdir -p $HOME/bin
    $ export PATH=$HOME/bin:$PATH
    $ curl -L https://raw.github.com/hnw/fakegit/master/bin/fakegit > $HOME/bin/git
    $ chmod a+x $HOME/bin/git
    $ hash -r

If necessary, enable fakegit in your shell by adding `$HOME/bin`
to your `PATH` and restart your shell.

## LICENSE
#
The MIT License

Copyright (c) 2011 Christoph Hochstrasser

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
