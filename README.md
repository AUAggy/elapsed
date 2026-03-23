# ELAPSED

A clock that tells you where you are in time, not what time it is.

Four rows. Four scales. Each one a progress bar showing how much of that period has already gone.

```
WEDNESDAY   ████████░░░░░░░░░░░░  42%
WEEK 12     ████████░░░░░░░░░░░░  43%
MARCH       ███████████░░░░░░░░░  55%
2026        ████░░░░░░░░░░░░░░░░  21%
```

Tap once to flip from elapsed to remaining. Tap again for nothing: just labels in the dark. Tap a third time to return. The person who wants emptiness gets emptiness.

---

## What each row means

**WEDNESDAY:** not how much of Wednesday is done, but how far through the week you are, right now, on a Wednesday. The week starts Monday.

**WEEK 12:** which week of 52 this is, expressed as a percentage. Advances once a week. Useful if you think in school terms, project sprints, or financial quarters.

**MARCH:** how far through the current month you are, with intra-day precision.

**2026:** how far through the calendar year, measured to the minute.

---

## What was considered and left out

**An hour row.** How far through today are you? The idea was appealing but the Wednesday row already answers it well enough, and an hour row would feel restless, demanding to be checked every few minutes. Left out.

**Color.** Considered briefly. Dropped immediately. The dots glow against darkness the way time feels: small bright things against a vast dark background. Color would import meaning the app did not earn.

**A light mode.** Some people prefer lighter backgrounds. But black is not a style choice here. It is the app. Invert it and the dots become dark marks on a bright field. They lose their glow. They become a spreadsheet.

**A heartbeat dot.** A single blinking dot to show the app is alive. Attractive idea until you look closely: every dot in the grid means something, on or off. A blinking dot reads as a glitch, not a pulse. Dropped.

**Amber warmth shifting through the year.** January cold white, December warm amber. Poetic in theory. Broken in practice: December in the UK is cold and dark. The metaphor only works in climates it was never designed for. Dropped.

**"THIS WEEK", "THIS MONTH", "THIS YEAR" as labels.** Cleaner language, but it removes the proof that the app knows where it is. WEDNESDAY proves it is Wednesday. MARCH proves it is March. The labels do two jobs: they orient and they anchor. Kept as is.

---

## On loading

When the app opens, the bars pour in from left to right, one row after the next. This happens once, then stops. It is not decoration. It is the only way to show that time has been accumulating before you arrived.

---

## Origin

This app is a direct homage to the Nothing Phone dot-matrix widget, seen on the Nothing Phone 4a Pro. That widget stopped the author cold. It is one of those rare designs that makes you feel something before you understand it. Kudos to the Nothing design team. After much exploration, iteration, and things considered and discarded, their original layout proved to be very well thought out. This is a PWA port of that idea, built to run in a browser on any device.
