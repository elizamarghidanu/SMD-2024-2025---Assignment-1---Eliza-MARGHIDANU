### Solution:
I used `radare2` to disassemble the binary and discovered the function that returns the flag.

```bash
# Use radare2 to disassemble the binary and search for the function
radare2 -A app_binary

# Search for the flag function
/ flag
```
### Flag Found:
flag-BD570736-D304-400A-A6B7-F61B02173428
