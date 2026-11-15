# gibbert's fork

Personal fork merging a few PRs and branches I care about:

- `main`: Follows upstream
- `feat/cursor-zoom`: Frozen at `6253a42509bae3f16d86357e7a870fc955f29636` from [Atan-D-RP4/niri](https://github.com/Atan-D-RP4/niri)
- `gibbert` (based on `main`): Includes these changes:
    - **Zoom / Screen magnifier** ([Atan-D-RP4/niri](https://github.com/Atan-D-RP4/niri/tree/feat/cursor-zoom-v4))
        - Uses `feat/cursor-zoom-v4` over `feat/cursor-zoom`. This branch has more bugs, but is actively developed and fixes more issues.
        - [PR: Feat/cursor zoom](https://github.com/niri-wm/niri/pull/3246)
        - [Discussion: Continuation of discussion for zoom/magnifier interface and impl in #3246](https://github.com/niri-wm/niri/discussions/3285)
    - **Tearing** ([urayde/niri](https://github.com/urayde/niri))
        - Also includes the [`wp_pointer_warp_v1` PR](https://github.com/niri-wm/niri/pull/4001)
        - [Issue: Tearing flip support](https://github.com/niri-wm/niri/issues/844)
        - [Smithay PR: Initial support for DRM async page flip v2](https://github.com/Smithay/smithay/pull/1948)
        - [Smithay PR: Implement wayland side of tearing control](https://github.com/Smithay/smithay/pull/1325)
    - **Force render** ([MithicSpirit/niri](https://github.com/MithicSpirit/niri/tree/force-render-v2))
        - [PR: feat: force render (v2)](https://github.com/niri-wm/niri/pull/4392)
    - **SVG cursors** ([HigherOrderLogic/niri-wm](https://github.com/HigherOrderLogic/niri-wm/tree/c))
        - [PR: cursor: support KDE's svg format](https://github.com/niri-wm/niri/pull/4760)

See niri's README [here](../README.md).
