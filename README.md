# I ❤️ Xcode
My own Xcode templates and snippets

# To add a new local entry and push to remote
- add the snippet/template normally with Xcode
- from terminal `cd code-snippets`
- run `./show-diff` to check what is missing. The command uses `ksdiff` so that utility must be installed
- run `./sync-from-xcode` to copy those entries in the Xcode folder which are missing in the local git repo

