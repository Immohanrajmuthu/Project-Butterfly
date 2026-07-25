# Author's Intent

Software is rarely improved in isolation.

The best software is the result of thoughtful collaboration, shared learning, and respectful feedback.

Code reviews exist to improve both the software and the people who build it.

The purpose of this standard is not to approve changes.

Its purpose is to increase understanding, improve quality, and strengthen trust within the team.

---

# Purpose

Code Review is the practice of collaboratively evaluating software changes before they become part of the product.

A good review improves readability, maintainability, quality, and shared understanding.

Every review is an opportunity to make both the software and the engineering team better.

---

# Code Review Doctrine

## Understanding Before Approval

The goal of a review is not to find fault.

The goal is to understand the problem, evaluate the solution, and improve it together.

Approval is the outcome of understanding—not the purpose of the review.

---

# Review Principles

## Review the Code, Not the Person

Every comment should focus on improving the software.

Respect people.

Question decisions.

Never question intentions.

Constructive feedback builds stronger teams.

---

## Seek Understanding First

Before suggesting changes, understand why the current solution exists.

Ask questions.

Avoid assumptions.

Context often explains decisions that code alone cannot.

---

## Explain the Why

Feedback should teach rather than instruct.

Instead of saying:

> Rename this variable.

Explain why:

> A more descriptive name would make this intent clearer for future readers.

Understanding creates lasting improvement.

---

## Celebrate Good Decisions

Reviews should recognize thoughtful engineering as well as opportunities for improvement.

Acknowledging good work encourages learning and reinforces good practices.

Celebrate clarity.

Celebrate simplicity.

Celebrate quality.

---

## Optimize for Learning

Every review should leave both the author and the reviewer with a better understanding than before.

Knowledge shared during reviews strengthens the entire team.

---

## Keep Feedback Actionable

Feedback should be:

- Specific
- Clear
- Respectful
- Practical

Avoid vague comments that leave room for interpretation.

Good feedback helps the author understand exactly what can be improved.

---

## Focus on What Matters

Prioritize discussions that improve:

- Correctness
- Simplicity
- Maintainability
- Accessibility
- Security
- Performance
- Architecture
- Readability
- Documentation

Not every suggestion deserves equal attention.

Focus on changes that create meaningful value.

---

# What to Review

Every review should consider the software as a whole.

## Purpose

Does this change solve the intended problem?

---

## Readability

Will another engineer understand this code without additional explanation?

---

## Simplicity

Is this the simplest solution that satisfies the requirements?

---

## Maintainability

Will future engineers be comfortable modifying this code?

---

## Architecture

Does this change align with the project's architectural direction?

---

## Accessibility

Does the implementation preserve or improve accessibility?

Accessibility is a quality requirement—not an optional enhancement.

---

## Performance

Does the change introduce unnecessary complexity or inefficiency?

Optimize where it matters.

Avoid premature optimization.

---

## Security

Does the implementation introduce unnecessary risk?

Protect user data.

Validate inputs.

Handle sensitive information responsibly.

---

## Testing

Have appropriate validation and tests been added or updated?

Confidence should increase with every meaningful change.

---

## Documentation

If the change affects behavior, architecture, or public interfaces, has the documentation been updated?

Future teammates depend on today's documentation.

---

# What Not to Review

Avoid spending review time on issues that automated tools can reliably detect.

Examples include:

- Formatting
- Indentation
- Import ordering
- Linting violations
- Generated code
- Minor stylistic preferences already covered by standards

Automation should handle repetitive checks.

Human reviews should focus on thoughtful engineering.

---

# Giving Feedback

Good feedback is respectful, constructive, and educational.

Prefer:

> Could we simplify this?

Instead of:

> This is wrong.

Prefer:

> Can you explain why this approach was chosen?

Instead of:

> This should be rewritten.

Good questions often create better discussions than immediate solutions.

---

# Receiving Feedback

Receiving feedback is an opportunity to learn.

Assume positive intent.

Explain decisions when necessary.

Accept improvements with openness.

Healthy discussions improve software.

Defensiveness slows improvement.

Remember:

The review is about the solution—not the individual.

---

# Review Checklist

Before approving a change, ask:

✓ Does this solve the intended problem?

✓ Is the solution easy to understand?

✓ Is the implementation as simple as possible?

✓ Does it align with our architecture?

✓ Does it preserve accessibility?

✓ Does it maintain security?

✓ Are appropriate tests included?

✓ Is documentation updated where necessary?

✓ Would I feel comfortable maintaining this code six months from now?

If yes,

the change is ready to approve.

---

# The Butterfly Test 🦋

Before approving any review, ask:

✓ Did this review improve the software?

✓ Did it help another engineer learn?

✓ Did it increase confidence?

✓ Was feedback respectful and constructive?

✓ Did it strengthen long-term maintainability?

✓ Would this discussion help a future teammate understand the decision?

If yes,

the review fulfilled its purpose.

---

# Closing Statement

Code reviews are not checkpoints.

They are conversations.

Every thoughtful question increases understanding.

Every respectful suggestion improves quality.

Every shared insight strengthens the team.

Software is built by individuals.

Great software is built by teams that learn together.

That is the code review philosophy of Project ButterFly.

---

**Document Owner:** Project ButterFly

**Status:** Approved

**Version:** 2.0

**Phase:** Standards

**Approved By:** Founder

**Last Updated:** 25 July 2026

**Next Review:** Every six months or whenever engineering practices evolve.

---

> Build with Purpose.
>
> Design with Empathy.
>
> Engineer with Excellence.
>
> — Project ButterFly 🦋