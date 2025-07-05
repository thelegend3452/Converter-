Description:

This is a simple Python-based GUI tool** for converting image formats and resizing images using the **Pillow (PIL) library. It allows you to:

* Convert images between `.png` and `.jpg`
* Resize images while preserving the original format

Requirements:

* Python 3.x
* [Pillow](https://pillow.readthedocs.io/en/stable/) (`pip install pillow`)
* Tkinter (comes built-in with Python for most systems)

Features:

1. Select an image file via a file dialog
2. Convert the image to PNG or JPG
3. Resize the image while keeping the original format and extension

---

How to Use:

1. Run the script:

   ```bash
   python your_script_name.py
   ```

2. A file dialog will appear — select an image file (e.g., `.jpg`, `.png`).

3. Choose an option:

   * `1` to convert the image format

     * Then choose `.png` or `.jpg`
     * Enter a new name (without extension)
     * The image will be saved in your Downloads folder
   * `2` to resize the image

     * Enter width and height in pixels
     * Enter a new name (without extension)
     * The resized image will be saved in your Downloads folder using the same format as the original


Notes:

* The script uses `Tkinter` to open a file dialog. No need to type file paths manually.
* Only `.png` and `.jpg` formats are currently supported.
* When resizing, the script retains the original file format.

