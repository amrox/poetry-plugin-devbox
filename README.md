# Poetry Plugin Example

This example uses a local Flake to add a plugin to the Poetry runtime.

To get started, run the following:

```
devbox shell
```

---

The key part is the flake.nix in the poetry folder, which uses nix to install the plugin in Poetry. A similar pattern could be used for other poetry plugins.

https://github.com/Lagoja/poetry-plugin-devbox/blob/main/poetry/flake.nix
I confirmed that I could run poetry dynamic-versioning enable once I started devbox shell
