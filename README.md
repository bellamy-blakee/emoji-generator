# Emoji Generator

This repository contains a Python package for working with smiley objects. The package includes two functions, `get_random_smileys` and `get_random_smileys_by_category`, which return a list of random smiley objects from a pre-defined list.

## Installation

You can install the package using pip:

```bash
pip install emoji-generator
```

## Usage

Import the package and use the functions to generate random smileys:

```python
import emoji_generator

# Get 5 random smileys
smileys = emoji_generator.get_random_smileys(5)
print(smileys)

# Get 3 random smileys with the category "Animals & Nature"
animals = emoji_generator.get_random_smileys_by_category("Animals & Nature", 3)
print(animals)
```

## Links

- [Random Emoji Generator](https://randomgenerate.io/random-emoji-generator)
- [RandomGenerate.io](https://randomgenerate.io/)
