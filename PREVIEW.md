# Study preview deployment

Synthetic-data testing only. Not approved for live participant collection.

This repository builds source snapshot 7c77f1b58929cbb29a693529de99ad9331d6160d from the study branch in CurentLeaf/adaptive-visualization-recommender. It does not merge that branch or change the original repository or website.

The preview runs the standalone pilot app. Full reVISit host integration and institution-approved participant collection are not enabled by this deployment.

Enable Settings > Pages > Build and deployment > Source: GitHub Actions in this preview repository. Inspect Actions > Publish study preview. Type checking, study tests, analysis tests, and build must pass before deployment. The deployment job reports the actual site URL.

The source snapshot is pinned; subsequent study-branch changes require a reviewed snapshot update. The workflow does not patch source files or disable checks. Do not enter sensitive data or recruit participants through this preview.
