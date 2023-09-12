# Book Bot

Book Bot is a Python script designed to analyze and process text from books. It provides functionality for counting words and characters, as well as generating statistics on letter frequencies.

## Features

- **Word Count**: Analyze a book to determine the total number of words it contains.
- **Character Frequency**: Get a breakdown of how often each character appears in the text.
- **Case Insensitivity**: Convert all characters to lowercase to avoid duplicates in character counts.

## Getting Started

### Prerequisites

- Python 3.x

### Usage

1. Clone the repository or download the `main.py` file.
2. Run `main.py` in your preferred Python environment.
3. Follow the prompts to input the path to your book file.

## Examples

### Counting Words

```python
python main.py

Enter the path to your book file: books/frankenstein.txt

Total words in the book: 77986
```

### Character Frequency

```python
python main.py

Enter the path to your book file: books/frankenstein.txt

Character frequency:
{'a': 27343, 'b': 5056, 'c': 7652, ...}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments