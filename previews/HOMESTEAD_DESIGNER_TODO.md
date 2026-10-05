# Permaculture Homestead Designer — Core UX Fix List

## Priority 1 — Make the canvas trustworthy
- [x] 1. Boundary and zone overlays no longer block placing objects inside them.
- [x] 2. Added separate Survey / Design modes with Existing vs Planned phases.
- [x] 3. Added autosave + restore. Project geometry/settings use local storage; large drone images use IndexedDB.
- [x] 4. Added zoom, mouse-wheel zoom, pan, reset/fit controls.

## Priority 2 — Make geometry genuinely editable
- [x] 5. Added real dimension controls for trees/buildings plus building rotation.
- [x] 6. Gardens, ponds, zones and boundaries use custom polygons; paths use lines.
- [x] 7. Replaced double-click finishing with explicit Finish / Cancel drawing controls.
- [x] 8. Added draggable polygon/line vertex handles.
- [x] 9. Mobile inspector now becomes a bottom sheet instead of disappearing.

## Priority 3 — Clean up the experience
- [x] 10. Timeline simplified to phase visibility rather than pretending to simulate full biology.
- [x] 11. Calibration now shows a visible measurement line, value and confirmation.
- [x] 12. Added base-image opacity, rotation safeguards, fit/reset and lock controls.
- [x] 13. Removed the placeholder object/water/garden counters and "Later intelligence" roadmap panel; replaced them with useful project counts and contextual editing.
- [ ] 14. Full live first-time workflow regression test on desktop + mobile.

## Target workflow
1. Upload or open land image.
2. Calibrate scale.
3. Survey existing land.
4. Trace boundary and existing features.
5. Switch to Design mode.
6. Add future systems with editable real geometry.
7. Save automatically.
8. Review by phase / year.

## Next test pass
- Upload a real drone image.
- Calibrate against a known real-world dimension.
- Trace boundary.
- Add existing house/trees/access.
- Switch to Design mode.
- Draw garden, pond, zone and path inside the boundary.
- Edit polygon vertices.
- Resize/rotate building.
- Refresh browser and confirm project + image restore.
- Test zoom/pan and timeline.
- Repeat on a phone-width viewport.
