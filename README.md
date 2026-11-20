# Bow Variants

**Bow Variants** is a Minecraft Bedrock add-on that adds special bows and arrows:

- **Demolition Bow**: fires explosive arrows that blow up on impact (they don't break blocks).
- **Bow of Levitation**: fires levitation arrows that make whatever they hit float for 10 seconds.

The bow and arrow files are shared with Skeleton Variants (`skeleton-variants`). Edit them there, then run `..\bedrock-tools\sync.ps1` here to copy them across. `sync.json` lists what's shared. Don't install both packs in the same world: they define the same items.

## Building

Use `package.ps1` from [bedrock-tools](https://github.com/TheCoberto/bedrock-tools), cloned next to this repo:

```powershell
powershell -ExecutionPolicy Bypass -File ..\bedrock-tools\package.ps1
```
