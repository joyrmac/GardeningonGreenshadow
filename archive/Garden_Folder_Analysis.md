# Garden Folder Analysis

> Full audit of the gardening folder — what's here, what's missing, what needs fixing.
> Generated March 8, 2026.

---

## Folder Structure Summary

```
gardening/
  Garden_Overview.md           -- Navigation hub (good shape)
  Garden_Folder_Analysis.md    -- You are here
  beds/                        -- 5 files covering major + small gardens
    Bloomveil.md               -- 5-zone flower garden ✓
    Edgeworth_Corner.md        -- Grid pollinator garden + shade bed ✓
    Wildwood.md                -- Veggie beds, cut flowers, herbs, corn, melons, pumpkins ✓
    Fernwood.md                -- Shade garden ✓
    Small_Gardens.md           -- Cat, Porch, Blueberry/Raspberry, Front ✓
  guides/                      -- 7 how-to guides
    Planting_How_To.md         -- Seed starting, sowing, transplanting ✓
    Garden_Care_and_Troubleshooting.md -- Maintenance, pests, diseases ✓
    Seasonal_Planting_Guide.md -- Year calendar ✓
    Planting_Calendar_NC.md    -- Crop dates for Zone 7b/8a ✓
    March_Garden_Checklist.md  -- March tasks ✓
    Soil_Notes.md              -- ⚠️ Almost empty (just an image link)
    Garden_Todo_List.md        -- ⚠️ Stale, needs rewrite
  inventory/                   -- 8 files (master list + CSVs + shopping lists)
    Master_Seed_and_Plant_List.md -- 228 items consolidated ✓
    (+ 5 CSV data files + 2 shopping lists)
  reference/                   -- 3 reference files
    Previous_Owner_Notes.md    -- Kelli's tips ✓
    Garden_Signs.md            -- Sign designs ✓
    NC_Native_Recommendations.md -- Native additions by bed ✓
  photos/                      -- 49 images ✓
  archive/                     -- 43 ChatGPT conversation dumps (reference only) ✓
```

---

## What's Working Well

These files are thorough, well-organized, and don't need changes:

- **Garden_Overview.md** — Clear navigation hub with property map, links to all files, file tree
- **Bloomveil.md** — Detailed zone plans with planted dates (3/8/26 dahlia tubers logged)
- **Edgeworth_Corner.md** — Grid layout with CSV data files backing it up
- **Wildwood.md** — Comprehensive: 8 veggie beds, corn circle, herb spiral, pond, cut flowers, pumpkins
- **Small_Gardens.md** — 7 gardens with specific plant lists, layouts, and cautions
- **Master_Seed_and_Plant_List.md** — All 228 items consolidated with sources and assignments
- **Planting_How_To.md** — Complete seed-starting through transplanting guide
- **Garden_Care_and_Troubleshooting.md** — Pest/disease ID, weekly checklists, monthly calendar
- **Seasonal_Planting_Guide.md** — Full year calendar with Bloomveil zone planting order
- **Planting_Calendar_NC.md** — Crop-specific dates for Zone 7b/8a
- **Garden_Signs.md** — 9 sign designs with shopping lists
- **NC_Native_Recommendations.md** — Native additions organized by bed

---

## Issues Found

### 1. Garden_Todo_List.md is stale
**File:** `guides/Garden_Todo_List.md`
**Problem:** 18 items, most unchecked, some vague ("Clay", "Plant weed"), one blank entry. Doesn't reflect what's actually been done (dahlias planted 3/8, lily-of-the-valley planted 3/8, buckwheat cover crop in corn circle planted 3/8). Missing newer tasks like kit placement decisions and mailbox redo.

**Fix:** Rewrite with current status — mark completed items, remove irrelevant ones, add missing tasks.

---

### 2. Bloomveil dahlia end-of-season advice is wrong
**File:** `beds/Bloomveil.md`, line 161
**Problem:** Says "dig tubers, let dry 1-2 days, store in peat moss" — but you leave dahlias in the ground. This section should reflect your actual practice, not the textbook default.

**Fix:** Update to match what you actually do (leave in ground with heavy mulch, or whatever your method is).

---

### 3. Fernwood is missing established plants
**File:** `beds/Fernwood.md`
**Problem:** Doesn't mention the bluebells that are already growing there, or the miniature daffodils (Tête-à-Tête) from the previous owner. The lily-of-the-valley is documented as planted 3/8/26 and noted as circling the bluebells — but the bluebells themselves aren't listed anywhere.

**Fix:** Add an "Already Established" section documenting what's growing from the previous owner.

---

### 4. No bed file for Wayward Meadow
**Problem:** Wayward Meadow appears on the property map and has a garden sign designed for it, but there's no plan in `beds/`. If the Prairie Habitat kits are going there, it needs its own file.

**Fix:** Create `beds/Wayward_Meadow.md` with location, dimensions, and initial plan.

---

### 5. Mailbox area plan is generic
**File:** `beds/Small_Gardens.md`, lines 159-163
**Problem:** The mailbox section is just a quick bullet list (zinnias, nasturtium, poppies, lavender, rosemary, citronella, creeping phlox or clover). If you're redoing this area with a kit or specific design, the plan needs to be fleshed out.

**Fix:** Expand once kit placement is decided, or flag as "needs design."

---

### 6. Soil_Notes.md is nearly empty
**File:** `guides/Soil_Notes.md`
**Problem:** Contains only an image link. No actual soil info — even though soil types, amendments, and pH are referenced throughout the other files (blueberry acidity, dahlia drainage, shade garden amendments, corn circle buckwheat cover crop).

**Fix:** Consolidate soil info that's scattered across other files into this one guide.

---

### 7. Unplanned garden areas on the property map
**Problem:** Several named areas from the property map have no plans anywhere:
- **The Gloam** — Has a sign designed (dusty lavender + white) but no bed file or section
- **Swingnook** — On the map, no mention elsewhere
- **South Grove** — On the map, no mention elsewhere
- **Maple Shrine** — On the map, no mention elsewhere
- **Hazel Nest** — On the map, no mention elsewhere

**Fix:** These don't all need full plans right now, but at minimum they should be listed in the Overview with a one-line description of what they are or will be, so nothing falls through the cracks.

---

### 8. Wagon seedlings need final placement
**Problem:** Snapdragons, hollyhocks, poppies, and milkweed started in the wagon don't have assigned garden locations yet. They're growing but have no plan for where they go when they're ready to transplant.

**Fix:** Decide destinations and note them in the relevant bed files.

---

### 9. Kit placement not documented
**Problem:** You have Prairie Habitat kits but haven't logged which gardens they're assigned to. Once decided, this needs to go in the relevant bed files and the master inventory.

**Fix:** After decisions are made, update bed files and Master_Seed_and_Plant_List.md.

---

## Action Checklist

| # | Task | Priority | File(s) Affected |
|---|------|----------|-----------------|
| 1 | Rewrite Garden_Todo_List.md | High | `guides/Garden_Todo_List.md` |
| 2 | Fix dahlia end-of-season section | Medium | `beds/Bloomveil.md` |
| 3 | Add established plants to Fernwood | Medium | `beds/Fernwood.md` |
| 4 | Create Wayward Meadow bed file | Medium | `beds/Wayward_Meadow.md` (new) |
| 5 | Flesh out Soil_Notes.md | Medium | `guides/Soil_Notes.md` |
| 6 | Add unplanned areas to Overview | Low | `Garden_Overview.md` |
| 7 | Expand mailbox area plan | Low | `beds/Small_Gardens.md` |
| 8 | Assign wagon seedling destinations | Low | Various bed files |
| 9 | Document kit placements (once decided) | Low | Various bed files + inventory |

---

## What's NOT in the Folder (and whether it should be)

| Missing? | Needed? | Notes |
|----------|---------|-------|
| Watering schedule | Maybe | Rules are scattered across files. Could consolidate if helpful |
| Budget tracker | Optional | $861.57 in Jan-Feb orders tracked in inventory. No running total |
| Harvest log | Not yet | Would be useful once veggies start producing |
| Plant journal / garden diary | Optional | For tracking what worked, bloom times, pest issues year over year |
| Companion planting chart | No | Already covered well in Planting_How_To.md |
| Photo index | No | 49 photos with UUIDs — would be nice but not essential |

---

*This file will be updated as issues are resolved.*
