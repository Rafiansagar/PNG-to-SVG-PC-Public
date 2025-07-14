# PNG to SVG Converter

A simple `.exe` tool to **convert `.png` files to `.svg` vector files** using **Potrace**.  
It also creates intermediate `.bmp` files automatically.  

---

## ⚙️ Requirements

- `potrace.exe` & `mkbitmap.exe` must be copied inside:  
`C:\WINDOWS\`

- No need to install Python on the target PC. This `.exe` is standalone.

---

## 📥 How to Use

1. Copy `png-to-svg.exe` to the folder where your `.png` files are located.
2. Double-click `png-to-svg.exe`.
3. The tool will:
    - Convert all `.png` files in the current folder to `.svg`.
    - Create a `converted/` folder.
    - Place:
      - All `.svg` files into `converted/`
      - All `.bmp` files into `converted/bmp/`

---

## 📂 Output Structure

```
/your-folder
    /converted
        /bmp
            your-image.bmp
        your-image.svg
    your-image.png
    png-to-svg.exe
```

---

## 📝 Notes

✅ Only `.png` files in the current folder will be processed.  
✅ `.svg` files are generated.  
✅ `.bmp` intermediate files are saved for reference.

---

## 🎉 Done!
Just run it and your `.svg` files will be ready.
