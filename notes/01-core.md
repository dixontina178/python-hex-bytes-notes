# Convert bytes to hexadecimal: implementation

## What the example does

Each integer must fit in one byte, from 0 through 255. Hex output uses two lowercase digits per byte including leading zeros.

The public function is `solve(value)`. The JSON input contract can be seen in this concrete example:

```json
[
  0,
  15,
  255
]
```

Expected result:

```json
"000fff"
```

Run `python3 example.py` for the Python representation of the result. `solution.py` contains the full implementation and can also be imported by another script.

## Scope

The function implements exactly the behavior described above. It does not perform network or filesystem access. Python exceptions indicate unsupported input; the next lesson turns them into a command-line error response. Review the limitations before reusing it in an application.
