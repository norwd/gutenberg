# Small Project Gutenberg Mirror

![GitHub repo size](https://img.shields.io/github/repo-size/norwd/gutenberg)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/norwd/gutenberg)
![GitHub License](https://img.shields.io/github/license/norwd/gutenberg)

This is a GitHub Actions powered mirror of some niche books and other literature from [Project Gutenberg].

---

Note, that while Project Gutenberg allows (and even encourages) [mirroring], it is recommended to use `rsync` instead of webcrawlers as used in this repo.
If the scope of this mirror ever extends beyond a relatively tiny set of books, that is probably the path forward, but in the meantime `wget` is the way to go.

Also note, the [LICENSE] for this repository only extends to the code here that documents and implements the mirroring, the mirrored files themselves are under their respective copyrights, or lack thereof more acurately.

[LICENSE]: /LICENSE
[Project Gutenberg]: https://www.gutenberg.org
[mirroring]: https://www.gutenberg.org/help/mirroring.html
