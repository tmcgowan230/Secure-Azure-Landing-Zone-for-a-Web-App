# Contributing to Secure Azure Landing Zone for a Web App

Thank you for your interest in contributing to this project! This guide will help you share your reviews, improvements, or suggestions with the original repository owner.

## How to Share Your Review with the Original Repository Owner

If you've forked this repository and want to contribute your changes back, follow these steps:

### 1. Ensure Your Fork is Up to Date

Before creating a pull request, make sure your fork is synchronized with the original repository:

```bash
# Add the original repository as an upstream remote (if not already added)
git remote add upstream https://github.com/ORIGINAL_OWNER/Secure-Azure-Landing-Zone-for-a-Web-App

# Fetch the latest changes from the original repository
git fetch upstream

# Merge changes from the original repository into your local branch
git checkout main
git merge upstream/main

# Push the updated changes to your fork
git push origin main
```

### 2. Create a Feature Branch

Create a new branch for your changes:

```bash
git checkout -b feature/your-improvement-name
```

### 3. Make Your Changes

- Make your improvements, fixes, or additions
- Follow the existing code style and documentation format
- Test your changes thoroughly
- Document your changes clearly

### 4. Commit Your Changes

```bash
git add .
git commit -m "Description of your changes"
git push origin feature/your-improvement-name
```

### 5. Create a Pull Request

1. Go to your forked repository on GitHub
2. Click the "Pull Request" button or navigate to the "Pull requests" tab
3. Click "New pull request"
4. Select the original repository's `main` branch as the base
5. Select your feature branch as the compare branch
6. Fill in the pull request template:
   - **Title**: A clear, concise description of your changes
   - **Description**: Explain what you changed and why
   - Include any relevant screenshots or documentation
   - Reference any related issues
7. Click "Create pull request"

### 6. Respond to Feedback

- The original repository owner may request changes or ask questions
- Be responsive to feedback and make requested modifications
- Push any additional commits to your feature branch
- The pull request will automatically update with your new commits

## Guidelines for Contributions

### What to Contribute

- **Security improvements**: Enhanced security configurations or best practices
- **Documentation**: Clarifications, corrections, or additional explanations
- **Architecture enhancements**: Improvements to the Azure infrastructure design
- **Bug fixes**: Corrections to any issues found
- **Cost optimizations**: Suggestions for reducing Azure costs

### Contribution Standards

- **Be respectful**: Follow the code of conduct and be courteous in all interactions
- **Be clear**: Provide clear explanations for your changes
- **Be focused**: Keep pull requests focused on a single improvement or fix
- **Be documented**: Update relevant documentation when making changes
- **Be tested**: Ensure your changes work as expected

## Questions or Issues?

If you have questions about contributing or encounter any issues:

1. Check existing issues and pull requests to see if your topic has been addressed
2. Open a new issue in the original repository to discuss your proposed changes
3. Ask questions in the pull request comments

## Alternative Ways to Contribute

If you don't want to create a pull request, you can still contribute by:

- **Opening issues**: Report bugs or suggest improvements
- **Providing feedback**: Comment on existing issues or pull requests
- **Sharing knowledge**: Write blog posts or tutorials about this project
- **Spreading the word**: Star the repository and share it with others

Thank you for contributing to making Azure environments more secure and well-architected!
