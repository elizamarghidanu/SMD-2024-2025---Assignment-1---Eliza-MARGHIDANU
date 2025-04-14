### Solution:
I used Passionfruit and the strings command to search through the app's binary for flag-related strings.

```bash
# Use Passionfruit to search for strings in the binary
passionfruit -p 31337 --strings

# Alternatively, use strings command to search binary files
strings app_binary | grep flag
```
### Flag Found:

flag-9861DA53-C08C-47C4-84D6-B48463AB738A
