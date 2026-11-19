# BetterX

A free gear-comparison addon for World of Warcraft: Forever.

## Download

**[Download the latest update](https://github.com/bakerbiz420-collab/BetterX/releases/latest)**

Under **Assets**, download **BetterX-0.3.39.zip**.
The automatic **Source code** downloads are not the addon installer.

## Install or update — Windows and Mac

1. Exit World of Warcraft completely.
2. Extract the ZIP. Safari may already have extracted it.
3. Open any outer download folder until you find the **inner BetterX folder containing BetterX.toc**.
4. Copy that inner folder into your existing `_forever_/Interface/AddOns/` folder, replacing BetterX when prompted.
5. Confirm the final path is `_forever_/Interface/AddOns/BetterX/BetterX.toc`.
6. Restart the game, enable **Better X**, and confirm **0.3.39** in BX.

Saved preferences stay in the game's **WTF** folder. Leave WTF alone.

## Comparisons

Choose **Damage only**, **Healing only**, **Damage first / Healing second**, or **Healing first / Damage second** where supported. Single-role choices ignore the other role; mixed choices show both. Resource costs, useful regeneration and survivability remain part of scoring.

The main tooltip shows **item-to-item BX percentage and BX score**. There is no questing/dungeon damage-playstyle switch.

## Optional details

Enable **Show clickable details icon in item tooltips** if desired. It is off by default for new preferences; existing detail opt-ins are preserved as icon access.

Hover an unequipped item, move onto the retained comparison and click **+** to see the compared gear, overall impact and explanations. Close details with **X**, **Close** or **Escape**. Leave, click away or press Escape to dismiss a retained tooltip. Details never open automatically and optional controls hide in combat.

## Verification and feedback

Current build: **0.3.39**. Supports 28 profile routes, support roles, pets and supported procs. The scoring foundation and focused in-game tooltip/details behavior have been accepted by the tester; aesthetic polish is deferred.

- 0.3.39: **4,116 client/UI regression checks**; 16 Lua modules compile.
- Unchanged scoring engine: last full 0.3.38 run passed **42,580 checks**.
- Release ZIP contents are checked against the included SHA256 manifest.

For surprising advice, open an issue with the version, class, level, selected comparison and a screenshot of both items. Do not include passwords or account tokens.

This remains a test build with documented model limits. BX percentages compare modeled values; they are not exact DPS/HPS measurements or universal BiS labels.