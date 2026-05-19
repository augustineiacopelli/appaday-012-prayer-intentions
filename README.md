# 012 · Prayer Intentions

**AppADay** · Category: P · Productivity and Life · Built: 2026-05-19

A quiet, devotional app for capturing and praying through personal intentions. Add the names and intentions of those you're carrying in prayer, then work through them one card at a time.

## What It Does

- Add intentions with a name and optional note
- Swipe through a prayer card deck — swipe right (or tap "Prayed") to mark complete, swipe left (or tap "Skip") to cycle to the back
- View all intentions in a filterable list (All / Unprayed / Prayed), toggle status, or delete
- Stats bar shows total, prayed, and remaining at a glance
- All data persists in localStorage — your intentions are there when you come back

## How to Use

1. Open the app and tap **+ Add** to enter a name or intention
2. Switch to **Pray** and work through the card deck
3. Drag a card right to mark as prayed, left to skip to the next
4. Use the **All** tab to review, toggle, or remove intentions

**Keyboard shortcuts (Pray view):** `→` or `P` to mark prayed · `←` or `S` to skip

## Technical Notes

- Vanilla HTML, CSS, JavaScript — no frameworks, no dependencies
- Google Fonts: Cormorant Garamond (display) + Lato (body)
- Touch and mouse drag both supported with directional tinting
- localStorage key: `appaday-012-intentions`
- Single `index.html`, mobile-first at 375px

## Definition of Complete

- [x] Add intentions with name and optional note
- [x] Swipeable card deck with drag and button controls
- [x] Mark as prayed or skip to back of queue
- [x] Full list view with filter and delete
- [x] Stats bar (total / prayed / remaining)
- [x] localStorage persistence
- [x] Mobile-friendly, 375px viewport
- [x] Visually polished — candlelight aesthetic, Cormorant Garamond typography
- [x] Published to GitHub Pages
