# cloak-actions
GitHub Actions for Cloak projects

## Usage

Add the following to a step:

```
jobs:
  job_name:
    runs-on: ubuntu-latest
    steps:
      - uses: bkwld/cloak-actions/install@v2
        # The following is optional
        with:
          cwd: packages/ugc-housekeeper
```
