# Commit Message Convention

To keep our history clean and readable, we follow a strict naming convention for all git commits.

### 1. The Format

Every commit message must consist of a **Capitalized Type**, a colon, and a **Capitalized Subject**.

Syntax:

Type: Subject

Example:

Feature: Add dark mode switch

### 2. The Grammar Rule: Imperative Mood

Write the subject line in the **imperative mood** (as if you are giving a command). Do not use the past tense or present continuous tense.

The Golden Rule:

Your message should complete the sentence: "If applied, this commit will..."

- ❌ **Bad:** `Refactor: Refactored the helper function` _(If applied, this commit will Refactored...)_
    
- ❌ **Bad:** `Fix: Fixing the login bug` _(If applied, this commit will Fixing...)_
    
- ✅ **Good:** `Refactor: Refactor the helper function` _(If applied, this commit will **Refactor**...)_
    
- ✅ **Good:** `Fix: Fix login bug` _(If applied, this commit will **Fix**...)_
    

### 3. Allowed Types

You must use one of the following types to classify your commit:

Feature

Use for a new feature or functionality.

- _Example:_ `Feature: Add user profile page`
    
- _Example:_ `Feature: Implement search filters`
    

Fix

Use for a bug fix.

- _Example:_ `Fix: Resolve crash on startup`
    
- _Example:_ `Fix: Prevent negative numbers in cart`
    

Refactor

Use for code changes that neither fix a bug nor add a feature. This includes cleaning up code, renaming variables, or removing unused files.

- _Example:_ `Refactor: Simplify date parsing logic`
    
- _Example:_ `Refactor: Remove unused legacy scripts`
    

Style

Use for changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc).

- _Example:_ `Style: Format code with Prettier`
    
- _Example:_ `Style: Fix indentation in navbar`
    

Config

Use for changes to configuration files (env, docker, pipelines, eslint, etc).

- _Example:_ `Config: Update eslint rules`
    
- _Example:_ `Config: Change database port in docker-compose`
    

Test

Use for adding missing tests or correcting existing tests.

- _Example:_ `Test: Add unit tests for payment validation`
    

Chore

Use for mundane tasks, maintenance, or dependency updates that don't fall into the categories above.

- _Example:_ `Chore: Update npm dependencies`
    
- _Example:_ `Chore: Delete temporary build files`
    

### Summary Table

|**Type**|**Description**|**Example**|
|---|---|---|
|**Feature**|New code logic|`Feature: Add submit button`|
|**Fix**|Bug repair|`Fix: Handle null error`|
|**Refactor**|Cleanup / Deletion|`Refactor: Remove dead code`|
|**Style**|Formatting only|`Style: Remove whitespace`|
|**Config**|Setup files|`Config: Update .env.example`|
|**Test**|Testing|`Test: Add login tests`|
|**Chore**|Maintenance|`Chore: Upgrade React version`|