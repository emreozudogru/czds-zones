# czds-zones

A repository of zone data files exported from CZDS, with one `.txt` file per top-level domain (TLD).

## Contents

- `*.txt` files: Zone-related data grouped by TLD name.
- `LICENSE`: MIT license for this repository.

## Usage

You can inspect any specific TLD file directly, for example:

```bash
head -n 20 com.txt
```

Or search across all zone files:

```bash
rg "example-pattern" *.txt
```

## Notes

- File names generally map to TLD labels.
- Internationalized domain labels are represented in punycode where applicable.
