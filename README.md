# Reboot the Earth Vermont 2026

Public event site and planning resource for **Reboot the Earth Vermont**, a two-day student climate hackathon hosted by the University of Vermont in partnership with the [United Nations Office of Information and Communications Technology (OICT)](https://unite.un.org/en/reboot-earth).

**Event:** October 2026 · Burlington, Vermont
**Participants:** 100–300 students from UVM, Champlain College, St. Michael's College, and Middlebury College
**UN Contact:** Mithusa Kajendran — mithusa.kajendran@un.org
**UVM Lead:** Kendall Fortney — kendall.fortney@uvm.edu

---

## Site Structure

| File | Description |
|---|---|
| `index.html` | Public landing page — event overview, tracks, FAQ |
| `about.html` | Event background, UN partnership, key people, sponsorship |
| `teams.html` | Team composition, what to bring, Day 1 schedule, submission guide |
| `resources.html` | Data sources, APIs, tools, and inspiration for participants |
| `styles.css` | Shared stylesheet (all pages) |
| `img/` | Event and campus photography |
| `server.py` | Local development server |

## Running Locally

```bash
python server.py
```

Opens the site at `http://localhost:8000`. Pass a custom port with `python server.py 3000`.

## Deploying to GitHub Pages

1. Push to the `main` branch
2. Go to **Settings → Pages → Source** and set to `main` / `/ (root)`
3. Site publishes at `https://kfortney.github.io/Reboot-the-Earth/`

## Images

Campus photos go in `img/`. Current images:

| File | Usage |
|---|---|
| `campus-aerial.jpg` | Hero image on index.html |
| `waterman-hall.jpg` | Header image on about.html |

Additional suggested filenames: `campus-bikes.jpg`, `campus-ivy.jpg`, `campus-historic.jpg`, `campus-modern.jpg`, `campus-glass.jpg`, `campus-library.jpg`

## Branding Notes

All materials carrying the UN logo must be submitted to Mithusa Kajendran for approval before production. Allow a minimum two-week turnaround.
