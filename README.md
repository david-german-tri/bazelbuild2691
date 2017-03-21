This is a small reproducing example for https://github.com/bazelbuild/bazel/issues/2691.

```
bazel build -s --crosstool_top=//tools:default-toolchain :helloworld
```
