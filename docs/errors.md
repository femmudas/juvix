### `Nonexhaustive patterns in function` error

**What it means:**

This error occurs when a function does not handle all possible input cases (patterns). Juvix expects your functions to cover every possible scenario. If you miss one, the compiler will give you this error.

**Solution:**

When using a `case` statement or pattern matching, ensure all possible cases are defined. If needed, you can use the `_` (underscore) character to catch all remaining cases.

**Example:**
When checking a `boolean` value, you should handle both the `true` and `false` cases.
