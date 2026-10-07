# BetterDresser Packs

Screenshot packs for [BetterDresser](https://github.com/CoffeeXIV/BetterDresser), a Dalamud plugin with a catalog of every
piece of gear in FFXIV. The catalog shows each item as a screenshot of its model, and this repository is where those
screenshots are released.

**You don't need to download anything here by hand.** BetterDresser does it for you: open the catalog with `/bdresser`,
then the packs window with the download button at the bottom left, tick the packs you want and press Download.

## Getting BetterDresser

BetterDresser is installed from its own plugin repository: see [its page](https://github.com/CoffeeXIV/BetterDresser)
for the steps. The repo URL to add in `/xlsettings` → Experimental → Custom Plugin Repositories:

`https://raw.githubusercontent.com/CoffeeXIV/BetterDresser/main/repo.json`

## Packs

| Pack | What's in it |
|---|---|
| `male` | Head, body, hands, legs and feet, worn by a male character |
| `female` | Head, body, hands, legs and feet, worn by a female character |
| `accessories` | Earrings, necklaces, bracelets and rings |
| `weapons` | Weapons and shields, sheathed on the back or at the waist as each job wears them |

## Releases

- One release per game patch, tagged with the patch number, e.g. `7.58`. A second release within a patch is `7.58.1`.
- Every release has each pack in full (`male.zip`, ...) and a delta (`male-delta.zip`, ...) with only the screenshots
  that are new or changed since the release before.
- BetterDresser downloads a pack in full once, then only the deltas. It takes the full pack again when a release has
  no delta for it (screenshots were removed) or when the deltas would weigh as much as the full pack.
- Pre-releases are packs being tested: only dev and testing builds of BetterDresser see them.
