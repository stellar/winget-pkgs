# winget-pkgs

This is a synced fork of https://github.com/microsoft/winget-pkgs.

Check [.github/workflows/sync.yml](https://github.com/stellar/winget-pkgs) for
details. The [master](https://github.com/stellar/winget-pkgs/tree/master) is the
main branch.

## Make a new release

1. Run the workflow `prepare` with the release version (e.g. 20.6.0)
2. After the run is finished, manually create a pull request against the
   Microsoft's `master` branch.
