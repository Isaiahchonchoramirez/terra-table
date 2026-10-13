# Terra Table source

Open this folder in VS Code.

- `dist/app.js`: globe, pins, regional menus, meal box
- `dist/style.css`: page styling
- `dist/index.html`: page structure
- `dist/assets/`: Earth textures, food photos, Three.js

To run locally, open a terminal in this folder and run:

```bash
python3 -m http.server 8000 --directory dist
```

Then visit http://localhost:8000. A local server is required for JavaScript modules.
