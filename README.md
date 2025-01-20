# Git Commit Message Standards

A well-structured commit message helps maintain clarity and consistency in the codebase, making it easier for collaborators to understand changes. This guide outlines the standards for writing effective Git commit messages.

## **Commit Message Structure**

Each commit message consists of three parts:
1. **Header** (Mandatory)
2. **Body** (Optional)
3. **Footer** (Optional)

---

### **1. Header**
The header summarizes the change in a single line. It follows the format:  


#### **Types**
| Type        | Description                                                   |
|-------------|---------------------------------------------------------------|
| **feat**    | A new feature.                                                |
| **fix**     | A bug fix.                                                    |
| **docs**    | Documentation updates or changes.                             |
| **style**   | Code formatting (does not affect functionality).              |
| **refactor**| Code changes that neither fix a bug nor add a feature.         |
| **perf**    | Code changes that improve performance.                        |
| **test**    | Adding or updating tests.                                     |
| **chore**   | Maintenance tasks (e.g., build process, dependency updates).  |
| **ci**      | Continuous Integration changes.                               |

#### **Examples**
- `feat: Add API to update office data`
- `fix: Resolve crash when updating office details`
- `docs: Update README with API usage details`

---

### **2. Body**
The body provides more details about the change, explaining **what** was done and **why**. Wrap text at 72 characters for better readability.

#### Example:

