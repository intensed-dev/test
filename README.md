# Rebase Test

The GitHub Pages site is authored from .rebase components and compiled during the Pages workflow.

It demonstrates:
- Vue-style script/template/style sections
- .rebase component imports and reuse
- {variable} interpolation
- {#if}, {:elif}, {:else}
- {#each}
- state(), computed(), effect(), watch()
- on:click
- component-local styles
- compiler output and the Rebase runtime

The Pages workflow checks out intensed-dev/code at feat/rebase-complete, compiles the .rebase sources, and deploys the generated dist/ directory.
