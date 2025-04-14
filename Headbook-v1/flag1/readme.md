### **Challenge**: The login page did not contain any visible login buttons or fields.

### **Solution**:
- I used **Passionfruit** to interact with the app's internal files.
- I explored the app's bundle and found the flag inside the `Info.plist` file.

```bash
# Use Passionfruit to explore the app's internal files
passionfruit -p 31337

# Open the Info.plist file to find the flag
cat Info.plist | grep flag
```
### Flag Found:
flag-EC840814-CEBA-4731-8620-CB991D850B14
