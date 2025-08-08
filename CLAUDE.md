# Claude AI Development Guidelines

## Core Directives

### 1. Structural Integrity
- Existing project structure is immutable
- One theme = one file/folder (unless structure dictates otherwise)
- Edit > Create: Always modify existing files first

### 2. File Management
```
project/
├── docs/          # All .md files
├── user-delegated/
├── ai-tools/      
└── dev/           
```

### 3. Prohibited Actions
- ❌ Windows scripts (.bat, .ps1) without explicit request
- ❌ TODOs, placeholders, or sample data
- ❌ Major changes without prior approval
- ❌ Redundant files or databases
- ❌ Unauthorized deletions

### 4. Required Actions
- ✅ Use actual credentials and data
- ✅ Maintain minimal file count
- ✅ Protect core files (DB logic, config, main)
- ✅ Document changes in CHANGELOG.md
- ✅ Verify dependency cascades

## Change Management

### Impact Analysis
1. Identify affected components
2. Map dependency chains
3. Update all touchpoints
4. Verify compatibility
5. Document in CHANGELOG.md

### Version Control
```markdown
## [X.Y.Z] - YYYY-MM-DD
### Changed
- Description [Components: A, B]
- Dependencies updated: [List]
### Impact
- Migration required: Yes/No
```

## Communication Protocol

### For Changes
```
"Planning to [action] because [reason]. 
This affects [components]. Proceed?"
```

### For Uncertainties
```
"Current structure shows [observation].
Should I [option A] or [option B]?"
```

## Quality Standards

1. **Clarity**: Readable > Clever
2. **Consistency**: Follow existing patterns
3. **Efficiency**: Minimal but complete
4. **Documentation**: Essential only

## Quick Reference

| Action | Check |
|--------|-------|
| Creating file | Can existing be edited? |
| Major change | User approval obtained? |
| Dependency update | All cascades mapped? |
| Documentation | CHANGELOG updated? |

---
**Remember**: Minimize entropy. Respect structure. Ask when uncertain.
