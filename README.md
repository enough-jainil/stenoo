# Stenoo :loop:


## Ultimate Steganography Software :superhero:

Stenoo is the do-all steganography application, designed to hide your messages rather than just encrypting them. :grin:

**Formats Supported:**

- Images
- Audio
- Text
- ~~Video~~ _To be supported in future versions_

> In today's world, hiding messages is as crucial as encrypting them. Stenoo provides a comprehensive solution for your steganography needs.

## Features

- Hide your private messages in images, audio & text files.
- Password protection for enhanced security.
- Forgot password recovery feature.
- User-friendly interface with helpful tooltips.
- Cross-platform compatibility (Windows, macOS, Linux).


## Installation

```bash
# Your global Python installation needs to have pipenv
pip install pipenv

# Clone the repo
git clone https://github.com/enough-jainil/stenoo.git

# Change directories into the project
cd stenoo

# Install dependencies
pipenv install

# Activate the Pipenv shell
pipenv shell

# Start the program
python main.py
```

## Usage

1. Launch the application by running `python main.py`
2. Choose the type of steganography (Text, Image, or Audio) from the main menu.
3. For encoding:
   - Select the carrier file
   - Enter the message or select a file to hide
   - Set a password
   - Choose the output location
   - Click "Encode" or "Embed"
4. For decoding:
   - Select the steganographic file
   - Enter the password
   - Click "Decode" or "Extract"

For detailed usage instructions, please refer to the [User Manual](docs/USER_MANUAL.md).

## Development

For those interested in contributing to Stenoo:

```bash
# Install dev dependencies
pipenv install --dev

# Run tests
pytest

# Check code style
flake8
```

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## Roadmap

- [ ] Implement video steganography support
- [ ] Enhance encryption for improved data security
- [ ] Develop web and mobile versions
- [ ] Implement advanced steganography techniques

## Why Steganography?

Steganography is not just about hiding data; it's about hiding the very existence of the data. While encryption makes data unreadable, steganography makes it invisible.

Example:
- Encrypted: `Qcaapgrw gq gknmprylr` (Easily detectable as encrypted)
- Steganographic: Your message is hidden within an ordinary-looking file, leaving no trace of its existence.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [SNOW](http://www.darkside.com.au/snow/) for text steganography
- OpenCV community for image processing capabilities
- All contributors who have helped shape Stenoo

---

Remember: Stenoo is a tool for privacy, not secrecy. Use responsibly and ethically.
