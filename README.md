# chester's website configs

This project contains the configuration for my personal websites (which I ansible-ized in an effort to explore Ansible further).

I published it because:

- Snippets may be useful to someone else (despite being very specific to my stuff);
- Keeps me honest (makes me write scripts that don't suck much, forces me not to have plaintext secrets, exposes security flaws, etc.);
- Public github is free! ;-)

Feel free to use it (I'm licensing as MIT to ensure that) and to open issues or [contact me][6] if you find something awry.

## What does it set up?

### chester.me (blog) [WIP]

My [personal blog][4], currently based on a [forked Octopress 2.x][5].

### cruzalinhas.com [TODO]

An app that allows quickly finding public transportation routes in São Paulo. See [source code][1] or [website][3] for details

### miniTruco server [TODO]

This is a simple Java app that listens on the 6912 port, handling communication between [miniTruco][2] clients and spawning bot players to fill incomplete tables (a miniTruco table requires 4 players).

[1]: https://github.com/chesterbr/cruzalinhas
[2]: https://github.com/chesterbr/minitruco-j2me
[3]: http://cruzalinhas.com
[4]: http://chester.me
[5]: https://github.com/chesterbr/octopress
[6]: mailto:cd@pobox.com?subject=chester-website-configs

## License

chester-website-configs - Copyright (c) 2015 Carlos Duarte do Nascimento (Chester)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.