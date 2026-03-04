# Profile Photo Setup Instructions

## Adding Your Profile Photo

To add your professional profile photo to the website:

### Option 1: Replace the Placeholder

1. **Find or take a professional headshot photo**
   - Square format recommended (1:1 aspect ratio)
   - Minimum 500x500 pixels
   - Professional attire
   - Clean background
   - Good lighting

2. **Rename your photo to `profile.jpg`** (or `profile.png`)

3. **Copy to the assets folder:**
   ```bash
   cp /path/to/your/photo.jpg assets/images/profile/profile.jpg
   ```

### Option 2: Use Existing Photo from SGC

If you have a `Pradeep_Profile.jpg` file from your old website:

```bash
# Find the file
find SGC -name "*Profile*.jpg" -o -name "*profile*.jpg"

# Copy it
cp /path/to/Pradeep_Profile.jpg assets/images/profile/profile.jpg
```

### Current Status

- ✅ Profile photo placeholder is set up in hero section
- ✅ Fallback icon displays if image is not found
- ✅ Image path: `assets/images/profile/profile.jpg`
- ⏳ **ACTION NEEDED:** Add your actual profile photo

### Verification

After adding your photo, verify it displays correctly:

1. Open `index.html` in a browser
2. Check the hero section (top of homepage)
3. Your photo should appear in a circular frame
4. If you see an icon instead, check the file path

### Tips

- **Format:** JPG or PNG (JPG preferred for file size)
- **Size:** Keep under 500KB for fast loading
- **Dimensions:** 800x800 pixels ideal (will be scaled)
- **Background:** Professional or neutral color
- **Expression:** Friendly, professional smile

---

## Award Certificates

### Currently Added

✅ **Globee Awards 2025**
- File: `assets/images/awards/Globee_Awards_2025.png`
- Status: Successfully added and displayed on all-awards.html

### To Add More Certificates

You can add more award certificates by copying them to:

```bash
cp "SGC/Awards/TITAN Business Awards Winner Certificate - e-certificate.pdf" assets/images/awards/

# Convert PDF to image if needed (using online tool or command):
# Then save as: assets/images/awards/titan-awards.png
```

Then update `all-awards.html` to use the actual certificate images instead of placeholders.

---

## Image Optimization Tips

For best website performance:

1. **Compress images** before uploading
   - Use tools like TinyPNG, ImageOptim, or online compressors
   - Target: < 500KB per image

2. **Use appropriate formats:**
   - Photos: JPG
   - Graphics/logos: PNG
   - Simple graphics: SVG (if available)

3. **Responsive images:**
   - Current setup automatically scales images
   - No additional work needed

---

## Next Steps

1. [ ] Add your profile photo to `assets/images/profile/`
2. [ ] (Optional) Convert PDF certificates to images
3. [ ] (Optional) Add more award certificate images
4. [ ] Test the website after adding images
5. [ ] Commit and push changes to GitHub

```bash
git add assets/images/
git commit -m "Add profile photo and award certificates"
git push origin main
```