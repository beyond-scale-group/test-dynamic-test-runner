# test-dynamic-test-runner

Integration test repository for the dynamic-test-runner GitHub Action.

## Structure

```
packages/
├── api/
│   ├── src/index.ts
│   └── test-config.json
├── web/
│   ├── src/App.tsx
│   └── test-config.json
└── shared/
    ├── src/utils.ts
    └── test-config.json
```

## Usage

Tests are triggered via `workflow_dispatch` from the main repository.

