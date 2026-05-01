# Contributing to AI Resume Analyzer

First off, thanks for taking the time to contribute! ❤️

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

* **Use a clear and descriptive title**
* **Describe the exact steps which reproduce the problem**
* **Provide specific examples to demonstrate the steps**
* **Describe the behavior you observed after following the steps**
* **Explain which behavior you expected to see instead and why**
* **Include screenshots and animated GIFs if possible**
* **Include your environment details** (OS, Python version, Node version, etc.)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

* **Use a clear and descriptive title**
* **Provide a step-by-step description of the suggested enhancement**
* **Provide specific examples to demonstrate the steps**
* **Describe the current behavior and the expected behavior**
* **Explain why this enhancement would be useful**

### Pull Requests

* Fill in the required template
* Follow the Python and TypeScript styleguides
* Include appropriate test cases
* Document new code based on the
 Documentation Styleguide
* End all files with a newline

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* Example: `Add resume parsing service (#123)`

### Python Styleguide

We follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) with some modifications:

* Use 4 spaces for indentation
* Use type hints for function parameters and returns
* Maximum line length: 100 characters
* Use docstrings for all public functions and classes
* Use meaningful variable names

Example:
```python
def parse_resume(file_path: str) -> Dict[str, Any]:
    """
    Parse resume file and extract structured data.
    
    Args:
        file_path: Path to resume file
        
    Returns:
        Dictionary with parsed resume data
    """
    pass
```

### TypeScript/React Styleguide

* Use 2 spaces for indentation
* Use meaningful component names (PascalCase)
* Use descriptive variable names (camelCase)
* Add JSDoc comments for complex functions
* Use functional components with hooks
* Maximum line length: 100 characters

Example:
```typescript
interface Props {
  title: string;
  onSubmit: (data: FormData) => Promise<void>;
}

export const ResumeUploader: React.FC<Props> = ({ title, onSubmit }) => {
  // Component code
};
```

### Documentation Styleguide

* Use Markdown
* Reference code blocks with triple backticks
* Use descriptive headers
* Include examples where applicable
* Keep line length to 80 characters for documentation

## Development Setup

1. Fork and clone the repository
2. Create a new branch for your feature: `git checkout -b feature/my-feature`
3. Make your changes
4. Add tests for new functionality
5. Ensure all tests pass: `pytest` and `npm test`
6. Commit your changes: `git commit -am 'Add my feature'`
7. Push to the branch: `git push origin feature/my-feature`
8. Create a Pull Request

## Testing

* Write tests for all new functionality
* Ensure existing tests continue to pass
* Aim for >80% code coverage

Backend:
```bash
cd backend
pytest tests/ -v
pytest tests/ --cov=app
```

Frontend:
```bash
cd frontend
npm test
npm run build
```

## Additional Notes

### Issue and Pull Request Labels

* `bug` - Something isn't working
* `enhancement` - New feature or request
* `documentation` - Improvements or additions to documentation
* `good first issue` - Good for newcomers
* `help wanted` - Extra attention is needed
* `question` - Further information is requested

## Attribution

These contribution guidelines are adapted from the Atom contribution guidelines.
