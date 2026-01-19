# Game is Hard — Level 28 (Walkthrough + Mini Clone)

**One-line solution:** Tilt your phone **left**, **right**, then **up** (toward the top dot) and **hold** each tilt until every purple dot inflates to max size.

Link: [Game is Hard Level 28](https://gameishard.org/level/28)

---

## Why this repo exists

Level 28 looks like a basic “pinch to zoom” trap. It isn’t. It’s a tilt/gyro level.

This repo gives you:
- A clean, fast walkthrough you can paste into your own guide site
- A tiny browser demo that recreates the core mechanic (tilt-to-inflate)

---

## Walkthrough (recommended wording)

### What you do
1. **Stop touching the screen.** Grip the phone by the sides.
2. **Tilt left** and **hold** until the **left dot** grows to full size.
3. **Tilt right** and **hold** until the **right dot** grows to full size.
4. **Tilt up** (top edge away from you) and **hold** until the **top dot** grows to full size.
5. Once all three are maxed, the level clears.

### Common fails
- “Lazy tilt” (too small an angle). Go harder. Think **45°**.
- Switching dots too early. Finish one dot fully before moving on.
- Pinch/zoom. The game ignores it here.

---

## Pro-tip (fast clear)
Do the **left → right → up** motion in one smooth “U” swoop, but only if you can keep each dot in its “feed zone” long enough to cap out.

---

## Code example: run the mini clone

### Option A: quick open
- Open `index.html` in a browser.

### Option B: phone testing (recommended)
Mobile browsers often restrict motion sensors unless you:
- serve the file over HTTPS, and/or
- tap a permission button first (the demo includes one)

---

## Controls (demo)
- **Phone:** tilt (device orientation)
- **Desktop fallback:** arrow keys
  - Left/Right = feed left/right dot
  - Up = feed top dot

---

## Repo layout suggestion

/README.md  
/index.html  

---

## License
MIT
