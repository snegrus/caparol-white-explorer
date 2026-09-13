# Caparol White Explorer

An interactive, local-first explorer for comparing near-white and natural shades from Caparol's 3D-System PLUS palette.

## Run locally

From this folder, run:

```sh
python3 -m http.server 4173
```

Then open <http://127.0.0.1:4173/>.

The shortlist and its order are saved in the browser's local storage. Adding, removing, or reordering shades also updates the `compare` URL parameter, so a comparison can be shared as a link.

## Publish with GitHub Pages

1. Create an empty public repository on GitHub named `caparol-white-explorer`.
2. Add that repository as this project's `origin` remote and push the `main` branch.
3. In the GitHub repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.

The site will be available at:

`https://YOUR-USERNAME.github.io/caparol-white-explorer/`
