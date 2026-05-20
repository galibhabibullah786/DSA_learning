# Time & Space Complexity

**Space complexity** = Auxiliary-space + Input-space

```cpp
cin >> a >> b; // Input-space; O(2)
int c = a + b; // Auxiliary-space; int c; O(1)
```

**NOTE:** Never modify inputs to save space. Always preserve those.

```cpp
cin >> a >> b;
b = a + b; // ❌❌
```
