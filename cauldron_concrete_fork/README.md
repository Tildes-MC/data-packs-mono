# Cauldron concrete

Fork of the [vanilla tweaks](https://vanillatweaks.net/picker/datapacks/) datapack with fixes for minecraft 1.21.11.

## Changelog

In 1.21.11 the following change has been made

> - `minecraft:filtered`
>   - The field `modifier` has been replaced with two fields:
>     - `on_pass` – function or a list of functions to run when `item_filter` predicate passes.
>     - `on_fail` – function or a list of functions to run when `item_filter` predicate fails.

All `modifier` function instances in cauldrone concrete have been replaced with `on_pass`.
