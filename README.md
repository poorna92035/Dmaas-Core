Expected package.json Scripts:

{
"scripts": {
"test": "jest",
"lint": "eslint .",
"type-check": "tsc --noEmit",
"build": "tsc"
}
}


Flow:
Validate
↓
Unit Tests
↓
Type Check
↓
Lint Check
↓
Security Audit
↓
Build Stable Contracts / Utilities
↓
Package Artifact
↓
Publish to AWS CodeArtifact
