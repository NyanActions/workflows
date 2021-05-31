Only works on `ubuntu`

cloudflared updates automatically

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
           # sudo cloudflared update
          args: update
```
