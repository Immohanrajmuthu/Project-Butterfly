# Author's Intent

Code is read far more often than it is written.

Every line should communicate intent as clearly as it performs work.

The purpose of this standard is not to enforce formatting preferences.

Its purpose is to encourage code that is understandable, maintainable, and expressive.

Good code should explain itself.

Comments should clarify decisions—not compensate for confusing implementation.

---

# Purpose

Code is a form of communication.

It should help future contributors understand what the system does, why it exists, and how it behaves.

Readable code reduces mistakes, simplifies maintenance, and enables confident collaboration.

The goal is not simply to make code work.

The goal is to make code understandable.

---

# Code Style Doctrine

## Code Should Explain Itself

Good code communicates its purpose through clear structure, meaningful names, and thoughtful organization.

If code requires excessive explanation, the implementation should be reconsidered before additional comments are added.

---

# Code Style Principles

## Readability Before Cleverness

Choose solutions that are easy to understand over solutions that are merely clever.

Future maintainability is more valuable than short-term ingenuity.

---

## One Function, One Responsibility

Every function should perform one clear task.

Large functions often indicate multiple responsibilities.

Smaller functions are easier to understand, test, and reuse.

---

## Express Intent Clearly

Write code that reveals what it is trying to accomplish.

Meaningful names and straightforward logic reduce the need for explanation.

---

## Simplicity Over Complexity

Prefer the simplest solution that solves the problem correctly.

Avoid unnecessary abstraction, premature optimization, and overly complex logic.

Complexity should only exist when it provides meaningful value.

---

## Consistency Creates Confidence

Use consistent coding patterns throughout the project.

Similar problems should be solved in similar ways.

Consistency improves readability and reduces cognitive load.

---

## Comments Explain Why

Code should explain what it does.

Comments should explain why it exists or why a particular decision was made.

Avoid comments that simply repeat the code.

Good

```typescript
// Retry once because the payment gateway occasionally returns transient failures.
```

Avoid

```typescript
// Increment i
i++;
```

---

## Remove Dead Code

Unused code increases confusion.

Version control preserves history.

If code no longer serves a purpose, remove it.

---

## Avoid Magic Values

Replace unexplained values with meaningful constants.

Good

```typescript
const MAX_LOGIN_ATTEMPTS = 5;
```

Avoid

```typescript
if (attempts > 5)
```

---

## Keep Functions Small

Small functions are easier to read, test, and maintain.

If scrolling is required to understand a function, consider extracting responsibilities.

---

## Fail Clearly

Errors should communicate what happened and how they can be resolved.

Avoid vague messages.

Good

```text
User profile not found.
```

Better than

```text
Error 101
```

---

# Code Organization

Arrange code in a logical order.

Example

- Imports
- Constants
- Types
- Main implementation
- Helper functions
- Exports

A predictable structure improves navigation.

---

# Examples

Good

```typescript
function calculateOrderTotal(items: CartItem[]): number {
    return items.reduce(
        (total, item) => total + item.price,
        0
    );
}
```

Poor

```typescript
function calc(a){
return a.reduce((t,i)=>t+i.price,0)
}
```

The difference is not functionality.

The difference is clarity.

---

# The Butterfly Test 🦋

Before committing code, ask:

✓ Does the code explain itself?

✓ Is the purpose immediately clear?

✓ Can responsibilities be understood quickly?

✓ Is there unnecessary complexity?

✓ Would another engineer understand this without additional explanation?

✓ Does the code follow existing project patterns?

If yes,

the code belongs.

---

# Closing Statement

Code is not measured by how clever it is.

It is measured by how clearly it communicates intent.

Every meaningful name improves understanding.

Every simple function reduces complexity.

Every thoughtful implementation makes future change easier.

That is the code style standard of Project ButterFly.

---

**Document Owner:** Project ButterFly

**Status:** Approved

**Version:** 2.0

**Phase:** Standards

**Approved By:** Founder

**Last Updated:** 25 July 2026

**Next Review:** Every six months or whenever coding practices evolve.

---

> Build with Purpose.
> Design with Empathy.
> Engineer with Excellence.

- Project ButterFly 🦋