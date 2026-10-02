# Helpful Git Aliases

Enhance your collaborative git workflow:

```ini
[alias]
    co = checkout
    br = branch
    ci = commit
    st = status
    pair = "!f() { git commit -m "$1

Co-authored-by: $2 <$3>"; }; f"
```
