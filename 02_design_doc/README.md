# Design Doc

## W skrócie

- Przykłady: [lyft](https://eng.lyft.com/awesome-tech-specs-86eea8e45bb9) i [bardziej rozbudowany](https://adityarohilla.com/2022/03/22/the-system-design-template-i-use/);
- Podobnie jak proces prowadzenia projektu w firmie, Design Doc rownież ewoluuje;
- Warto zacząć od prostszego formatu w Google Docs, a później iteratywnie poprawiać;
- do pary z UX/UI designem czy mockupami.

## Przykład - 20231011-funkcjonalnosc-xyz

W waszym repozytorium `docs/YYYYMMDD_design_doc.md` lub `docs/design_doc.md`:

```
**Tytuł**

Author: Joanna Kowalska
Created at:

## Intro

*Why/Problem*

*How*

*What*

...

## Goals and Non-Goals

...

## Proposed solution

Starting with high-level design, arch diagrams, screenshots, mockups,...

...

You might here also touch things, such as testing.

## Other options

Discarded alternatives.

...

## Open Questions

...

## References

```

## Możliwe dodatkowe elementy

- informacje dotyczące UX/UI design, linki do kolejnych odsłon designu,
- Decision Log - w pierwszych iteracjach można wykorzystać do tego design doc zamiast osobny [ADRów](https://github.com/joelparkerhenderson/architecture-decision-record?ref=the-pragmatic-engineer).

## Warto przeczytać

- https://blog.pragmaticengineer.com/scaling-engineering-teams-via-writing-things-down-rfcs/
- https://www.industrialempathy.com/posts/design-docs-at-google/
