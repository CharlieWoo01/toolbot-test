# toolbot-test

A test repository for [Toolbot](https://github.com/CharlieWoo01/toolbot). The *Toolbot* workflow opens a pull request whenever one of these tools has a new release:

| Tool | What Toolbot updates |
| --- | --- |
| `tools/pact-cli` | Release assets from GitHub (small files, plain git) |
| `tools/helm` | Binary extracted from the tar.gz/zip on get.helm.sh; ~60 MB, so stored with Git LFS |
| `tools/terraform-pin` | Only the version in `.terraform-version` (no binary) |

Run it: *Actions → Toolbot → Run workflow* (tick *dry-run* to only report).
