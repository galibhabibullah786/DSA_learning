In most modern programming languages, **non-primitive (complex)** data structures like array, class, object, struct, dictionary, list, set, map are typically passed by reference.

While **primitive** types like integers and booleans are usually copied (passed by value), larger structures share their memory address to save resources and allow direct modification.

## Why use pass-by-reference?

- Efficiency: It avoids the "costly" process of copying large amounts of data in memory.

- In-place Modification: It allows a function to update the original data structure directly, which is useful for operations like `swap()` or sorting.

- Returning Multiple Values: A function can "return" multiple results by modifying several variables passed to it by reference.