# hash-identifier

Identify what kind of hash a string is, by inspecting its shape.

## Usage

```bash
# Run directly
python3 hash_identifier.py <hash>

# After setup with uv + just
just run -- <hash>
```

## Examples

```bash
python3 hash_identifier.py 5f4dcc3b5aa765d61d8327deb882cf99
python3 hash_identifier.py '$2b$12$EixZaYVK1fsbw1ZfbX3OXe'
```

## Setup

```bash
just setup   # creates .venv and installs all dependencies
just test    # run the test suite
just lint    # run ruff + pylint + mypy
```

