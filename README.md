# `.gitignore` Template Generator

Combines `.gitignore` files from the `github/gitignore` repository.

I’ve only added functionality for templates I use personally.

## Usage

Simply run `generate.py` followed by the names of templates **exactly** as written below, e.g.:

`python3 generate.py Swift macOS`

This will create a file `generated.gitignore` with the given templates combined with headers like this:

```
##############################
# Swift                      #
##############################
```

- [C++](https://github.com/github/gitignore/blob/master/C%2B%2B.gitignore)
- [CMake](https://github.com/github/gitignore/blob/master/CMake.gitignore)
- [Java](https://github.com/github/gitignore/blob/master/Java.gitignore)
- [JetBrains](https://github.com/github/gitignore/blob/master/Global/JetBrains.gitignore)
- [macOS](https://github.com/github/gitignore/blob/master/Global/macOS.gitignore)
- [Rust](https://github.com/github/gitignore/blob/master/Rust.gitignore)
- [Swift](https://github.com/github/gitignore/blob/master/Swift.gitignore)
- [Windows](https://github.com/github/gitignore/blob/master/Global/Windows.gitignore)

If you want a template not on here, simply add it to `templates.json` and it will work :)
