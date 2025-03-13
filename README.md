# 256colors

## About
`256colors` is a Bash script that demonstrates ANSI escape sequences for 256 colors. It dynamically adjusts the display to fit the terminal width and provides various text styles based on user input.

### Features:
- Displays a table of 256 ANSI colors.
- Supports different text formatting styles such as **bold**, *dim*, _italic_, underlined, blinking, inverted, hidden, and strikethrough.
- Adapts to the terminal width to prevent text wrapping or truncation.

![screenshot](/img1.jpg)

## Installation
```sh
# Clone the repository
git clone https://github.com/BuriXon-code/256colors

# Navigate to the directory
cd 256colors

# Give execution permission
chmod +x 256colors
```

## Usage
Run the script without parameters to display the standard color table:
```sh
./256colors
```

Use a parameter to change text formatting:
```sh
./256colors [mode]
```

![screenshot](/img2.jpg)

### Available Modes:
- `0` or no parameter: Standard color table
- `1`: Bold
- `2`: Dim
- `3`: Italic
- `4`: Underline
- `5` or `6`: Blinking
- `7`: Inverted (text/background swap)
- `8`: Hidden
- `9`: Strikethrough

Example:
```sh
./256colors 4  # Displays underlined color codes
```
```sh
./256colors 1 2 3  # Displays 1, 2 and 3 styles one-by-one
```

## Support

### Contact me:
For any issues, suggestions, or questions, reach out via:

- **Email:** support@burixon.com.pl  
- **Contact form:** [Click here](https://burixon.com.pl/kontakt.php)

### Support me:
If you find this script useful, consider supporting my work by making a donation:

[**DONATE HERE**](https://burixon.com.pl/donate/)

Your contributions help in developing new projects and improving existing tools!

