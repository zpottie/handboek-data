# Handboek Data

A public repository containing Afrikaans-English vocabulary data, designed to support language learning applications. This repository provides a structured JSON dataset of Afrikaans words with their English translations, definitions, and example sentences.

## Data Structure

The data is stored in JSON format with the following structure:

```json
{
  "metadata": {
    "languagePair": "af-en_gb",
    "version": "1.0.1",
    "lastUpdated": "YYYY-MM-DD",
    "idFormat": "uuid-v6"
  },
  "words": [
    {
      "id": "1ee5c1c0-5c1c-6c1c-8c1c-1ee5c1c0c1c0",
      "afrikaans": {
        "word": "word",
        "definition": "definition in Afrikaans",
        "example": "example sentence in Afrikaans"
      },
      "english": {
        "word": "word",
        "definition": "definition in English",
        "example": "example sentence in English"
      }
    }
  ]
}
```

### ID Format

Word entries use UUID v6 format for their identifiers. This format provides:
- Time-ordered UUIDs (based on timestamp)
- Guaranteed uniqueness
- Sortable by creation time
- Compatible with distributed systems

## Usage

This data is freely available for use in language learning applications, educational tools, or any other project that helps people learn Afrikaans. The data is licensed under the MIT License.

## Contributing

We welcome contributions to expand the vocabulary database! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 
