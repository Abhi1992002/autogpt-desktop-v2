Evidence for Significant-Gravitas/AutoGPT#16511 (SECRT-3154, one colour token set).

- before/: dev e681d74, after/: the PR branch; same seeded database, production builds with NEXT_PUBLIC_PW_TEST=true,
  captured with autogpt_platform/frontend/scripts/screenshot-pages.ts at 1440x900 and 390x844.
- diff/: pixelmatch at threshold 0 (red = changed pixel). compare.md: changed pixels per shot.
- crops/: side-by-side before | after crops of each changed region.
- palette-swaps.txt: every palette class the codemod swapped (file:line old -> new), from a dry run over dev.

r2/: refreshed after merging dev 606cb1b (with #16513, the Text/Icon/Button variants) into the PR at 1ae437b.
before = dev 606cb1b, after = PR head 1ae437b; same database and capture settings as above.
