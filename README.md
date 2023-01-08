# svelte-jsoneditor-standalone
Jos de Jong's new [svelte-jsoneditor](https://github.com/josdejong/svelte-jsoneditor) for `R` whose `htmlwidgets` generally require a classic standalone.  This project uses `esbuild` format immediately-invoked function expression (`IIFE`) to produce a standalone with global `JSONEditor` where `JSONEditor.JSONEditor` (yes ugly) offers the instantiation function.

Used primarily to experiment with updating the [listviewer](https://github.com/timelyportfolio/listviewer) widget with the new version of `jsoneditor`.
