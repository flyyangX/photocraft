# Simplified Chinese UI review evidence

Original UI screenshots rendered by PhotoCraft's offscreen `snapshot` example on macOS (Apple M4, Metal), at 1440 x 900 points and 2x scale. The documents are synthetic blank canvases.

Before: upstream `a0d49de0478fbaa91733517297432e7bbe5b479f` UI and catalog. After: `fix/complete-simplified-chinese-ui`.

Attribution: PhotoCraft contributors; source https://github.com/storytold/photocraft. The contribution and generated review evidence use MIT OR Apache-2.0 (license files included).

Reproduce each view using the matching `*-script.json`:

```sh
cargo build --locked -p photocraft-ui-egui --example snapshot
target/debug/examples/snapshot --out ui.png --size 1440x900 --scale 2 --script "$(cat properties-script.json)"
```

The evidence branch is separate from the pull request's source diff.
