# `target_disable_static_analysis` function

This function disables static analysis for the given target:

```cmake
target_disable_static_analysis(some_external_target)
```

There is also individual functions to disable a specific analysis for the target:

- `target_disable_cpp_check(target)`
- `target_disable_vs_analysis(target)`
- `target_disable_clang_tidy(target)`