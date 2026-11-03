# Study preview deployment

Synthetic-data testing only. Not approved for live participant collection.

This repository builds source snapshot cd5a0cba138a7a864790acfa9c63ed3886ae2936 from CurentLeaf/adaptive-visualization-recommender. It does not merge or change that repository or its website. The source study is work in progress; this preview is not a claim of completed reVISit integration or research validation.

Enable Settings > Pages > Build and deployment > Source: GitHub Actions in THIS repository. Then inspect Actions > Publish study preview. If necessary choose Run workflow after enabling Pages. Type checking, tests and build must pass before deployment. Read failing logs before retrying; never skip checks just to publish. The deployment job reports the actual site URL.

The source snapshot is pinned: subsequent changes to the study branch are not automatically published. Updating the snapshot requires a reviewed workflow change. Do not enter sensitive data or use this preview for participant recruitment.
