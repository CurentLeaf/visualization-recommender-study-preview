# Study preview deployment

Synthetic-data testing only. Not approved for live participant collection.

This preview builds the refreshed study UI from CurentLeaf/adaptive-visualization-recommender, study branch, pinned to commit d717e1196f95b238251af8eba81ec20996b995be (UI revision rehearsal-2026.11.06.2).

Open https://curentleaf.github.io/visualization-recommender-study-preview/ after the Publish study preview workflow succeeds. The standalone pilot uses an open content-first layout, thin section rules, plain radio choices, guided progress, and accessible evidence/response navigation. Full reVISit hosting and live participant collection are not enabled.

The workflow installs dependencies, type checks, runs study and analysis tests, builds with the preview repository base path, and deploys GitHub Pages. The source snapshot is pinned; later study-branch changes require updating the workflow ref. No changes are made to the original repository or its main website.
