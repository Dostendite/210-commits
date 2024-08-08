# Personal commit style guide [WIP]

Hello! This is my personal commit style guide, it is
heavly inspired in the Conventional Commits site I found
thanks to The Odin Project.

These past weeks I've been improving my coding skills
notably, and to level up and celebrate I'd like to introduce
my own system of Git commits.

Feel free to use this guide if you like it!

## Capitalization
Every commit should start with a capital letter,
as well as the message body after it.
**E.g.:** `Fix | Restore colorized terminal output for to_s`

Some types, such as _new_, *debug* and *refactor* already
are verbs in an imperative form, so you can skip having to
add another one in the message body.

## Commit types:
* New / Feature
* Debug / Fix
* Document
* Refactor
* Style
* Performance
* Tests
* Revert / Undo
## Prefixes
*Such as !, !!, ?, etc*
**WIP**

## Separators
I haven't decided on the type of separator I'd like to use
on all my commits yet, but here are some promising ones:

### Colon :
**E.g.:** `Document: All methods for the Navigation module`
### -> Arrow ->
**E.g.:** `Feature -> Add three new skins to the ball game`

## Endings
Maybe add different ending types? Such as _[P]_
if the commit belongs to a feature that is still in progress,
or _[E]_ if that commit is the last one for that current feature.
**WIP**
