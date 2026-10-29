# fotohmbaku.com

Personal website of Fotoh Mbaku. A single static page: `index.html` with `headshot.jpg`, no build step.

## Editing experience

Work history lives in the `jobs` array in the `<script>` at the bottom of `index.html`. Each entry has the company, employment type, an optional description, a list of roles (`start`/`end` as `YYYY-MM`, `end: null` for current roles) and skill tags. Update `NOW` in the same script when durations should roll forward.

## Running locally

Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.
