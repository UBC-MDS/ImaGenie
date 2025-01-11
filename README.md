# ImaGenie

ImaGenie is a Python package designed to streamline and enhance image processing tasks. Whether you need to flip, scale, convert to grayscale, or blur images, ImaGenie is your one-stop solution for fast and efficient image manipulation.

## Features

- **Flip Images**: Horizontally or vertically flip your images.
- **Convert to Grayscale**: Transform colorful images into black-and-white simplicity.
- **Scale Images**: Resize your images to desired dimensions.
- **Blur Images**: Apply a blurring effect to smooth out details or reduce noise.
- **Batch Processing**: Apply operations to multiple images simultaneously.

## Installation

Install ImaGenie via pip:

```bash
pip install imagene
```

Alternatively, clone the repository and install directly:

```bash
git clone https://github.com/UBC-MDS/ImaGenie.git
cd ImaGenie
pip install .
```

## Usage

### Example 1: Flip an Image

```python
from imagene import flip

# Flip an image horizontally
flipped_image = flip(image, direction='horizontal')
```

### Example 2: Convert to Grayscale

```python
from imagene import grayscale

grayscale_image = grayscale(image)
```

### Example 3: Scale an Image

```python
from imagene import scale

# Resize the image to 200x200 pixels
scaled_image = scale(image, width=200, height=200)
```

### Example 4: Blur an Image

```python
from imagene import blur

# Apply a blur with a kernel size of 5
blurred_image = blur(image, kernel_size=5)
```

## Contributing

We welcome contributions to ImaGenie! If you would like to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push to your fork.
4. Submit a pull request to the `develop` branch.

## Development Workflow

### Setting Up the Environment

1. Clone the repository:
   ```bash
   git clone https://github.com/UBC-MDS/ImaGenie.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ImaGenie
   ```
3. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running Tests

Run tests to ensure everything is working:

```bash
pytest tests/
```

## License

ImaGenie is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, please open an issue on [GitHub](https://github.com/UBC-MDS/ImaGenie/issues).
