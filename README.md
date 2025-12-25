# project-base

A comprehensive, standardized project template with best practices for code formatting, documentation, and Git workflow.

---

## Overview

**project-base** is a reusable project foundation that provides:
- Consistent code formatting and style guidelines
- Comprehensive `.editorconfig` supporting multiple languages
- Well-organized documentation infrastructure
- Git workflow best practices
- GitHub integration templates
- Minimal but essential tooling

This repository serves as a template for starting new projects with established standards and structure.

---

## Features

### Code Standards
- **Tabs for indentation** - 4-space tab width, never spaces
- **K&R brace style** - Opening braces on same line as declarations
- **UTF-8 encoding** with CRLF line endings (Windows standard)
- **Lowercase hexadecimal** values
- **Blank line at EOF** in all files
- **No trailing whitespace** (except markdown line breaks)

### Configuration Files
- **`.editorconfig`** - Comprehensive formatting rules for multiple languages
	- C#, JavaScript/TypeScript, Python, JSON, YAML, Markdown, SQL, and more
	- K&R brace style for C#
	- Language-specific rules and conventions
- **`.gitignore`** - Extensive ignore patterns for:
	- Visual Studio and .NET artifacts
	- JetBrains Rider files
	- Python virtual environments
	- Node.js modules
	- Platform-specific files (Windows/macOS)
	- Temporary and build files

### Documentation Structure
- **`~docs/`** - Meta-documentation about project creation
	- Chat logs of AI conversations
	- Session summaries
	- Project roadmap and structure
	- Manual prompts log (user-maintained)
- **`docs/`** - Project-specific documentation

---

## Getting Started

### Using as a Template

1. **Clone or download** this repository
2. **Review and customize** configuration files as needed
3. **Update README.md** with your project information
4. **Remove or modify** documentation in `~docs/` as appropriate
5. **Start building** your project with established standards

### File Structure

```
project-base/
├── .editorconfig           # Code formatting configuration
├── .gitignore             # Git ignore patterns
├── LICENSE                # Project license
├── README.md              # This file
│
├── ~docs/                 # Meta-documentation
│   ├── manual-prompts-log.txt
│   ├── roadmap.md
│   ├── structure.md
│   ├── chat-logs/
│   └── session-logs/
│
├── docs/                  # Project documentation
│
└── .github/               # GitHub templates (TBD)
	├── ISSUE_TEMPLATE/
	└── workflows/
```

See [~docs/structure.md](~docs/structure.md) for detailed file and folder descriptions.

---

## Coding Standards

### Formatting
All code formatting is defined in [.editorconfig](.editorconfig):
- Tabs (4-space width) for indentation
- K&R brace style for C# (opening brace on same line)
- Consistent spacing and line breaks
- UTF-8 encoding with CRLF line endings

### Documentation
- **Comment everything** - All code should be well-documented
- **Maintain logs** - Keep chat and session logs up to date
- **Document decisions** - Record architectural and design choices

### Git Workflow
- **Feature branches** - Create a branch for each feature
- **Issue tracking** - Reference issues in commits
- **Logical commits** - Commit related changes together
- **Descriptive messages** - Write clear commit messages

---

## Development Workflow

### Branching Strategy
1. Create feature branch from `main`
2. Develop and test on feature branch
3. Create pull request when ready
4. Review and merge back to `main`

### Commit Conventions
Format: `[#issue] Category: Brief description`

Examples:
- `[#1] Docs: Add contributing guidelines`
- `[#5] Feature: Implement user authentication`
- `[#12] Fix: Resolve null reference in data parser`

### Issue Management
- Create issues for all planned work
- Use labels to categorize issues
- Link commits to issues
- Update issue status as work progresses

---

## Documentation

### Meta-Documentation (`~docs/`)
Documents the creation and maintenance of the project:
- **roadmap.md** - Project roadmap and milestones
- **structure.md** - Detailed project structure
- **chat-logs/** - AI conversation logs
- **session-logs/** - Work session summaries

### Project Documentation (`docs/`)
Project-specific documentation (structure depends on project type):
- API documentation
- Architecture diagrams
- User guides
- Development setup
- Deployment instructions

---

## Contributing

Contributions are welcome! Please follow these guidelines:

1. **Follow code standards** defined in `.editorconfig`
2. **Create an issue** for significant changes
3. **Use feature branches** for development
4. **Write descriptive commit messages** referencing issues
5. **Update documentation** as needed
6. **Test thoroughly** before submitting PR

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed contribution guidelines (to be created).

---

## License

[License information to be added]

---

## Roadmap

See [~docs/roadmap.md](~docs/roadmap.md) for the complete project roadmap.

### Current Phase: Foundation
- ✅ Create configuration files
- ✅ Set up documentation structure
- ✅ Define coding standards
- 🔄 Complete initial documentation
- ⬜ Set up GitHub integration

### Next Steps
- Create issue templates
- Set up GitHub Projects (Kanban)
- Write contribution guidelines
- Add LICENSE file

---

## Resources

- **EditorConfig:** https://editorconfig.org
- **Git Best Practices:** https://git-scm.com/book/en/v2
- **Conventional Commits:** https://www.conventionalcommits.org

---

## Contact

[Contact information to be added]

---

**Last Updated:** December 25, 2025
