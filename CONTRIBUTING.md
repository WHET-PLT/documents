As far as git/github goes,

1. Use imperative present tense (e.g. fix, add, change) or descriptive present (e.g. fixes, adds, changes)
2. Don't end lines with a period. 
3. If you're fixing an issue add "fixes #xxx" where xxx is the issue number. 
4. If you're referencing an issue add "#xxx" where xxx is the issue number. 
5. Read [best practices](assets/VCS-best_practices.pdf) document, most of it applies (use branch-when-necessary, at the end)

also worth noting, 

1. setup gitignore so we dont get .DS_store, binaries, or other junk
2. COMMENT EVERYTHING
3. Commit often/atomically, but only push working/functioning changesets (see above, 5)
