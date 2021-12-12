# Toml functions

## Read a Toml file
```
import toml

def function read_toml(filename: str) -> list:
    """Reads a toml file and returns a list or dict."""
    if '.toml' not in filename:
        filename += '.toml'

    ...
```
