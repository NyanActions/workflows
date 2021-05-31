Only works on `ubuntu`

## Example
```yaml
name: cloudflared 
on: push

jobs:
  cloudflared:
    runs-on: ubuntu-latest
    steps:
      - uses: kspactions/workflows/cloudflared@main
        with:
          args: update
```
