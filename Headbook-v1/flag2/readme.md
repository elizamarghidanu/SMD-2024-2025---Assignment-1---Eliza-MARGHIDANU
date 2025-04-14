The app contained an Assets.car file, which may contain hidden flags in the images.
### Solution:
I opened the Assets.car file using Asset Catalog Tinkerer. I extracted the images with acextract and found the flag embedded in one of the images.

```bash
# Use Asset Catalog Tinkerer to open the Assets.car file
assetutil -i Assets.car

# Use acextract to extract the images
chmod +x acextract2
mkdir out
./acextract2 -i Assets.car -o out

# Check the extracted images
ls out/
```
### Flag Found:

flag-3a658cfd-4b65-433d-9e94-83dbdc60b49d
