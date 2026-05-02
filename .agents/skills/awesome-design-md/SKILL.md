```markdown
# awesome-design-md Development Patterns

> Auto-generated skill from repository analysis

## Overview
This skill teaches the core development patterns and conventions used in the `awesome-design-md` TypeScript repository. It covers file naming, import/export styles, commit message patterns, and testing practices. The guide is designed to help contributors maintain consistency and quality in the codebase.

## Coding Conventions

### File Naming
- Use **PascalCase** for all file names.
  - Example:  
    ```
    DesignComponent.ts
    MarkdownParser.test.ts
    ```

### Import Style
- Use **relative imports** for all modules.
  - Example:
    ```typescript
    import { parseMarkdown } from './MarkdownParser';
    ```

### Export Style
- Use **named exports** for all modules.
  - Example:
    ```typescript
    // In DesignComponent.ts
    export function DesignComponent() { ... }
    ```

### Commit Messages
- Commit messages are **freeform** (no enforced prefix), with an average length of 39 characters.
- Example:
  ```
  Add new parser for design tokens
  ```

## Workflows

### Adding a New Module
**Trigger:** When you need to add a new feature or utility.
**Command:** `/add-module`

1. Create a new file using PascalCase (e.g., `NewFeature.ts`).
2. Implement your logic using TypeScript.
3. Use named exports for all exported functions or classes.
4. Import dependencies using relative paths.
5. Write a corresponding test file named `NewFeature.test.ts`.
6. Commit your changes with a clear, descriptive message.

### Writing Tests
**Trigger:** When you implement or update a module.
**Command:** `/write-test`

1. Create a test file with the pattern `*.test.ts` (e.g., `MarkdownParser.test.ts`).
2. Write your test cases using the preferred (unknown) testing framework.
3. Ensure all major functionality is covered.
4. Run your tests to verify correctness.

## Testing Patterns

- Test files follow the pattern: `*.test.ts`
- Place test files alongside the modules they test.
- Example:
  ```
  MarkdownParser.ts
  MarkdownParser.test.ts
  ```
- The testing framework is not specified; follow existing patterns in the repo.

## Commands
| Command        | Purpose                                 |
|----------------|-----------------------------------------|
| /add-module    | Scaffold and add a new module           |
| /write-test    | Add or update tests for a module        |
```
