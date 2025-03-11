# PRD Workflow Tools

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

A collection of reusable AI prompts to streamline your product development workflow. These prompts can be copied and pasted into any AI assistant (like Cursor) to automate common tasks in your product development process.

## Available Prompts

- [**Interactive PRD Creation**](interactive-prd-creation-prompt.md) - Create a PRD through a guided step-by-step questioning process
- [**PRD Comprehensive Verification**](prd-comprehensive-verification-prompt.md) - Verify and improve your PRD by identifying critical gaps and quality issues
- [**PRD to Features Extraction**](prd-to-features-prompt.md) - Extract and organize features from your PRD
- [**PRD to Rules**](prd-to-rules-prompt.md) - Generate technical guidelines and standards for development
- [**PRD to RFCs**](prd-to-rfcs-prompt.md) - Break down your PRD into manageable implementation units
- [**Implementation Template**](implementation-prompt-template.md) - Template for implementing individual RFCs
- [**PRD Change Management**](prd-change-management-prompt.md) - Manage changes to your PRD during development

## Recommended Workflow

### Initial Development
1. **Create PRD** - Start with a vague idea and develop it into a complete PRD using the Interactive Creation prompt
2. **Verify PRD** - Identify critical gaps and improve quality using the Comprehensive Verification prompt
3. **Extract Features** - Transform your verified PRD into organized features with priorities and acceptance criteria
4. **Create Rules** - Establish technical guidelines and standards based on your PRD and features
5. **Generate RFCs** - Break down the project into logical, manageable implementation units
6. **Implement RFCs** - Use the implementation template for each RFC to guide development

### Managing Changes
When new requirements or changes arise during development:
1. **Analyze Changes** - Use the Change Management prompt to assess impact and integration strategy
2. **Update Documents** - Revise affected PRD, features, rules, and RFCs based on the analysis
3. **Continue Implementation** - Resume development with the updated documentation

## How to Use

### Method 1: Manual Copy
1. Open the desired prompt file
2. Copy the entire contents
3. Paste into your AI assistant (Cursor, ChatGPT, Claude, etc.)
4. Attach your PRD or relevant documents
5. Let the AI process your request

### Method 2: Using the Copy Script
For convenience, you can use the included script to copy a prompt to your clipboard:

```bash
# Make the script executable (first time only)
chmod +x copy-prompt.sh

# Copy a prompt to clipboard
./copy-prompt.sh interactive-prd-creation-prompt.md

# See available prompts
./copy-prompt.sh
```

Then paste the prompt into your AI assistant and proceed as normal.

## Quick Tips

- Provide complete documents when possible
- Answer any clarifying questions the AI asks
- Review and customize AI outputs before implementation
- Use the prompts in sequence for best results
- For complex projects, iterate through prompts as needed

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">Made with ❤️ for better product development with AI</p> 