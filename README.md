# Ryan's Dotfiles

Managed by [chezmoi](https://www.chezmoi.io)

## Setup dotfiles on a new machine

  1. Install chezmoi to `~/bin`.
      - https://github.com/twpayne/chezmoi/blob/master/docs/INSTALL.md
     ```
     $ brew install chezmoi
     ```

  2. Initialize chezmoi. Use `https` since we don't have creds yet.
     ```
     $ chezmoi init https://github.com/ryanrs-chang/dotfiles
     ```

  3. (Optional) Check the diff.
     ```
     $ chezmoi apply -nv
     ```

  4. Install the dotfiles.
     ```
     $ chezmoi apply
     ```

Done! To keep up to date in the future:

```
$ chezmoi update
```
