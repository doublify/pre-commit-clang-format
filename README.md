# ClangFormat hook for pre-commit

[ClangFormat](http://clang.llvm.org/docs/ClangFormat.html) package for [pre-commit](http://pre-commit.com).

## Using clang-format with pre-commit

```yaml
-   repo: git://github.com/doublify/pre-commit-clang-format
    sha: master
    hooks:
    -   id: clang-format
```
