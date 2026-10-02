# What Is a Codebase?

A **codebase** is all the files that define a software project: source code, configuration, tests, documentation, and assets, usually in one folder or Git repository. Developers change it together; builds and deployments read from the same tree.

**Source code** implements behavior (data, UI, APIs) and is split into modules so changes stay localized. **Configuration** (`package.json`, `requirements.txt`, Dockerfiles, etc.) declares dependencies and how to build and run the app. **Tests** record expected behavior and make refactors safer. **Docs** (README, comments, design notes) explain setup and intent for humans.

**Git** stores history: commits, branches, and reviews. **Tooling** (linters, type checkers, CI) uses config in the repo to keep quality consistent. The codebase is also a **team asset**: shared conventions, reviews, and ongoing cleanup of technical debt shape how fast you can ship and maintain the product.

**This project (`my-first-project`)** is still empty—no app code yet. Adding a README, choosing a stack, running `git init`, and committing your first files is how this folder becomes a real codebase.
