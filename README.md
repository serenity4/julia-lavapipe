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

## Contributions

We warmly welcome contributions, and in particular to add support to Windows/MacOS and other Linux distributions.

For Windows, we could probably use https://github.com/pal1000/mesa-dist-win and extract the files in the right places to have the driver detected by a Vulkan loader.
