# Git laboratory submission

All required non-bonus tasks from `Л_р_Git.docx` are represented in this local project.

## Calculator

`main.py` asks for two integers and prints their difference. Earlier commits show the starter program, integer input, and addition. Commit `C5` changed the operation to subtraction. Commit `C6` briefly changed it back to addition, and commit `C7`, made through GitHub's web editor, restored subtraction. With input `7` and `5`, the final program prints `Difference: 2`.

Run it with `python main.py`.

## Git work completed

- Created the `vova` working branch and pushed it to `origin`.
- Added the starter source, input prompts, `.gitignore`, and arithmetic operation in separate commits.
- Viewed the commit history with `git log --oneline --graph --all --decorate`.
- Compared the first and third program commits with `git diff 86ff0e9 e1d534d`.
- Changed the operation to subtraction in a second clone and pushed it as `C5`.
- Edited `main.py` in GitHub's web interface in `C6`, changed subtraction back to addition, synchronized `vova`, and merged it into `master`.
- Matched the final subtraction behavior on `vova` in the GitHub web editor as `C7`, synchronized it locally, and merged it into `master`.
- Built both requested commit graph outcomes: a merge result on `diagram-merge`, and the rebased linear history on `diagram-rebase`.
- Added two separate files in one commit (`D6`) on `diagram-rebase` to demonstrate combining two changes as one commit.

## Graph results

Merge:

```text
D1---D2---D3------M
      \           /
       D4---D5---/
```

Rebase (before the combined follow-up commit):

```text
D1---D2---D3---D4'---D5'
```

The demo changes touch separate files, so these required graph operations complete without conflicts.

## Remote and scope

The public GitHub repository is `https://github.com/vladimirprotopopov581-netizen/git-lab-vova`. The branch `vova` is the working branch. A second clone was used for the remote-side change before the local branch was synchronized.

The required graph tasks are shown on `diagram-merge` and `diagram-rebase`. The non-conflicting commit graph is used; the explicitly marked bonus comparison of conflicting and non-conflicting `C3`/`C5` changes and the separate asterisk-marked final graph exercise are skipped.

The branch name `vova` follows the Windows profile name because the lab file does not provide a surname or initials.
