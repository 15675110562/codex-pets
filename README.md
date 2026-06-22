# Codex Pets

This repository contains two ready-to-use Codex desktop pets:

- `pets/yinyue`
- `pets/Q版银月`

Each pet folder contains:

- `pet.json`
- `spritesheet.webp`

## Install

Copy the pet folder you want into your Codex pets directory:

```powershell
Copy-Item -Recurse -Force ".\pets\yinyue" "$env:USERPROFILE\.codex\pets\yinyue"
Copy-Item -Recurse -Force ".\pets\Q版银月" "$env:USERPROFILE\.codex\pets\Q版银月"
```

After copying, restart Codex or reload the pet list if needed.

## Notes

These are generated desktop pet assets. They are stored here so they can be reused without regenerating the spritesheets.
