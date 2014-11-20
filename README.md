# jsondiff

## Usage

Clone the repo, add `jsondiff` to your path and run

```bash
jsondiff <reference.json> <comparison.json> [ignored_keys]
```

e.g.

```bash
jsondiff resources/a.json resources/b.json zz,c.g.h
```

This will use a.json as the reference file, compare b.json to it and output any differences (ignoring the keys "zz" and "c.g.h")


jsondiff expects one piece of JSON per line.
