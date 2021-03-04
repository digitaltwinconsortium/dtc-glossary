# dtc-glossary

> A repository for collaboration on a [glossary of digital twins and digital twin technology](glossary.md) from the [Digital Twin Consortium](https://www.digitaltwinconsortium.org/).

## Criteria for including terms

Sometimes less is more. Some relevant questions to ask about a candidate term include:

- Does the term *add value* in the form of clarification or context that is not available in a common dictionary?
- Does the term provide a place to reference other DTC-defined content?
- Does the term *solve a terminology problem* for the author of a digital twin use case or some other product of the DTC?
- Is the term *industry-specific*?
  - The [glossary](glossary.md) is not intended to cover industry-specific domains for which one might build a digital twin system.
  - For example “bridge abutment”, “rotator cuff”, “supply chain”, “financial asset”, etc. probably belong in a different glossary.
- Is the term *implementation-specific*?
  - This glossary is not the place to describe the terms of a particular implementation approach.
  - We may have entries for types of technology relevant to digital twins, and those entries may list (and link to) specific examples.
- Does the definition *apply across all industry domains*?
- Is the term really *necessary*? What problems would be caused if it were omitted?

## Template for new entries

Authors of new entries should create them in alphabetical order using the template below and update the [Table of Contents](glossary.md#table-of-contents). Only the formal definition following the template `> A {term} is a [{broader term}](#broader-term) that {differentiating clause}.` is required--other content is optional.

```markdown

## {Term}

> A {term} is a [{broader term}](#broader-term) that {differentiating clause}.

{Elaboration. In other words... Analogous to...}

{Examples... Examples include...}

{Counter-Examples... ____ is not a {term}}

{Motivation. Why {term} is important for digital twins...}

{Pictures: ![name of picture](images\PreferredTerm.png) }

***Alternate terms***

- [{synonym term}](#synonym-term) {Explanation of synonym}
- [{non-term}](#non-preferred-term) {Explanation of why it is not preferred}

***Narrower terms***

- [{narrower term 1}(#narrower-term-1)]
- [{narrower term 2}(#narrower-term-2)]

***Related terms***

- A {term} {relational verb phrase} a {related term}.
- A {term} {relational verb phrase} a {related term}.

*Back to the (Table of Contents)(#Table-of-Contents)

---
```

### Formal Definition

The formal definition should be a complete sentence following the template

`> A {term} is a [{broader term}](#broader-term) that {differentiating clause}.`

For example

`> A kangaroo is a marsupial that lives in Australia, hops, and is a good boxer.` 

(but create a hyperlink to "marsupial" if it is defined elsewhere in the glossary.)

### Context

This section includes elaboration, examples, counter-examples, motivations, pictures and clarifies the meaning and usage of the term.

### Alternate Terms

These can use complete sentences to indicate if the alternate term is non-preferred or to explain the context in which the synonym is commonly used. If there is an entry for the alternate term, link to it.

### Narrower Terms

These are hyperlinks to entries "lower" in the taxonomic hierarchy. For example, the entry for "kangaroo" might list the "narrower" terms: "red kangaroo", "eastern grey kangaroo", "western grey kangaroo", and "antilopine kangaroo".

### Related Terms

These should be complete sentences that describe how the {term} relates to some other term. For example:

```markdown
- A digital twin is implemented in a [digital twin system](#digital-twin-system).
- A digital twin has a corresponding [physical twin](#physical-twin).
- A digital twin is part of a [cyber-physical system](#cyber-physical-system).
```

### Non-Preferred Term

You may include entries for non-terms or synonyms simply as a place to link back to the primary entry.

```markdown

## {Non-Preferred Term}

Use [{term}(#term)] instead.

*Back to the (Table of Contents)(#Table-of-Contents)

---
```
