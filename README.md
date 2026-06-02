# Heat Resilience Decision Engine Prototype

This is a GitHub Pages-ready prototype. It runs fully in the browser using HTML, CSS, and JavaScript.

You can:

- add a ward or neighbourhood
- test heat-risk scores
- load sample data
- delete wards
- export CSV
- import CSV
- generate a ward decision brief
- generate a top-3 city decision brief

## How to host on GitHub Pages

1. Create a new public GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**.
6. Click **Save**.
7. Wait a few minutes.

Your live site will be:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/`

## Important note

The tool is static, but interactive. It saves entered ward data in the user's browser using localStorage. It does not save to a shared database. Use **Export CSV** if you want to keep or share data.

## Method

The prototype calculates a risk score out of 100 using:

- heat exposure: 30%
- population density: 15%
- informal or low-income housing: 15%
- shade deficit: 15%
- health access gap: 10%
- outdoor worker exposure: 15%

This is an early decision-support prototype, not a final scientific model.
