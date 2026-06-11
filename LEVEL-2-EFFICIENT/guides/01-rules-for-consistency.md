# Guide 1: Rules for Consistency

[⬅ Back to Level 2 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md) | [📖 Full Roadmap](../../ROADMAP.md)

---

**Time:** 15 minutes  
**Goal:** Teach Cline your coding preferences so you don't repeat yourself

---

## What Are Cline Rules?

Think of rules as **Cline's instruction manual** for your project. Instead of saying "use TypeScript" every time, you write it once in a rule file and Cline follows it automatically.

**Without rules:** You have to repeat yourself constantly  
**With rules:** Cline remembers your preferences across all sessions

---

## Step 1: Create the Rules Directory

In your project root folder, create a directory called `.clinerules/`:

```
your-project/
  .clinerules/          ← Create this directory
  src/
  package.json
```

## Step 2: Create Your First Rule File

Create a file at `.clinerules/coding.md`:

```markdown
# Coding Standards

## Language
- Use TypeScript for all new files
- Use camelCase for variables and functions
- Use PascalCase for classes and components

## Imports
- Group imports: external → internal → styles
- Use named exports, not default exports

## Error Handling
- Use try/catch for async operations
- Return meaningful error messages
```

## Step 3: Add More Rule Files (Optional)

Split by topic so you can toggle them on/off:

`.clinerules/testing.md`:
```markdown
# Testing Standards

- Write tests for all business logic
- Name tests: "should [do something] when [condition]"
- Mock external APIs, not internal modules
```

`.clinerules/architecture.md`:
```markdown
# Architecture Decisions

- Use React functional components with hooks
- Keep components under 200 lines
- Use the repository pattern for data access
```

## Step 4: Test Your Rules

1. Start a new Cline task
2. Ask Cline to write a simple function
3. Cline should follow your rules automatically

**Try this prompt:**
```
Create a function that fetches user data from an API.
```

Cline should use TypeScript, camelCase, try/catch, and the patterns you specified.

---

## Pro Tips

- **Be specific**: "Use camelCase" works. "Write good code" doesn't.
- **Show examples**: Point to files in your project: "Follow the pattern in `src/utils/errors.ts`"
- **One topic per file**: Makes it easy to toggle rules on/off in the Cline UI
- **Commit rules to Git**: Share them with your team via version control

[📖 Sample Rule Files →](../configs/sample.clinerules/coding.md)  
[📖 Next: Checkpoints →](02-checkpoints-safety-net.md)