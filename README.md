# OPUS Language Codes

This repository contains a comprehensive table of language codes used in the [OPUS project](https://opus.nlpl.eu/). The table includes a mix of ISO standards (e.g., ISO 639-1, ISO 639-3) and custom codes, reflecting the diverse and sometimes chaotic nature of the language identifiers in OPUS datasets.

## About the Table

The language codes and names were collected using Python and Selenium to scrape the OPUS results table available at:
[https://opus.nlpl.eu/results/en&xx/corpus-result-table](https://opus.nlpl.eu/results/en&xx/corpus-result-table)  
The `xx` part of the URL was iteratively replaced to extract data for different languages.

I tried using APIs and other standard methods to retrieve the data, but it didn't work. If anyone knows the right way to do it, please let me know!

### Challenges

One notable challenge during this project was the inconsistent and non-standard use of language codes in OPUS. The mix of ISO-compliant, regional, and custom codes made mapping and organization difficult but rewarding for understanding the breadth of multilingual data in OPUS.

### File Structure

- **`language_codes.csv`**: The primary file, containing:
  - `Code`: The language code used in OPUS.
  - `Language Name`: The corresponding language name.

### How to Use

1. Clone this repository:
```bash
   git clone https://github.com/hiroshima-pot/opus-language-codes.git
```

2. Use the `language_codes.csv` file in your projects for reference or mapping.

### Contributions

If you notice missing or incorrect codes, feel free to open an issue or submit a pull request.

### License

This project is licensed under the [MIT License](LICENSE).
