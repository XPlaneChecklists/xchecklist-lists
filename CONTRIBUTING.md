# Contributing Guidelines

Thank you for contributing to the X-Plane XChecklist Community Repository.

## 📁 Directory Structure

All contributions must follow this structure:

```

/<studio>/<icao>/<variant>/clist.txt

```

### Example

```

/toliss/a320/a320neo/clist.txt
/zibo/b738/b737-800x/clist.txt

```

## 🧾 Naming Conventions

- Use lowercase for all folder names
- Avoid spaces — use hyphens if needed
- Keep names concise and recognizable

### Examples

| Type     | Example        |
|----------|----------------|
| studio   | `toliss`       |
| icao     | `a320`         |
| variant  | `a320neo`      |

## ✅ Checklist Requirements

Before submitting:

- Ensure the checklist works with XChecklist
- Verify compatibility with the specific aircraft version
- Avoid generic checklists — tailor to the aircraft
- Maintain consistent formatting

## ✍️ Style Guidelines

- Use clear, concise step descriptions
- Group steps logically (e.g., Preflight, Before Start, After Takeoff)
- Avoid unnecessary verbosity
- Prefer real-world procedures when possible

## 📚 Sources (Optional but Encouraged)

If applicable, include references:

- FCOM
- POH
- Aircraft manuals
- Developer documentation

You may include notes in comments within the checklist file.

## 🔄 Pull Request Process

1. Fork the repository
2. Create a new branch:
```

feature/<aircraft-name>

```
3. Add your checklist in the correct directory
4. Commit with a clear message:
```

Add ToLiss A320neo checklist

```
5. Open a Pull Request with:
- Aircraft name
- Version tested
- Notes (if any)

## 🚫 What to Avoid

- Incorrect directory structure
- Duplicate submissions without improvements
- Broken or untested checklists
- Non-XChecklist formats

## 💬 Questions

If you're unsure about anything, open an issue before submitting your contribution.
