# BeamerBuddy

A browser-based 3D planner for projection in galleries, theatres and outdoor sites.

- Christie and Barco projector and lens catalog, plus your own custom projectors and lenses
- Throw distance, zoom fitting, lens shift and content aspect
- Flat and curved screens (up to full 360°), risers, rear-projection screens
- Indoor gallery, theatre (proscenium, stage, apron, raked house, balcony), outdoor sloped site, or an imported SketchUp export (.dae / .obj / .stl / .glb)
- Brightness heatmaps in nits, foot-lamberts or lux, image-edge coverage view, blend overlap
- Shadow checks for audience members, performers and instruments
- X / Y / Z distance overlay, from the selected object or between all projectors, screens and risers
- Export to SketchUp as COLLADA (.dae): venue, screens, risers, projectors, beams and people as named groups,
  optionally with the brightness map painted on as textures. With an imported model, the export uses that
  model's own coordinates so it drops back into the original .skp in place
- WASD camera movement, lens view and eye-level view

## Running it

It is a single file. Open `index.html` in a modern browser, or publish the repository with GitHub Pages
(Settings → Pages → deploy from branch `main`, folder `/root`).

An internet connection is needed: three.js and fonts load from public CDNs.

## Notes

Plans, custom equipment and imported models are saved in the browser you use. Use **Save / load** and
**Catalog → My equipment → Import / export** to move them between browsers.

Throw ratios and lumen figures are planning estimates. Confirm lens choice and shift range with the
manufacturers' lens calculators before ordering.
