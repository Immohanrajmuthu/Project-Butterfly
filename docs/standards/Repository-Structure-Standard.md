# Author's Intent

A repository is more than a collection of files.

It is the shared workspace where ideas become products.

A well-structured repository helps people understand a project before they understand its code.

The goal of this standard is to create repositories that are easy to navigate, easy to maintain, and capable of growing without losing clarity.

Structure should reduce confusion.

Good organization should feel almost invisible.

---

# Purpose

Repository structure exists to organize knowledge.

Every folder should communicate responsibility.

Every file should have a clear home.

Every contributor should be able to understand where something belongs without relying on tribal knowledge.

A thoughtful structure makes projects easier to build, review, maintain, and evolve.

---

# Repository Doctrine

## Structure Should Reveal Purpose

Every folder exists for a reason.

Its name should communicate what belongs inside.

Structure should explain responsibility before implementation.

When structure reflects purpose, navigation becomes intuitive.

---

# Repository Principles

## Organize by Responsibility

Group files based on what they are responsible for—not by habit or convenience.

Good

```
features/
authentication/
checkout/
catalog/
```

Avoid

```
misc/
common/
new/
old/
```

---

## Every Folder Has One Purpose

A folder should represent one responsibility.

Avoid creating folders that become storage locations for unrelated files.

If a folder requires explanation, reconsider its purpose.

---

## Clarity Before Depth

Prefer shallow, understandable structures over deeply nested hierarchies.

Good

```
src/
components/
features/
hooks/
services/
```

Avoid

```
src/
app/
shared/
common/
base/
utilities/
helpers/
misc/
```

Deep nesting increases navigation effort and reduces discoverability.

---

## Related Things Belong Together

Files that work together should live together.

Avoid scattering related files across multiple unrelated directories.

Keeping responsibilities together improves understanding and maintenance.

---

## Features Tell Better Stories

When appropriate, organize projects around features rather than technical layers.

Instead of

```
components/
hooks/
services/
screens/
```

consider

```
features/

authentication/
checkout/
profile/
orders/
```

Each feature becomes a complete story.

---

## Shared Resources Should Be Truly Shared

Only create shared directories when the contents are genuinely reused across multiple features.

Avoid moving files into shared folders prematurely.

Premature sharing often creates unnecessary dependencies.

---

## Structure Should Evolve Naturally

Repositories grow over time.

Structure should evolve to support growth—not anticipate every possible future.

Avoid designing for problems that do not yet exist.

---

# Repository Guidelines

## Root Directory

The root should contain only project-level resources.

Example

```
docs/
src/
tests/
scripts/
assets/

README.md
CHANGELOG.md
LICENSE
package.json
```

Avoid placing implementation files directly in the project root.

---

## Documentation

Keep documentation organized by purpose.

Example

```
docs/

constitution/

charters/

standards/

guides/

reference/

assets/
```

Documentation should be easy to discover and maintain.

---

## Source Code

Keep application code inside a dedicated source directory.

Example

```
src/

features/

components/

hooks/

services/

contexts/

utils/
```

Separate implementation from documentation and project configuration.

---

## Assets

Store reusable assets in a dedicated location.

Example

```
assets/

images/

icons/

fonts/

logos/
```

Avoid scattering assets throughout the project.

---

## Tests

Tests should live close to the code they verify or within a clearly defined testing directory.

Example

```
tests/

unit/

integration/

e2e/
```

or

```
Button/

Button.tsx

Button.test.tsx
```

Choose one approach and apply it consistently.

---

## Configuration

Project configuration files should remain easy to identify.

Example

```
package.json

tsconfig.json

eslint.config.js

prettier.config.js
```

Avoid hiding configuration inside unrelated directories.

---

# Repository Growth

As projects evolve:

Add folders only when they improve clarity.

Merge folders when responsibilities overlap.

Remove obsolete structures.

Keep names meaningful.

A growing repository should become more organized—not more complicated.

---

# Examples

## Good Structure

```
project/

docs/

src/
  features/
  components/
  hooks/
  services/

tests/

assets/

README.md

CHANGELOG.md
```

---

## Poor Structure

```
project/

common/

misc/

temp/

helpers/

stuff/

new/

old/

final/

test2/
```

Folder names should communicate purpose—not history.

---

# The Butterfly Test 🦋

Before creating a new folder, ask:

✓ Does this folder have one clear responsibility?

✓ Does its name reveal its purpose?

✓ Can someone predict what belongs here?

✓ Will it remain meaningful as the project grows?

✓ Does it improve the overall structure?

If yes,

the folder belongs.

---

# Closing Statement

A repository is not measured by the number of files it contains.

It is measured by how easily people can understand, navigate, and evolve it.

Every thoughtful structure reduces confusion.

Every clear boundary improves collaboration.

Every well-organized repository allows teams to focus on building rather than searching.

That is the repository structure standard of Project ButterFly.

---

**Document Owner:** Project ButterFly

**Status:** Approved

**Version:** 2.0

**Phase:** Standards

**Approved By:** Founder

**Last Updated:** 25 July 2026

**Next Review:** Every six months or whenever repository organization practices evolve.

---

> Build with Purpose.
> Design with Empathy.
> Engineer with Excellence.
- Project ButterFly 🦋