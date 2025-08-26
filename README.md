# Number to Words Image Generator

This Python program converts numbers into words and creates a visual representation.

## Features

- Converts numbers (0-999,999) to written words
- Creates an HTML file with the text displayed as an image alternative
- Clean, professional styling
- Error handling for invalid inputs

## Usage

Run the program:
```bash
python number_converter.py
```

Enter a number when prompted, and the program will:
1. Convert the number to words
2. Display the conversion in the terminal
3. Create an HTML file with the text beautifully formatted

## Examples

- Input: `32` → Output: "Thirty Two"
- Input: `1234` → Output: "One Thousand Two Hundred Thirty Four"
- Input: `0` → Output: "Zero"

## Limitations

Due to WebContainer environment constraints:
- No external libraries (num2words, PIL) available
- HTML alternative provided instead of PNG/JPG image generation
- Number range limited to 0-999,999

## Complete Version

The `complete_version.py` file shows how this would work with external libraries:
- Uses `num2words` for more comprehensive number conversion
- Uses `PIL` (Pillow) for actual image generation
- Supports larger numbers and more languages

To use the complete version in a full Python environment:
```bash
pip install num2words pillow
python complete_version.py
```

## Files Generated

- `number_[NUMBER]_words.html` - Visual representation of the number in words