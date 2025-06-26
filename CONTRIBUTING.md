# Contributing to Ogresync

Thank you for your interest in contributing to Ogresync! Your contributions help us improve this tool for everyone. Please review the following guidelines before submitting your contributions.

## How to Contribute

### Reporting Bugs
- Use GitHub Issues to report any bugs.
- Provide detailed information: steps to reproduce, expected vs. observed behavior, and any relevant logs.

### Suggesting Features
- Open an issue to propose a new feature or enhancement.
- Describe the idea, its benefits, and any thoughts on implementation.

### Code Contributions
1. **Fork the Repository**  
   Click the "Fork" button on the repository page.

2. **Create a New Branch**  
   Create your branch from the `development` branch:
   ```bash
   git checkout -b feature/your-feature-name development
   ```
3. **Implement Your Changes**\
    Follow PEP 8 guidelines and add comments/documentation as needed.

4. **Commit Your Changes**\
    Write clear, descriptive commit messages:
    ```bash
    git commit -m "Brief description of changes"
    ```
5. **Push and Create a Pull Request**\
    Push your branch to your fork:
    ```bash
    git push origin feature/your-feature-name
    ```
    Then, open a pull request against the `development` branch.

6.  **Review Process**  
    Your pull request will be reviewed by the maintainers. Please respond to feedback and make necessary revisions.

## Branching Strategy

-   **main**: Stable, production-ready code for distribution.

-   **development**: Active development branch with full test suite. All new work should be branched off from here.

## Code Style

-   Follow PEP 8 for Python code.

-   Write clear and concise commit messages.

-   Document your code where necessary.

Additional Guidelines
---------------------

-   Contributions are welcome in all forms, including code, documentation, and design improvements.

-   If you need assistance or clarification, please ask in GitHub Issues or Discussions.
