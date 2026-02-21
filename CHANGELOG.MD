# 📦 Feb 21, 2026 — Modpack V1.2.1  
## 🧩 TUFM Mod v0.0.2.2

This update focuses on **spawn balancing, progression clarity, and dimension expansion**.  
Our goal with this patch was to refine gameplay pacing while introducing meaningful new content.

---

# ➕ Added

## 🧪 Eli’s Powder

We discovered that **Eli’s Powder** did not have a properly registered crafting recipe.  
This has now been resolved.

### ✅ What Changed
- Restored and properly registered the **intended crafting recipe**.
- Ensured it appears correctly in JEI/recipe viewers.
- Verified server/client sync for multiplayer environments.

### 🎯 Why This Matters
Eli’s Powder plays a role in progression systems tied to TUFM content.  
Without a working recipe, players were locked out of its intended use case.  
This fix restores intended gameplay flow.

---

## 🌌 The Upside Down (New Dimension)

We have officially introduced **The Upside Down** as a playable dimension.

### 🌍 Dimension Overview
- **Biomes Included**
  - All base biome variants
  - **Blue Forest** (custom biome)

- **New Mob**
  - **Blue Slime**

- **Access Recipe**
  - 👀 Requires something blue…
  - (Yes, we’re hinting at Lapis. Explore. Experiment.)

---

# 🔄 Changed

Balancing was the core focus of this update. We analyzed spawn rates, XP gain, and mob difficulty curves to better match intended progression pacing.

---

## 💎 Diamond Chicken

The Diamond Chicken is intended to be:
> Rare. Dangerous. Worth hunting.

However, its previous configuration didn’t reflect that intention properly.

---

### 📊 Spawn Weight Adjustment

| Old | New |
|------|------|
| 10 | **13** |

- At **10**, it spawned too rarely.
- At **20**, it appeared excessively.

We chose **13** as a midpoint to:
- Slightly improve encounter frequency
- Preserve its rarity
- Avoid flooding spawn tables

This should make finding one possible — but still exciting.

---

### ⚔️ Combat Rebalance

We want the Diamond Chicken to feel threatening — not unfair.

| Attribute | Old | New |
|------------|------|------|
| Movement Speed | 0.2 | **0.5** |
| Attack Strength | 3 | **2** |
| Attack Knockback | 0 | **0.3** |

#### 🧠 Why These Changes?

- **Movement Speed Increased**
  - Makes the encounter dynamic and aggressive.
  - Prevents easy kiting.

- **Attack Strength Reduced**
  - Encourages longer fights rather than burst deaths.
  - Makes difficulty come from mobility, not raw damage.

- **Knockback Added**
  - Creates positional pressure.
  - Makes combat feel impactful.

### 🎯 Intended Result
A faster, more engaging fight that rewards preparation — not just armor stacking.

---

## 🦴 Calcium Being

The Calcium Being was unintentionally becoming an XP farm due to:
- High experience drops
- Frequent spawning in Calcium Land

We adjusted spawn weight to correct progression pacing.

### 📊 Spawn Weight Adjustment

| Old | New |
|------|------|
| 10 | **6** |

### 🎯 Why?
- Reduces passive XP farming.
- Keeps Calcium Land viable without becoming overpowered.
- Encourages exploration over grinding.

---

## 🖼️ Paintings

We previously added a painting titled:

> **"PePe"**

But never documented it.

### 🖌️ Details
- Size: **16x16**
- Occupies: **1 block x 1 block**
- Fully survival-placeable

This was an oversight in documentation — now officially part of the mod.

---

# ❌ Removed

## 🛑 The S.I.D. Set

The S.I.D. set has been removed from the mod.

### Reasoning
- Did not align with current progression direction.
- Required future rework to match balance standards.
- Better to remove temporarily than leave incomplete or unbalanced.

It may return in a redesigned form in a future update.

---

# Feb 21, 2026 — Modpack v1.2

### Modpack Update (02/20/2026)
- Pushed the `02/20/2026` (V1.2) modpack build to the repository.

### TUFM Mod v0.0.2.1
- Added **TUFM Mod v0.0.2.1** to the modpack.

### GitHub
- Initialized repository for change tracking.
