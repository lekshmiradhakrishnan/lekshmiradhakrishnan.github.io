# lekshmi-radhakrishnan.github.io

Personal academic homepage. Plain HTML — no build step, no dependencies.

- `index.html` — the whole site
- `portrait.jpg` — headshot (800×911)
- `images/` — website photos (`name.jpg` full size for the enlarged view, `name-sm.jpg` for the page)
- `Lekshmi_Radhakrishnan_CV.pdf` — public CV shown on the CV tab

## To edit

Open `index.html` in any text editor. The content starts after the closing
`</style>` tag; everything above it is styling you can ignore.

**Travel maps (Elsewhere tab).** The shaded countries and states are the
`countries` and `states` lists in the `<script>` near the bottom of
`index.html`. To add a place, add its name to the list, spelled exactly as in
`maps.js` (search that file for `data-name="…"`; don't edit it otherwise). Places too small to draw on the world map, such as Singapore,
go in the `pins` list with their latitude and longitude. The counts on the map
buttons update by themselves.

## Things to add later

- ORCID iD, once registered at orcid.org — add a line to the Contact block
- Google Scholar profile, once the Journal of Comparative Neurology paper is out
- `cv.pdf` — drop the file in this folder, then change "Available on request"
  in the Contact block to `<a href="cv.pdf">Download (PDF)</a>`
