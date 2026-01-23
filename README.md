# Onfocusio Libs

Install homebrew versions of libraries supported by Adagio.

```bash
brew uninstall rocksdb
brew unlink snappy # or: brew uninstall --ignore-dependencies snappy
brew unlink gflags # or: brew uninstall --ignore-dependencies gflags
brew install onfocusio/libs/gflags # 2.2.2
brew install onfocusio/libs/snappy # 1.2.2
brew install onfocusio/libs/rocksdb # 10.4.2
```

Disclaimer: this can create problems with other brews that need a most recent version of gflags or snappy