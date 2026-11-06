# Study preview deployment

Synthetic-data testing only. Not approved for live participant collection.

This preview builds the refreshed study UI from CurentLeaf/adaptive-visualization-recommender, study branch, pinned to commit 4154d203393bd05f2482e2aabe4cc859b904e9a3 (UI revision rehearsal-2026.11.06.1).

Open https://curentleaf.github.io/visualization-recommender-study-preview/ after the Publish study preview workflow succeeds. The standalone pilot includes guided progress, refreshed onboarding, evidence/response navigation, and accessible response controls. Full reVISit hosting and live participant collection are not enabled.

The workflow installs dependencies, type checks, runs study and analysis tests, builds with the preview repository base path, and deploys GitHub Pages. The source snapshot is pinned; later study-branch changes require updating the workflow ref. No changes are made to the original repository or its main website.
