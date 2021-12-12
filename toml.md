# Toml functions

## Read a Toml file
```python
import toml

def read_toml(filename: str) -> list:
    """Reads a toml file and returns a list or dict."""
    if '.toml' not in filename:
        filename += '.toml'
    data = toml.load(filename)
    return data
```


