---
layout: essay
type: essay
title: "Tyrannicsaurus Wrecks"
# All dates must be YYYY-MM-DD format!
date: 2025-10-22
published: true
labels:
  - Coding Standards
  - The Good
  - The Bad
  - The Ugly
---

Coding standards are the rules an entity (business, professor, agency, etc.) implement for a variety of reasons. These might be ease of readability, compiler limitations, safety, or personal preference. It may be something of an exaggeration, but the variety in entities, languages, and the reasons espoused result in nearly as many coding standards as there are coders. Worse, many of these standards may be redundant, contradictory, not aligned with industry best practices, or simply unnecessary.

## "In law, nothing is certain but the expense." -Samuel Butler

Disobeying coding standards doesn't typically result in lawyers, but the costs involved are very tangible. If a project's coding standards can take the form of a book rivaling a dictionary in heft, not only will onboarding personnel be incapable of following each and every rule but it cannot be reasonably expected for _senior_ coders to remember each and every rule.

This means time will be consumed by revisions, but where the first revision misses something the second won't, and then the third, ad infinitum. Different teams will have copies of the standard, and they will inevitably fail to stay up to date. Reviewers will misremember rules, or not be informed of changes, and yet more time will be wasted proving they are wrong. These reviewers will _definitely_ take being proven wrong well and _definitely_ won't be spiteful in finding irrelevant "problems" to send projects back for correction.

These are all situations encountered regularly in the Navy, if perhaps not coding specific. Perhaps the most direct comparison is the Quality Assurance (QA) program for maintenance. Safety critical systems are subject to more strict standards than "mundane" systems, and reasonably so. Sometimes, someone high in the chain of command will be visited by the Good Idea Fairy and think that applying these QA standards to _all_ maintenance is a Good Idea.

Without fail, this Good Idea results in maintenance being backlogged, excessive paperwork being generated, and occasionally even Sailors being punished for not following rules that are _completely unnecessary_ for the situation. Morale tanks, maintainers find ways to forge paperwork or otherwise conceal slipshod work, and the problems the Good Idea was meant to solve end up going septic after festering in the dark.

## Rules Are Written In Blood

On the other hand, many rules are very much necessary, particularly in safety critical systems. There is an interesting article by Gerard J. Holzmann of NASA's Jet Propulsion Laboratory (JPL) titled _The Power of 10: Rules for Developing Safety-Critical Code_[[1]](#1). These ten rules will not be vital to all projects, but provide a basis for projects involving human lives without being excessive in number.

They do not address minutiae such as "no tabs" or "white space between functions," but perhaps such guidelines are superfluous. Perhaps it would be better to simply trust programmers to be competent, and not create rules that anticipate putting an entire program on a single line of code. Outliers exist, but outliers will _always_ exist. Course correct individuals as needed, excise rot where necessary, and keep the actual rules simple.

## Summation

Coding standards are necessary, but they are not necessarily good. In an educational environment, strict standards assist students in developing good habits, in learning best practices, and generally making it simpler for professors and TAs to grade assignments. In the real world, coding standards should be subject to periodic review. When developing a new standard, provide the rationale as we see in Holzmann's article. When the rationale is no longer relevant, archive the standard. When a rationale doesn't make sense, or is extraordinarily mundane, archive the standard. When the standard is due to a bug in the compiler, and the compiler is updated to remove the problem, archive the standard. Twice as much effort should go into pruning branches as goes into adding leaves to keep the tree healthy and functional. Don't wreck everything through tyranny.

## References
<a id="1">[1]</a>
Holzmann, G. J. (2006).
The power of 10: Rules for Developing Safety-Critical Code [Article].
Software Technologies, 1–4. [https://web.eecs.umich.edu/~imarkov/10rules.pdf](https://web.eecs.umich.edu/~imarkov/10rules.pdf)
