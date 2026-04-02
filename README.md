# ECHO — Same Space. Infinite Realities.

A cinematic interactive 3D experience built with Three.js. One architectural space rendered across 4 completely different worlds — Ancient Ruins, Submerged Cathedral, Neon Nightclub, and The Void. Each world has unique lighting, atmosphere, particles, creatures, and secrets.

## 🚀 How to Run

https://realityinus.netlify.app

## 🎮 Controls

| Action | Input |
|--------|-------|
| Orbit camera | Mouse drag / Touch drag |
| Zoom | Scroll wheel / Pinch |
| Next world | `W` or `→` arrow or `→` button |
| Previous world | `Q` or `←` arrow or `←` button |
| Jump to world | Keys `1` `2` `3` `4` |
| Click dots | Bottom navigation dots |
| Fullscreen | `F` key or ⊡ button |


---

## 🌍 The 4 Worlds

| World | Era | Atmosphere |
|-------|-----|------------|
| Ancient Ruins | 400 AD | Torch fire, dust shafts, stone debris |
| Submerged Cathedral | 2000 AD | Caustic light, fish, jellyfish, bubbles |
| Neon Nightclub | 2087 AD | Disco ball, strip lights, neon rain |
| The Void | ∞ | Floating fragments, stars, deep space |

---

## ⚙️ Technical

- **Renderer**: Three.js r128 (loaded from CDN)
- **Audio**: Web Audio API — generative drone, no audio files
- **Physics**: Custom boids-free fish AI with cursor flee, wall avoidance
- **Particles**: Per-world CPU particle systems, delta-time normalized
- **Transitions**: Particle storm — geometry sampled from current world, explodes and morphs to destination palette
- **Performance**: Auto-detects mobile/Edge, scales particles and shadows accordingly
- **File size**: Single HTML file, ~2000 lines

---

## 📁 File Structure

```
echo-worlds/
└── index.html    ← entire experience, self-contained
└── README.md
```

No build tools. No npm. No config. Just open and run.
