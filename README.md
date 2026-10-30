# Homebrew tap for NOQTIS

```sh
brew install rootcoder007/noqtis/noqtis
```

or

```sh
brew tap rootcoder007/noqtis
brew install noqtis
```

NOQTIS seals the exact files behind a result with a post-quantum
signature (ML-DSA, SLH-DSA), so anyone can check later, offline, that
nothing changed. Documentation: <https://rootcoder007.github.io/noqtis/>.

The formula is written by the NOQTIS release workflow when a release is
published, from the signed release tarball and its SHA-256; its source
is `packaging/brew/noqtis.rb` in
[rootcoder007/noqtis](https://github.com/rootcoder007/noqtis). The same
formula is also in the `rootcoder007/morie` tap.
