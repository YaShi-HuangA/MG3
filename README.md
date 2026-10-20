# MG3
## Devlog
Write your Devlog here.
## Devlog
1.Default values
The default values are `0` for floats, `0` for ints, `false` for bools, and `null` for strings.
2.How is Update() called?
Unity automatically calls `Update()` once per frame when the script is enabled and its GameObject is active. We do not need to call it ourselves.
3.How does KickWeapon use the timer?
`KickWeapon` starts a timer when the kick activates. In `Update()`, it checks whether the timer has finished and deactivates the kick when time runs out.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)