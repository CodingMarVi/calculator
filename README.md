# Simple Calculator 🧮

A lightweight, responsive calculator application built with vanilla HTML, CSS, and JavaScript. Supports basic arithmetic operations with a clean, intuitive interface.

## Features

- ✨ Basic Operations: Addition, subtraction, multiplication, division, and modulo
- 🎨 **Responsive Design**: Works on all screen sizes and devices
- ⌨️ **Keyboard Support**: Use number keys and operators directly (optional via JavaScript)
- 🧹 **Clear Function**: Reset calculations with the clear button
- ⬅️ **Backspace**: Remove the last digit entered
- 💯 **Decimal Support**: Perform calculations with decimal numbers

## File Structure

```
CALCU/
  calcu.html    # Complete calculator application (HTML, CSS, and JavaScript)
```

## How to Run

### Method 1: Open Directly in Browser
1. Navigate to the `CALCU` folder
2. Double-click on `calcu.html` to open it in your default web browser
3. Start calculating!

### Method 2: Using a Local Server (Recommended)
For better performance and compatibility, use a simple HTTP server:

**With Python:**
```bash
# Python 3
python -m http.server 8000

# Or Python 2
python -m SimpleHTTPServer 8000
```

**With Node.js (using http-server):**
```bash
npx http-server
```

Then open `http://localhost:8000/CALCU/calcu.html` in your browser.

## How to Use

1. **Number Entry**: Click number buttons or use your keyboard (0-9)
2. **Decimal Point**: Click the `.` button to add decimal places
3. **Operations**: Click operation buttons (+, −, ×, ÷, %)
4. **Calculate**: Press the `=` button to see the result
5. **Clear**: Press `C` to reset the calculator
6. **Backspace**: Press `←` to remove the last digit

## Browser Compatibility

- Chrome/Edge ✅
- Firefox ✅
- Safari ✅
- Internet Explorer 11+ ⚠️ (limited support)

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `0-9` | Enter numbers |
| `+` | Addition |
| `-` | Subtraction |
| `*` | Multiplication |
| `/` | Division |
| `.` | Decimal point |
| `Enter` or `=` | Calculate result |
| `Backspace` | Delete last digit |
| `c` or `C` | Clear all |

## Technical Details

- **No Dependencies**: Pure JavaScript, no frameworks required
- **Single File**: All code contained in one HTML file
- **Accessible**: ARIA labels for screen readers
- **Lightweight**: Minimal CSS and JavaScript for fast loading

## License

Open source - Feel free to use and modify as needed.
