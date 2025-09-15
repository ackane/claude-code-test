# Claude Code Configuration

This file contains project-specific configuration and best practices for Claude Code.

## Commands

### Build & Test
```bash
# Add your build command here
npm run build

# Add your test command here
npm test

# Add your lint command here
npm run lint

# Add your type check command here
npm run typecheck
```

### Development
```bash
# Add your dev server command here
npm run dev

# Add your format command here
npm run format
```

## Project Structure

```
claude-code-test/
├── README.md          # Project documentation
├── CLAUDE.md          # Claude Code configuration
└── src/               # Source code (add as needed)
```

## Best Practices

### Code Style
- Follow existing code conventions in the project
- Use consistent naming patterns
- Add comments only when necessary for complex logic
- Prefer self-documenting code

### Git Workflow
- Use descriptive commit messages
- Test changes before committing
- Keep commits focused on single changes
- Use conventional commit format when possible

### Testing
- Write tests for new functionality
- Run tests before pushing changes
- Maintain test coverage
- Test edge cases and error conditions

### Documentation
- Keep README.md updated
- Document complex functions and modules
- Include usage examples
- Update CLAUDE.md when adding new commands

## Claude Code Tips

### File Operations
- Always read files before editing to understand context
- Use existing patterns and conventions
- Prefer editing over creating new files

### Search & Navigation
- Use Grep for code searches
- Use Glob for file pattern matching
- Search before making assumptions about code structure

### Task Management
- Break complex tasks into smaller steps
- Use the todo system for multi-step processes
- Mark tasks complete as you finish them
- Be specific about task descriptions

## Environment Setup

Add any project-specific setup instructions here:

```bash
# Example setup commands
# npm install
# cp .env.example .env
# npm run setup
```

## Troubleshooting

Common issues and solutions:

- **Build failures**: Check dependencies and run clean install
- **Test failures**: Verify test environment setup
- **Lint errors**: Run formatter and fix style issues
- **Type errors**: Update type definitions and imports