# AI Code Documentation Generator

## Overview
Automatically generate comprehensive, high-quality code documentation using GPT-4 and Claude APIs. Analyzes source code structure, logic, and design patterns to produce contextual documentation in multiple formats.

## Key Features
- **Multi-Language Support**: Python, Java, JavaScript, TypeScript, C++, Go
- **LLM Integration**: OpenAI GPT-4, Anthropic Claude
- **Documentation Formats**: Markdown, HTML, Sphinx, JSDoc
- **Code Analysis**: Automatic extraction of functions, classes, variables
- **Type Annotation**: Smart inference of parameter and return types
- **Example Generation**: Creates usage examples from code patterns
- **Batch Processing**: Document entire projects in one command

## Tech Stack
- **LLM APIs**: OpenAI, Anthropic
- **Code Analysis**: AST parsing, syntax analysis
- **Languages**: Python 3.9+
- **Dependencies**: langchain, ast, tree-sitter

## Quick Start
```python
from doc_generator import CodeDocGenerator

generator = CodeDocGenerator(model='gpt-4')
docs = generator.analyze_file('app.py')
generator.export(docs, format='markdown')
```

## Achievements
- Generated documentation for 500+ Python functions
- 92% accuracy in type inference
- 30 seconds avg processing per 1000 lines of code
- Successfully integrated with 15+ open-source projects

## License
MIT
