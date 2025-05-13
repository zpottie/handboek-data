# Contributing to Handboek Data

Thank you for your interest in contributing to the Handboek Data repository! This document provides guidelines and instructions for contributing new vocabulary entries.

## How to Contribute

### Adding New Words

1. Fork the repository
2. Create a new branch for your changes
3. Add new words to the appropriate JSON file (currently `af-en_uk.json`)
4. Follow the existing data structure:
   - Each word must have a unique UUID v6 identifier
   - Include both Afrikaans and English versions
   - Provide clear definitions and natural example sentences
   - Ensure proper formatting and JSON syntax

### Word Entry Format

```json
{
  "id": "1ee5c1c0-5c1c-6c1c-8c1c-1ee5c1c0c1c0",  // UUID v6 format
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
```

### Generating UUIDs

When adding new words, you'll need to generate a UUID v6 for each entry. You can use various tools to generate these:

1. Online UUID generators (make sure they support UUID v6)
2. Programming language libraries:
   - Python: `uuid6` package
   - JavaScript: `uuid` package with v6 support
   - Other languages: Check for UUID v6 support in your preferred language

### Guidelines for Entries

1. **Definitions**: 
   - Keep definitions clear and concise
   - Use simple language that learners can understand
   - Include common usage contexts

2. **Example Sentences**:
   - Use natural, everyday language
   - Keep sentences relatively simple
   - Ensure examples demonstrate the word's meaning clearly

3. **Quality Checks**:
   - Verify spelling and grammar in both languages
   - Ensure translations are accurate
   - Check that the JSON is properly formatted
   - Validate that the UUID is in the correct v6 format

### Submitting Changes

1. Commit your changes with a clear commit message
2. Push to your fork
3. Create a pull request
4. Wait for review and feedback

## Code of Conduct

Please be respectful and constructive in all interactions. We aim to maintain a welcoming and inclusive environment for all contributors.

## Questions?

If you have any questions about contributing, please open an issue in the repository. 