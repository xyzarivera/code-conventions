# Xyza's Coding Conventions

This guide is here to help keep my code clean, consistent, and easy to read.

## Checklist

The TL;DR of the do's and dont's. Questions to ask before requesting for code reviews or refactoring code.

- [ ] Do you have truthy or falsy checks?
    - Use direct comparisons 
- [ ] Do you have "Magic Numbers/Strings"?
    - Assign them to a descriptive variable name
- [ ] Do you have `&&` or `||` operators? 
    - Check if `??` can be used instead

## Do's

- DRY. Prefer inline code, especially when code is used once.
- Create variables when:
    - code is used multiple times
    - descriptive naming for literal values. `const PI = 3.14`
- Prefer to use nullish coelescing `??` over short-circuit AND operator `&&` and OR operator `||` 

## Dont's

- No truthy and falsy checks.