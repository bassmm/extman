# extman - Python CLI Tool for Managing Extensions in VSCodium and Forks

`extman` is a Python-based command-line tool designed to help users manage extensions for VSCodium and its forks. With `extman`, you can install, uninstall, list, and update extensions easily, all through the terminal.

## Features

- **Install Extensions**: Install extensions from the marketplace or from local `.vsix` files.
- **Uninstall Extensions**: Remove installed extensions.
- **List Installed Extensions**: View currently installed extensions.
- **Update Extensions**: Update extensions to the latest versions.
- **Compatibility**: Works with VSCodium and its forks (e.g., Windsurf, Cursor).

## Installation

### Prerequisites

- Python 3.6 or later
- `uv` (Python project and package manager)

### Installing `extman`

You can install `extman` globally using `pip`:

```bash
pip install extman
```

Alternatively, you can install it from source:

```bash
# Clone the repository
git clone https://github.com/yourusername/extman.git

# Navigate to the project folder
cd extman

# Install dependencies
pip install -r requirements.txt

# Install `extman`
python setup.py install
```

## Usage

Once `extman` is installed, you can use it through the command line. Below are some common commands for managing your extensions.

### 1. Install an Extension

To install an extension from the marketplace, run:

```bash
extman install <extension-id> <version>
```

Example:

```bash
extman install ms-python.python 2025.3.2025031701
```

To install an extension from a local `.vsix` file:

```bash
extman install <path-to-file>.vsix
```

### 2. Uninstall an Extension

To uninstall an extension:

```bash
extman uninstall <extension-id>
```

Example:

```bash
extman uninstall ms-python.python
```

### 3. List Installed Extensions

To list all currently installed extensions:

```bash
extman list
```

This will display a list of installed extensions, their version numbers, and any relevant details.

### 4. Update Extensions

To update all installed extensions to their latest versions:

```bash
extman update
```

To update a specific extension:

```bash
extman update <extension-id>
```

Example:

```bash
extman update ms-python.python
```

## Contributing

Contributions are welcome! If you'd like to contribute to `extman`, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and ensure all tests pass.
4. Submit a pull request with a detailed description of your changes.

## License

`extman` is open-source software licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or feedback, please open an issue on the GitHub repository.

---

**Note**: `extman` is designed for use with VSCodium and its forks. For more information on VSCodium, visit [https://vscodium.com/](https://vscodium.com/).
```

Just copy and paste this into a new `README.md` file, and you'll have a fully formatted markdown document for your Python tool, `extman`.
