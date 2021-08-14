# Espanso Configuration

## Summary

[Espanso](https://espanso.org/) is a fantastic, cross-platform text-expander.

I have a number of custom Espanso configurations in the `user/` directory.

- `user/email.yml`
    - Common email phrases.
- `user/log.yml`
    - Stuff for my personal log (personal journal, knowledge base, wiki).
- `user/markdown.yml`
    - Markdown syntax.
- `user/misc.yml`
    - Anything that doesn't fit in the above.

## Install

After cloning the repository, follow the two steps below to install.

```sh
# Remove existing config user directory:
rm --recursive --force /home/jprice.config/espanso/user

# Create symbolic link from repository to config directory:
ln --symbolic <path-to-repo>/espanso/user /home/jprice/.config/espanso/user
```
