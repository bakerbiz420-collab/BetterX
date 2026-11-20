# BetterX

A free gear-comparison addon for World of Warcraft: Forever.

## Download and update

**[Download the latest release](https://github.com/bakerbiz420-collab/BetterX/releases/latest)**

Under **Assets**, download **BetterX-0.3.46.zip**. The automatic **Source code** downloads are not installers.

1. Exit World of Warcraft completely.
2. Extract the ZIP. Safari may already have extracted it on Mac.
3. Find the **BetterX folder directly containing BetterX.toc** inside any outer download folder.
4. Copy that BetterX folder into `_forever_/Interface/AddOns/`, replacing the existing addon.
5. Confirm the final path is `_forever_/Interface/AddOns/BetterX/BetterX.toc`.
6. Restart WoW and confirm **0.3.46** in BX.

Leave the game's **WTF** folder and saved preferences alone. Windows and Mac instructions are also included in the download.

## New-gear equip offers

Open **BX → Upgrade equipping → Ask before equipping**. Newly acquired qualifying gear is checked automatically while questing or in dungeons. A small **Equip / Skip / Ignore item** window asks what you want to do. Combat queues the check until afterward, when the recommendation is evaluated again.

Options include locked equipment slots, a minimum item upgrade percentage (default **5%**), new items only, binding and weapon confirmations, and replacement notices. Both-hand arrangements always ask. Blizzard binding confirmation remains manual.

**Automatic** equipping is also available. Existing Automatic settings switch to Ask once in this update; a later explicit Automatic selection is retained. Off stays Off, and new installations default Off until you select a mode.

With **Newly acquired items only** checked, an item already in your bags at login/reload is not a new arrival. **Check my bags** optionally checks existing inventory, following the selected mode.

## Comparisons

Main tooltips show **item-to-item BX percentage and BX score**. Select Damage only, Healing only, or either mixed-role priority where supported. Single-role choices ignore the other role; mixed choices show both. Sustain remains included in scoring.

The old details arrow and retained tooltip have been removed. The replacement optional **Alt-right-click** shortcut is currently unreliable and remains under investigation. Use the BX menu's item-ID/link comparison for detailed results.

## Verification and feedback

- **4,244 client regression checks** pass; 17 Lua modules compile.
- Last full all-28-profile, hybrid, pet/proc regression run: **42,703 checks**. Scoring is unchanged in this update.
- A tester confirmed a new-arrival offer appeared immediately and equipped the item after choosing Equip. Broader live coverage, including combat deferral, is ongoing; offline checks do not establish every native-game interaction.
- The release ZIP's 21 addon files are verified against the published SHA256 manifest.

This is a test build. Percentages describe modeled item values, not exact DPS/HPS output or universal BiS labels. For a problem, include the version, class, level, selected comparison and screenshots of both items in a GitHub issue. Do not include passwords or account tokens.
