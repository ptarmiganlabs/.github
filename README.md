# .github

Default community health files for the repositories of
[Ptarmigan Labs](https://github.com/ptarmiganlabs).

GitHub uses a file here for every repository in the organisation that has no file of that type of
its own. Nothing is copied into the individual repositories, and the defaults do not appear in
their file browsers or clones.

| File | Used by |
| --- | --- |
| [pull_request_template.md](pull_request_template.md) | Every repository without a pull request template of its own. |

## Overriding the default in one repository

Add `.github/pull_request_template.md` to that repository's default branch. It replaces this one
whole: nothing is inherited, and later changes here do not reach it. So start from a copy of this
one and add to it, and keep the comment about the pull request title.

## Changing this repository

**It is public, because GitHub serves defaults only from a public `.github` repository.** The
defaults apply to private repositories too, but anyone can read the files themselves. Nothing
internal goes in here: no hostnames, customer names, private repository names or unannounced
products.

`pull_request_template.md` is published from the organisation's internal rules, where it is
reviewed alongside the reasons for each part of it. Change it there first and copy it here
unchanged, so the two stay identical.

Keep one copy of each file, at the root. GitHub looks in a `.github/` folder before the root, so a
second copy added there would silently become the one served.
