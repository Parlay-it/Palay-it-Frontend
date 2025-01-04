# Palay-it-Frontend
Welcome to the **Frontend** repository of the project! This application is built using **React.js** with **Vite** for fast and efficient development.


## Table of Contents

- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Branching Strategy](#branching-strategy)
- [Commit Style](#commit-style)
- [How to Contribute](#how-to-contribute)



## Project Overview

This repository contains the frontend of the project, structured using the **atomic design methodology** to ensure scalable and maintainable code. The application is built with **React.js** and powered by **Vite** for faster build times and a better development experience.



## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/frontend-repo.git
   cd frontend-repo

2. Install dependencies:

```bash
npm install
```
3. Start the development server:

```bash
npm run dev
```
4. Build for production:
```bash
npm run build
```

## Branching Strategy
The repository uses a two-branch strategy:

1. Staging (staging): All contributions must be made to this branch first. It is used to test and verify changes before being pushed to production.

2. Production (production): Only tested and approved changes from staging are merged here.


## Commit Style
We follow the Conventional Commit style for commit messages. This ensures clarity and consistency across the repository.

Common Commit Types:
- feat: A new feature.
- fix: A bug fix.
- chore: Changes to build process or dependencies.
- docs: Updates to documentation.
- style: Code style changes (e.g., formatting).
- refactor: Code changes that neither fix a bug nor add a feature.
- test: Adding or updating tests.

## How to Contribute
1. Fork the Repository
2. Create a Feature Branch: always create a new branch from staging

```bash
git checkout staging
git checkout -b feature/your-feature-name
```
3. Commit Changes
Use the Conventional Commit style:

```bash
git add .
git commit -m "feat(scope): description of the feature"
```
4. Push Changes
Push your changes to your feature branch:

```bash
git push origin feature/your-feature-name
```
5. Create a Pull Request
Open a Pull Request (PR) to the staging branch on GitHub.
Wait for reviews and approvals before merging.

6. Merging to Production
Once changes are tested and approved on staging, they can be merged into production.
