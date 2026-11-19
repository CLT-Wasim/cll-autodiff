# cll-autodiff

**automatic differentiation** — part of [CLL](https://github.com/CLT-Wasim/CLL), the Conserving Logic Language.

> Read [`AGENTS.md`](./AGENTS.md) first. It points at the binding rules; this README is only a summary.

## Purpose

Source-transform autodiff over CLL MIR. For `rev fn`, the backward pass recomputes inputs through the derived inverse instead of storing activations.

## Status

Pre-v1. Nothing here is shipped until a command produced the result and the result is in a
results table with the command that produced it. See the milestone list in
[`ROADMAP.md`](https://github.com/CLT-Wasim/CLL/blob/main/ROADMAP.md).

## Layout

* `src/`
* `tests/`

## Language policy

The MIR pass is Rust (it runs inside the compiler); the user-facing library is CLL.

## License

Apache-2.0. See [`LICENSE`](./LICENSE).
