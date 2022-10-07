# expr-solver

A boolean-expression solver implemented in NodeJS.

### Usage

---

Solve the expression `!a&b&c`
```bash
node . --expression  "!a&b&c"
```

Solve the expression `(a & !b) | (!a & b)` and show the parser output.
```bash
node . --expression "(a & !b) | (!a & b)" --show-ast
```

The variable's values resulting in positive outputs are highlighted on the
truth table (positive values in green, negative in red).