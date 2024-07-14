# julia-lavapipe

Action used to install the Lavapipe Vulkan drivers from Mesa using APT on Ubuntu runners.

**This action supports Ubuntu runners only at the moment.**

Example usage:

```yaml
uses: serenity4/julia-lavapipe@latest
```

```yaml
uses: serenity4/julia-lavapipe@latest
with:
  debug: "true" # defaults to "false"
```
