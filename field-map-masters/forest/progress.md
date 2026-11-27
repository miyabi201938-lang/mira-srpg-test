# Forest Terrain Work Progress

Updated: 2026-11-28

## Current workflow decision
- Use the existing 7-hex base as a single continuous canvas.
- Paint/design one continuous forest across all seven hexes first, prioritizing seamless vegetation, canopy, shadows, and ground continuity.
- Only after the full cluster is approved, crop/split into individual game hex tiles.
- Reassemble the seven cropped tiles in the game's hex layout and inspect seams before approval.

## Geometry reference (game CSS)
- Hex tile: 560 x 440 px at 10x scale
- Horizontal pitch: 420 px
- Vertical pitch: 440 px
- Odd columns offset vertically by 220 px
- Polygon: (140,0), (420,0), (560,220), (420,440), (140,440), (0,220)

## Current status
- Existing 7-hex base file: `field-map-masters/forest/forest-7hex-base.png`
- Individual tile concept images exist, but edge continuity is not approved.
- Center tile is the fixed reference; do not redraw or alter the center tile during edge-tile corrections.
- The prior north-edge tile concepts were judged not seamlessly connected to the center.

## Next task
1. Start from the 7-hex base and create a single continuous forest illustration over the full cluster.
2. Visually inspect the whole cluster before splitting.
3. Once approved, crop seven tiles at exact CSS-aligned geometry.
4. Seam-test reassembly; save only approved tiles with clear filenames.

## Approval rule
No tile or cluster is marked final until the user has visually checked it and the seam test passes.
