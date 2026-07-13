# Materna — Interview Portfolio (GitHub Pages)

This folder hosts a static single-page portfolio for explaining the Materna project during interviews (~7 minutes).

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main presentation page |
| `styles.css` | Theme and layout |
| `assets/demo.mp4` | App walkthrough video |
| `assets/home.jpeg` | Home screen screenshot |
| `assets/analytics.jpeg` | Health analytics screenshot |
| `assets/architecture-ref.jpeg` | Early design reference (not primary architecture) |

## Preview locally

Open `index.html` in a browser, or serve the folder:

```bash
cd docs
python -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080).

## Publish on GitHub Pages

1. Push this repo to GitHub (include the `docs/` folder and `assets/`).
2. Go to **Repository → Settings → Pages**.
3. Under **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or your default branch)
   - **Folder:** `/docs`
4. Save. After a minute or two, the site will be live at:

   `https://<your-username>.github.io/Materna/`

## Interview flow

Use the top navigation (or keys **1–7**) to walk through:

1. Hero — purpose and stack  
2. Objective — problem, solution, stakeholders  
3. Architecture — real system diagram  
4. Features — capability grid  
5. Workflows — tabbed user journeys  
6. Demo — embedded video + screenshots  
7. Challenges — issues and fixes  
8. Analytics — cost optimization and sample metrics  

## Note on video size

`demo.mp4` is ~36 MB. GitHub allows files up to 100 MB. For faster loads, consider compressing the video before pushing.
