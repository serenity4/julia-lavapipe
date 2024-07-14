# julia-lavapipe

Action used to install the Lavapipe Vulkan driver from Mesa using APT on Ubuntu runners.

**This action only supports Ubuntu runners at the moment.**

Example usage:

```yaml
uses: serenity4/julia-lavapipe@latest
```

```yaml
uses: serenity4/julia-lavapipe@latest
with:
  debug: "true" # defaults to "false"
```
