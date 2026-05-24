## Image Steganography using Python 🔐

**Tools:** Python, OpenCV, NumPy, Pillow, Matplotlib

### What it does:
- Hides secret text messages inside images
- Extracts hidden messages from encoded images
- Uses LSB (Least Significant Bit) technique
- Images look identical before and after encoding

### How it works:
1. Convert secret message to binary
2. Replace the least significant bit of each pixel
3. Image looks unchanged to the human eye
4. Decoder extracts the hidden binary and converts back to text

### Key Concepts:
- LSB Steganography
- Image Processing with OpenCV
- Binary encoding/decoding
- Data Security & Privacy
