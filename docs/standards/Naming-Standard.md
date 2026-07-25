# Author's Intent

Names are the foundation of communication.

Every project, folder, file, component, function, variable, and document begins with a name.

Good names reduce confusion.

Great names communicate purpose.

The goal of this standard is to create names that remain clear, consistent, and meaningful throughout the lifetime of a project.

---

# Purpose

A name should explain what something is—not how it is implemented.

Clear naming improves readability, collaboration, maintenance, and long-term understanding.

Good names reduce the need for additional explanation.

---

# Naming Doctrine

## Names Should Reveal Purpose

A name is successful when its purpose is immediately understandable.

Names should communicate intent before implementation.

---

# Naming Principles

## Purpose Before Implementation

Prefer names that describe responsibility instead of technology.

Good

```
UserProfile
```

Avoid

```
UserProfileReactComponent
```

---

## Clarity Before Brevity

Use complete, meaningful words.

Good

```
calculateTotalPrice()
```

Avoid

```
calcTP()
```

---

## Consistency Creates Confidence

Use similar naming patterns for similar concepts.

If one service uses:

```
UserService
```

another service should not use:

```
UserManager
```

unless their responsibilities are genuinely different.

---

## One Meaning Per Name

A name should represent one concept.

Avoid using the same word to describe multiple unrelated responsibilities.

---

## Avoid Unnecessary Abbreviations

Only use abbreviations that are universally understood.

Good

```
API
URL
HTML
```

Avoid

```
cfg
tmp
obj
util
misc
```

---

## Be Specific

Choose names that explain responsibility.

Good

```
ShoppingCartSummary
```

Better than

```
DataContainer
```

---

## Names Should Age Well

Choose names that will remain meaningful as the product evolves.

Avoid names based on temporary implementation details.

---

# Naming Guidelines

## Projects

Use clear product names.

```
ProjectButterFly
KuttyCouture
```

---

## Repositories

Use consistent repository names.

```
project-butterfly

kutty-couture-web

kutty-couture-api
```

---

## Folders

Use lowercase with hyphens.

```
design-system

shared-components

accessibility
```

---

## Files

Use descriptive names.

```
component-charter.md

design-system-charter.md

user-profile.tsx
```

---

## Components

Use PascalCase.

```
ProductCard

CheckoutButton

UserAvatar
```

---

## Functions

Use verbs.

```
calculateTotal()

loadProducts()

submitOrder()
```

---

## Variables

Use nouns.

```
user

products

totalPrice
```

---

## Constants

Use UPPER_SNAKE_CASE only for true constants.

```
MAX_LOGIN_ATTEMPTS

DEFAULT_LANGUAGE
```

---

## Boolean Values

Use names that answer yes/no questions.

```
isLoading

hasPermission

canEdit

shouldRetry
```

---

# Examples

| Poor Name | Better Name |
|-----------|-------------|
| data | productList |
| temp | temporaryFile |
| util | currencyFormatter |
| helper | validationService |
| obj | customer |
| info | productDetails |

---

# The Butterfly Test 🦋

Before introducing a new name, ask:

✓ Does it reveal its purpose?

✓ Is it easy to understand?

✓ Is it consistent with similar names?

✓ Will it still make sense one year from now?

✓ Would a new team member understand it immediately?

If yes,

the name belongs.

---

# Closing Statement

Names are more than identifiers.

They are the first expression of understanding.

Every clear name reduces confusion.

Every consistent name strengthens communication.

Every thoughtful name makes future work easier.

That is the naming standard of Project ButterFly.

---

**Document Owner:** Project ButterFly

**Status:** Approved

**Version:** 2.0

**Phase:** Standards

**Approved By:** Founder

**Last Updated:** 25 July 2026

**Next Review:** Every six months or whenever naming practices evolve.

---

> Build with Purpose.
> Design with Empathy.
> Engineer with Excellence.
 - Project ButterFly 🦋