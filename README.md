# Eqela Build Action

A GitHub action that let's you automate compiling your sling applications.

## Usage Example

```yaml
name: Build and test sling app
on: push
jobs:
  build:
    runs-on: ubuntu-latest    
    steps:
      - name: Eqela Build Action
        uses: ortegarenzy/eqela-build-action@v1.0
```

