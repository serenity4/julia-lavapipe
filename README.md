# julia-lavapipe

Action used to install the Lavapipe Vulkan driver from Mesa using APT on Ubuntu runners.

**This action only supports Ubuntu runners at the moment.**

Example usage:

```yaml
uses: serenity4/julia-lavapipe@v1
```

```yaml
uses: serenity4/julia-lavapipe@v1
with:
  debug: "true" # defaults to "false"
  validation: "false" # defaults to "true"
```
