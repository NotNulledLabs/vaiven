# Working on Vaivén

Vaivén is a translation engine that runs as Claude project instructions. There is
no code, no build step and nothing to run. The deliverable is the text itself.

## The three files must agree
VAIVEN.txt is the source of truth: it defines every command, extra and rule.
README.md and README.es.md document it for humans.
Any change to a command, an extra or a behaviour must be reflected in all three.
The two READMEs must stay equivalent in content, not translated word for word.

## Conventions
Never use em dashes or en dashes anywhere. Use commas, full stops or brackets.
Wrap at roughly 80 characters.
Engine text is written for Claude to follow: short imperative rules, no essays.
README text is written for non-technical readers.

## Before finishing any change
Check that commands and extras in VAIVEN.txt match the tables in both READMEs.
Check that no rule contradicts another, especially around which way a message
gets translated.
