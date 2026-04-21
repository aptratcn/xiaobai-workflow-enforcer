# Workflow Enforcer 🔒

> Mandatory workflows for AI agents

**Inspired by Superpowers (161K stars)** — the framework that proved enforcement is the killer feature.

## The 5 Gates

Every task MUST pass through these gates:

```
GATE 1: DESIGN
├── What problem are we solving?
├── What's the simplest solution?
└── Output: Design doc

GATE 2: PLAN
├── Break into atomic tasks
├── Identify dependencies
└── Output: Task list

GATE 3: TDD
├── Write test first
├── Run test (should fail)
└── Output: Failing test

GATE 4: EXECUTE
├── Write minimal code
├── Run test (should pass)
└── Output: Working code

GATE 5: VERIFY
├── All tests pass
├── No regressions
└── Output: Verified feature
```

## Why Enforcement Works

| Without Enforcement | With Enforcement |
|---------------------|------------------|
| "I'll do it properly later" | Must do it properly now |
| Skip tests "just this once" | Tests are mandatory |
| Half-finished refactors | Complete or don't start |
| "It works on my machine" | Verified before merge |

## Quick Start

```
# The gates are automatic
# Just start working, and the workflow will enforce:

1. Ask "what are we building?" → DESIGN gate
2. Ask "what are the steps?" → PLAN gate
3. Generate test first → TDD gate
4. Write code → EXECUTE gate
5. Run all tests → VERIFY gate
```

## Anti-Rationalization Table

| Common Excuse | Reality |
|---------------|---------|
| "Tests slow me down" | Bugs slow you down more |
| "I'll add tests later" | You won't |
| "This is just a quick fix" | Quick fixes create tech debt |
| "I know it works" | How do you know? |

## License

MIT
