# Better X 0.3.56 — Test Build

A free gear-comparison addon for World of Warcraft: Forever, levels 1–60.

## Download and update

Latest release: https://github.com/bakerbiz420-collab/BetterX/releases/latest
Download **BetterX-0.3.56.zip** under Assets. GitHub's automatic Source code
archives are not addon installers.

1. Exit World of Warcraft completely.
2. Extract the ZIP. Safari may already extract it on Mac.
3. Find the **BetterX folder directly containing BetterX.toc** inside any outer
   download folder. Copy that folder into `_forever_/Interface/AddOns/`, replacing
   the existing BetterX folder/files.
4. Final path: `_forever_/Interface/AddOns/BetterX/BetterX.toc`.
5. Restart WoW, enable Better X, and confirm version 0.3.56 in BX.

Keep the game's WTF folder and saved preferences. Do not install a folder named
BetterX-0.3.56 or BetterX-0 as the addon. Windows/Mac instructions are included.

## One window, four tabs

- **Gear:** class/spec target, role priority and tooltip options.
- **Equipping:** upgrade mode, minimum percentage, locked slots and bag check.
- **Compare items:** paste an item link or ID for detailed comparisons.
- **Insights & history:** optional personal activity, death history and messages.

Main tooltips show item-to-item percentage and BX score. Overall modeled impact
and health/armor tradeoffs are in details. Damage/Healing choices remain
separate; mixed priorities show both. Ordinary durability no longer turns
improved damage/healing output into an output downgrade; tank defense and
actual resource/health mechanics remain relevant. Percentages are item values,
not promises of an exact DPS/HPS gain or universal best-in-slot ranking.

## Upgrade offers and binding approval

Open BX → Equipping and choose Ask before equipping or Automatic. New installs
default Off. New qualifying bag gear is checked automatically. Offers wait
through combat, shopping and trading, then recheck current gear and options.
A single small Equip / Skip / Ignore item box advances through queued items.
Talent and active-spec changes also review carried bags, even with new-only
selected, and ask before applying resulting upgrades after combat.

With binding confirmation enabled (default), the first Equip click only opens
**Bind & Equip / Cancel** in that same box. No equip request is sent before
explicit Bind & Equip approval. Cancel/close does not approve. Refundable items
also require explicit confirmation. Blizzard may show its own warning afterward.

Lock selected slots and choose a minimum item upgrade (default 5%). Empty-slot
upgrades without a positive percentage baseline ask for review. A statless item
is not automatically an output upgrade merely because it fills an empty slot.
New-only normally excludes old inventory at login; Check my bags rechecks it.
Ignore is persistent; session Skip is reconsidered after a talent/spec change.

## Performance Insights (optional)

Enable recording under Insights & history. Private after-combat messages have
a separate checkbox, off by default; they appear only in your own chat window.
Advice uses your recorded activity, separated by active spec and situation,
with evidence thresholds. It does not automatically change your gear priorities.

Public casts and death notifications can be recorded. Damage/healing results
are used only when accessible. On clients restricting combat-log access,
detailed damage causes and outcome-based advice remain unavailable/unknown;
BX does not bypass restrictions or invent results. Initial suggestions concern
repeated overhealing, overkill and low-mana patterns, not proven optimal rotations.
Shields/absorbs and recovery between pulls are not measured in this test version.

History retains 30 days of daily summaries, up to two years of older weekly
summaries, and lifetime totals. Death history distinguishes recorded lethal
hits from preceding damage, with up to 10 seconds/32 hits per recent recap and
20 detailed recaps total. NPCs may be named; player opponents are anonymous.
There is a two-click reset. No general raw combat log or other players' names
or GUIDs are saved.

## Verification and current limits

- 6,735 current client regression assertions pass; 18 Lua modules compile.
- Last full all-28-profile/hybrid/pet/proc suite: 44,846 assertions. Subsequent
  changes were tested in the client suite; unchanged numerical matrices were
  not repeatedly rerun.
- Native testers confirmed the basic arrival/equip offer and the startup warning
  fix. The newest tabbed layout, Sky Elf identity compatibility and broader
  death/message coverage still need in-game acceptance. Offline tests do not
  prove every native client interaction.
- Sky Elf name/faction aliases now resolve to the researched Skyborne variants;
  unrecognized/neutral identities remain pending instead of guessing base stats.
- Optional Alt-right-click item details remains unreliable and deferred. Use
  **Compare items** for details. No retained tooltip/arrow is required.
- Inactive-spec bank/mail gear comparisons are not implemented. Bag reviews use
  the active build and selected gear priorities.
- The ZIP's 22 addon files are verified against the published SHA256 manifest.

Report issues with addon version, class, level, selected priority and screenshots
of the compared items. Do not include account credentials or personal saved data.
