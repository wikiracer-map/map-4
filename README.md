# Wikiracer map, part 4 of 4

The link map behind [Wikiracer](https://wikiracer.kieronoates.workers.dev/). Built from the English Wikipedia dump of 1 October 2026.

This repo only serves files for the site's shortest-route search, which reads them in small pieces with HTTP Range requests. The code that builds them lives in the [wikiracer](https://github.com/roff-dev/wikiracer) repo, under `pipeline/`.

Each version sits in its own folder (`v20261001/`) and replaces the previous one when I refresh the map.
