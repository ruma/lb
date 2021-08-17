# `lb` - Low Bandwidth

A wrapper around `ruma` to implement [MSC3079](https://github.com/matrix-org/matrix-doc/pull/3079), otherwise known as "Low Bandwidth Matrix"

**Note:** This crate is *WIP*, stability guarantees aren't in place at this time, and APIs can change drastically from version to version. Pinning dependencies to individual commits or versions is recommended.

**Note:** The fate of this crate is unstable, the current implementation is mostly meant as a stop-gap solution before a more integrated and maintainable approach is found inside `ruma`, as such, performance is not (yet) optimal.