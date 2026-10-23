# CI/CD Lab

DevOps Week 1 - CI/CD Pipeline Lab

## Folder Structure

```
ci-cd-lab/
├── .github/
│   └── workflows/
│       └── ci.yml
├── test/
│   └── test.js
├── .gitignore
├── .yarnrc.yml
├── app.js
├── eslint.config.js
├── package.json
├── README.md
└── server.js
```

## Getting Started

### 1. Install Dependencies
```bash
npm install
```

### 2. Start Server
```bash
npm start
```
The server will run on `http://localhost:3000`.

### 3. Run Tests
```bash
npm test
```

### 4. Run Linter
```bash
npm run lint
```

## Continuous Integration
Automated testing and linting run via GitHub Actions on every push and pull request to `main` or `master` across Node.js matrix versions (18, 20, 22).
