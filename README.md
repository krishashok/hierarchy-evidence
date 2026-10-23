# Hierarchy of Evidence

An interactive pyramid that explains the hierarchy of scientific evidence, climbed one tier at a time with shilajit as the worked example. Built for use inside a reel script.

Live: https://krishashok.github.io/hierarchy-evidence/

## Controls

| Input | Action |
| --- | --- |
| `↑` `→` `Space` `Enter` | climb one tier |
| `↓` `←` `Backspace` | go down one tier |
| `Home` / `End` | intro / verdict |
| `1`–`9`, `0` | jump to tier (0 = verdict) |
| `l` / `c` / `h` | toggle light theme / clean mode / hide cursor |
| tap or click a tier | jump to it |

## URL options for recording

| Parameter | Effect |
| --- | --- |
| `?level=N` | start at a given state: `0` intro, `1`–`9` tiers, `10` verdict |
| `?clean=1` | hide header, footer and navigation buttons |
| `?cursor=0` | hide the mouse cursor |
| `?card=0` | pyramid only, no explanation card |
| `?theme=light` | light theme |

Example for a clean portrait recording starting at the first tier:

```
https://krishashok.github.io/hierarchy-evidence/?level=1&clean=1&cursor=0
```

The layout switches automatically: portrait windows stack the pyramid above the card, landscape windows place them side by side.
