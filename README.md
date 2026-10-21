# BeamerBuddy

A browser-based 3D planner for projection in galleries, theatres and outdoor sites.

- Christie, Barco and BenQ projector and lens catalog (including BenQ short throw, ultra short throw and portable
  models with their built-in lens offsets), plus your own custom projectors and lenses
- Throw distance, zoom fitting, lens shift and content aspect
- Flat and curved screens: curved left to right (up to full 360°), top to bottom, or both ways as a dish;
  risers, rear-projection screens
- Indoor gallery, theatre (proscenium, stage, apron, raked house, balcony), outdoor sloped site, or an imported SketchUp export (.dae / .obj / .stl / .glb)
- Brightness heatmaps in nits, foot-lamberts or lux, image-edge coverage view, blend overlap
- Content preview: give each projector a JPG and see it projected on every surface, with falloff, overlap and
  shadows (images are kept in the browser, not in the plan code)
- Shadow checks for audience members, performers and instruments
- Floor-plan dimensions, like a drafting top view: distance square to each screen face, to the surrounding walls
  (not outdoors), and height above the floor. Projector measurements are taken from the center of the projector body
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
