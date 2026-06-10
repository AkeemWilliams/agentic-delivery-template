# Copilot Instructions

## Enginerring standards
- Use Typescript strict mode
- Avoid use of any as a type
- Prefer unknown when type is uncertain
- Validate external data at boundaries
- Keep domain logic out of React components
- Add or update tests for changed behavior
- Preserve accessibility

## Workflow
Before coding:
1. Read relevant files
2. Explain the plan
3. Identiyfy risks
4. Make the smallest safe change

After coding:
1. Run typecheck
2. Run lint
3. Run tests
4. Summarize changed files
5. List risks and follow-ups

## Architectural rules
- React components cannot import database code
- API routes must validate input
- Environment variables must go through config module
- Generated code must follow the same standards as human code