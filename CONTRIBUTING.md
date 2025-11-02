# Contributing to Automate The Boring Stuff

Thank you for your interest in contributing to this project! This document provides guidelines on how to report issues and contribute to the project.

## How to Report Issues

When you encounter a problem or have a suggestion, you can submit an issue to broadcast it to others and get help from the community.

### Before Creating an Issue

1. **Search existing issues** - Check if someone has already reported the same problem
2. **Verify the problem** - Make sure you can reproduce the issue consistently
3. **Gather information** - Collect relevant details about the problem

### Creating a Good Issue Report

A well-written issue helps others understand and resolve the problem quickly. Include the following information:

#### For Bug Reports:
- **Title**: A clear, concise description of the problem
- **Description**: 
  - What you were trying to do
  - What you expected to happen
  - What actually happened
  - Steps to reproduce the issue
- **Environment**: 
  - Python version
  - Operating system
  - Relevant library versions
- **Code samples**: Include minimal code that demonstrates the problem
- **Error messages**: Copy the full error message or traceback

#### For Feature Requests:
- **Title**: Brief description of the feature
- **Description**:
  - What problem does this feature solve?
  - How would this feature work?
  - Why would this be useful?
- **Examples**: Show how the feature would be used

#### For Questions:
- **Title**: Clear question statement
- **Description**:
  - What are you trying to accomplish?
  - What have you tried so far?
  - Where are you stuck?

### Example Issue Format

```
Title: Script fails when processing files with special characters

Description:
I'm trying to use the file organization script on my Documents folder, 
but it crashes when it encounters files with non-ASCII characters in the filename.

Steps to reproduce:
1. Create a file named "résumé.txt"
2. Run the script: python organize_files.py
3. Script crashes with UnicodeDecodeError

Expected behavior:
The script should handle files with special characters in their names.

Actual behavior:
Script crashes with the following error:
[paste error message here]

Environment:
- Python 3.9.5
- Windows 10
- Script: organize_files.py from Chapter 9
```

## Issue Etiquette

- **Be respectful** - Treat others as you would like to be treated
- **Be patient** - Contributors are volunteers with limited time
- **Be constructive** - Focus on solving problems, not placing blame
- **Stay on topic** - Keep discussions focused on the issue at hand
- **Update issues** - If you find a solution, share it with others

## After Submitting an Issue

1. **Monitor notifications** - Check for responses and questions
2. **Provide additional information** - Respond to requests for clarification
3. **Test solutions** - If someone suggests a fix, try it and report back
4. **Close resolved issues** - Mark the issue as resolved when fixed

## Contributing Code

If you'd like to contribute code fixes or improvements:

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes with clear commit messages
4. Test your changes thoroughly
5. Submit a pull request with a description of your changes

## Getting Help

If you're new to GitHub issues:
- [GitHub Issues Documentation](https://docs.github.com/en/issues)
- [How to Write a Good Bug Report](https://developer.mozilla.org/en-US/docs/Mozilla/QA/Bug_writing_guidelines)

Thank you for helping improve this project!
