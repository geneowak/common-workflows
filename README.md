# Common Workflows

This repository contains a collection of common github workflows that I've found reusable across multiple projects. The goal is to define all of them here and reuse them in the various projects without having to recreate them all the time.

### Example

```yaml
#...
jobs:
  build_and_test:
    uses: geneowak/common-workflows/.github/workflows/laravel-build-and-test.yml@main
#...
```
