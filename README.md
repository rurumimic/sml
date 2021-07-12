# Standard ML

- [Standard ML of New Jersey](https://www.smlnj.org/)
- [Versions](https://www.smlnj.org/dist/working/index.html)
- [Literature](https://www.smlnj.org/doc/literature.html)
  - [ML for the Working Programmer](https://www.cl.cam.ac.uk/~lp15/MLbook/): [contents](https://www.cl.cam.ac.uk/~lp15/MLbook/pub-details.html)
  - [Programming in Standard ML](http://www.cs.cmu.edu/~rwh/isml/book.pdf)
- Wikipedia: [Standard ML](https://en.wikipedia.org/wiki/Standard_ML)

## Example

```bash
sml
Standard ML of New Jersey (64-bit) v110.99.1 [built: Mon Apr 12 18:45:14 2021]
```

```sml
- use "./sum.sml";
[opening ./sum.sml]
val sum = fn : int * int -> int
val it = () : unit
```

```bash
- sum (3, 5);
val it = 8 : int
```

```sml
- ^D (* Control + D *)
```

## Install on mac

brew: [smlnj](https://formulae.brew.sh/cask/smlnj)

```bash
brew install --cask smlnj
```

To use smlnj, you may need to add the /usr/local/smlnj/bin directory to your `PATH` environment variable, e.g. (for Bash shell): `export PATH=/usr/local/smlnj/bin:"$PATH"`

```bash
echo 'export PATH=/usr/local/smlnj/bin:"$PATH"' >> ~/.bashrc
# ~/.bash_profile, ~/.zshrc, ~/.zshenv
```
