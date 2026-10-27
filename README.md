# MeshLive website

Source of [meshlive.github.io](https://meshlive.github.io): the home page with the status of every MeshLive app, the [privacy policy](https://meshlive.github.io/privacy/) (used as the app's privacy policy URL) and the [child safety standards](https://meshlive.github.io/child-safety/). Contact: meshlive.dev@gmail.com.

Plain Jekyll served by GitHub Pages, with no theme and no JavaScript: `_layouts/` (page frames), `assets/site.css` (functional minimal dark style) and the pages `index.html`, `privacy.md`, `child-safety.md`, `404.html`. To preview locally, run `bundle exec jekyll serve` with the `github-pages` gem.

Keep the platform table on the home page consistent with the repository READMEs and the [organisation profile](https://github.com/MeshLive/.github/blob/main/profile/README.md). Do not change the privacy policy or the child safety page without checking them against what the apps actually do: they are the store-facing policy documents. The `/privacy/` and `/child-safety/` addresses must keep working.

Apps: [Android](https://github.com/MeshLive/meshlive-android), [Windows](https://github.com/MeshLive/meshlive-windows), [iPhone and Mac](https://github.com/MeshLive/meshlive-apple). Results: [meshlive-benchmarks](https://github.com/MeshLive/meshlive-benchmarks).
