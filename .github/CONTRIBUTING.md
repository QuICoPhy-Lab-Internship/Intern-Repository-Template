# Introduction

Thank you for your interest in contributing to our project! We welcome contributions from the community and appreciate your efforts to help improve our codebase. This document provides guidelines and instructions for contributing to our project.

## Installation

To set up the development environment, please follow these steps:

1. Clone your repository:
   ```bash
    git clone <your-fork-url>
    ```
2. Navigate to the project directory:
3. Initialize the Virtual Environment using [uv](https://docs.astral.sh/uv/):
    ```bash
     uv sync --dev
    ```
4. Set up Pre-commit hooks:
    ```bash
     uv run pre-commit install
    ```

# Guidelines

1. When you whish to contribute, please create a new branch for your changes.
2. Make your changes and commit them with clear and descriptive commit messages.
3. Push your changes to your repository, on the branch dedicated for those changes.
4. Each week, pull request in the branch `review` and add your supervisor(s) as reviewer(s).
5. Everytime a task is finished, create a pull request in your repository on the `dev` branch, describing the changes you have made and why they are important/necessary.
6. We will review your pull request and provide feedback. We may ask for changes or improvements before merging your contribution.
7. Once your contribution is approved, it will be merged into the `dev` branch.
8. Please ensure that your code follows the project's coding standards and guidelines, and that it includes appropriate tests and documentation.
