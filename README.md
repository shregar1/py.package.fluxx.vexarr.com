# `fluxx`

Official Python SDK for the [Fluxx](https://fluxx.dev) control plane API.

Targets Python 3.10+.

## Install

```bash
pip install fluxx
```

## Quickstart

```python
from fluxx import Client

client = Client(api_key="flx_live_…")
# fleet = client.fleet.list()
```

> **Status:** scaffold. The client surface is being generated from
> `https://api.fluxx.dev/openapi.json`. Track progress in this repo's
> issues.

## Development

```bash
pip install -e ".[dev]"
pytest
```

## License

Apache-2.0
