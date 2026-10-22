# Git laboratory submission

All required non-bonus tasks from `Л_р_Git.docx` are represented in this local project.

## Calculator

`main.py` asks for two integers and prints their difference. Earlier commits show the starter program, integer input, and addition before the operation was changed to subtraction. With input `7` and `5`, the final program prints `Difference: 2`.

Run it with `python main.py`.

## Git work completed

- Created the `vova` working branch and pushed it to `origin`.
- Added the starter source, input prompts, `.gitignore`, and arithmetic operation in separate commits.
- Viewed the commit history with `git log --oneline --graph --all --decorate`.
- Compared the first and third program commits with `git diff 86ff0e9 e1d534d`.
- Represented the remote-side change in a second clone: changed addition to subtraction, committed and pushed it, then fast-forwarded the working branch.
- Merged `vova` into `master` and pushed `master`.
- Built both requested commit graph outcomes: a merge result on `diagram-merge`, and the rebased linear history on `diagram-rebase`.
- Added two separate files in one commit (`D6`) on `diagram-rebase` to demonstrate combining two changes as one commit.

## Graph results

Merge:

```text
D1---D2---D3------M
      \\           /
       D4---D5---/
```

Rebase (before the combined follow-up commit):

```text
D1---D2---D3---D4'---D5'
```

The demo changes touch separate files, so these required graph operations complete without conflicts.

## Remote and scope

No GitHub/GitLab URL or existing local repository was available on the laptop. `origin` is therefore a local bare repository at `../remote.git`, and a second local clone represents the server-side edit. No files were published to an unspecified account.

Skipped only the explicitly bonus-marked comparison of conflicting and non-conflicting `C3`/`C5` changes and the separate asterisk-marked final graph exercise.

The branch name `vova` uses the Windows profile name because the lab file does not provide a surname or initials.
