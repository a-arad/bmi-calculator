# span Task: Setup React Frontend Project (ID: setup-fe)

## Task Description
Initialize React project with Create React App, add styled-components, setup basic folder structure and config

## Component & Technical Context
**Component:** frontend
**Estimated Complexity:** 5 Claude Code conversation turns
**Current Retry:** 0 (if > 0, review previous failure context)

## Dependencies & Prerequisites
**No dependencies** - This task can start immediately

## Environment Variables
```
ESTIMATED_TURNS: 5
DELIVERABLES: package.json,src/,.gitignore,README.md
TASK_COMPONENT: frontend
```

## Deliverables & Success Criteria
This task must produce:
- **Primary Implementation:** Concrete, working code files
- **Testing:** Comprehensive tests that validate functionality
- **Documentation:** Update relevant docs (README, API docs, etc.)
- **Pull Request:** Clear PR with descriptive title and body
- **Integration:** Ensure no breaking changes to existing functionality

## Claude Code Execution Guidelines

### Turn Management (Max: 5 turns)
1. **Planning Phase** (1-2 turns): Understand requirements, explore codebase
2. **Implementation Phase** (60-70% of turns): Core development work
3. **Testing Phase** (20-30% of turns): Validation and edge cases  
4. **Finalization** (1-2 turns): Documentation, PR creation

### Required Actions
- [ ] Read and follow project conventions in `/CLAUDE.md`
- [ ] Use appropriate tools: `Edit`, `View`, `Bash(git:*)`, `GrepTool`, `Replace`
- [ ] Run tests to validate implementation: `npm test` / `cargo test` / `pytest`
- [ ] Create meaningful commit messages following project standards
- [ ] Open PR with labels: `span-task`, `frontend`

### Error Handling & Quality
- Handle edge cases and error conditions explicitly
- Follow security best practices (input validation, no hardcoded secrets)
- Use existing patterns and utilities in the codebase
- Optimize for readability and maintainability

## span Orchestration Context
- **Project Repository:** bmi-calculator
- **Orchestration System:** This task is part of span's AI-coordinated development
- **Progress Tracking:** Completion will be tracked via GitHub issues automatically
- **Dependency Chain:** Completing this task may trigger dependent tasks
- **Failure Recovery:** Failures create investigation issues for human review

## Implementation Strategy
Based on the component type `frontend`, consider:

- Set up component structure and routing
- Implement UI components with proper state management
- Add form validation and user feedback
- Connect to backend APIs with error handling
- Write unit tests for components and integration tests for user flows

## Final Notes
- **Time Budget:** Complete within 5 conversation turns maximum
- **Focus:** Incremental progress with each turn producing measurable results
- **Communication:** Clear commit messages and PR descriptions for human reviewers
- **Integration:** Coordinate with existing codebase patterns and dependencies

Ready to begin implementation. Start by exploring the codebase to understand the current state and integration points.
