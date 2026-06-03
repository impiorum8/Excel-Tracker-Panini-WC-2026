# Excel-Tracker---Panini-WC-2026-Sticker-Collection
This is an Excel-based sticker tracker for the FIFA World Cup 2026 Panini sticker album.

# WC26 Panini Sticker Tracker

An Excel-based sticker tracker for the **FIFA World Cup 2026 Panini sticker album**.

This tracker helps you keep an overview of:

* which stickers you already have
* which stickers are still missing
* which stickers you have as duplicates for exchange
* how many copies of each sticker you own

Instead of marking stickers manually on paper or searching through long lists, you can increase the count of each sticker in Excel and the file updates the summary, missing list, and duplicate list automatically.

---

## Why this tracker is useful

When collecting stickers, it can become difficult to keep track of everything, especially when you have many duplicates.

This Excel tracker makes it easier because:

* collected stickers are automatically marked in the summary
* missing stickers are listed automatically
* duplicate stickers are listed automatically in a readable exchange format
* each sticker can have a count, not only “yes/no”
* team stickers and special stickers are separated clearly
* the tracker can be used while opening packs
* exchange lists can be copied and shared easily

For example, if you have several duplicates, the tracker can show them like this:

```text
2x MEX 1, 1x NED 5, 3x FWC 7
```

The missing-sticker list can also automatically remove stickers once you mark them as collected.

---

## Sheets included

### Summary

The `Summary` sheet gives an overview of all sticker codes.

When a sticker count is higher than `0`, the sticker code turns green. This makes it easy to see your album progress at a glance.

### Group sheets

The team stickers are separated into group sheets:

* `A-B`
* `C-D`
* `E-F`
* `G-H`
* `I-J`
* `K-L`

Each sheet includes the teams from those groups and their sticker codes.

You enter or increase the number of stickers you own in the count cells next to each sticker.

### Others

The `Others` sheet is used for non-team stickers, such as:

* `00`
* `FWC`
* `CC`

### Missing Stickers

The `Missing Stickers` sheet automatically lists stickers that you do not have yet.

If a sticker count is `0`, it appears in the missing list.
If the count becomes `1` or higher, it is removed from the missing list.

Example:

```text
MEX 1, MEX 2, MEX 3, MEX 4, MEX 5
```

After collecting `MEX 2` and `MEX 3`, the list becomes:

```text
MEX 1, MEX 4, MEX 5
```

### Extra Stickers

The `Extra Stickers` sheet automatically lists your duplicates for exchange.

The tracker assumes that one copy belongs in your album. Everything above `1` is treated as an extra sticker.

Example:

```text
Sticker count = 1 → not listed as extra
Sticker count = 2 → 1x extra
Sticker count = 3 → 2x extra
```

So if you own three copies of `MEX 1`, the extra list shows:

```text
2x MEX 1
```

---

## Available versions

There are three versions of the tracker. The structure is the same in all versions. Only the input method is different.

### Version 1 — Double-click / Right-click

This version uses macros.

How to use:

* double-click a count cell to increase the number
* right-click a count cell to decrease the number

This is the fastest version for personal use if you are comfortable enabling macros.


### Version 2 — Plus / Minus buttons

This version also uses macros.

How to use:

* click `+` to increase the count
* click `-` to decrease the count

This version is useful if you prefer visible buttons instead of double-clicking or right-clicking.


### Version 3 — Excel spin buttons

This version does not require macros.

How to use:

* use the small Excel spin buttons next to the sticker count cells
* click up/down to increase or decrease the count

This is the safest version if you do not want to enable macros.

## How to use the tracker

1. Open the Excel file.
2. Go to the relevant group sheet, for example `A-B`.
3. Find the sticker code or player.
4. Increase the count when you get that sticker.
5. Check the `Summary` sheet to see your progress.
6. Check `Missing Stickers` to see what you still need.
7. Check `Extra Stickers` to see what you can exchange.

---

## Macro warning

The `.xlsm` versions use VBA macros only for the input controls.

The macros are used for:

* increasing sticker counts
* decreasing sticker counts
* making the tracker easier to use

They are not required for the formulas themselves.

If you do not want to enable macros, use the `.xlsx` spin-button version.

---

## Compatibility

This tracker is designed for the desktop version of Microsoft Excel.

Some features may not work correctly in:

* Excel Online
* mobile Excel
* other spreadsheet programs such as Google Sheets, LibreOffice, or Numbers

The macro versions require Microsoft Excel with macros enabled.

---

## Notes

This is a fan-made Excel tracker.

It is not affiliated with FIFA, Panini, or any official World Cup organization.

Sticker names, codes, and structure are provided for tracking purposes only.
