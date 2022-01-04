# Espanso Configuration

## Summary

[Espanso](https://espanso.org/) is a fantastic, cross-platform text-expander.

I have a number of custom Espanso configurations in the `user/` directory.

| File           | Description                                 |
|----------------|---------------------------------------------|
| `email.yml`    | Common email phrases                        |
| `log.yml`      | Personal log (wiki/knowledge base) snippets |
| `markdown.yml` | Markdown syntax                             |
| `misc.yml`     | Everything else                             |


## Install

After cloning the repository, follow the two steps below to install.

### Linux

```sh
# Remove existing config user directory:
rm --recursive --force /home/<username>/config/espanso/user

# Create symbolic link from repository to config directory:
ln --symbolic <path-to-repo>/espanso/user /home/<username>/.config/espanso/user
```

### MacOS

```sh
# Remove existing config user directory:
rm --recursive --force /Users/<username>/Library/Preferences/espanso/user

# Create symbolic link from repository to config directory:
ln --symbolic <path-to-repo>/espanso/user /Users/<username>/Library/Preferences/espanso/user
```
