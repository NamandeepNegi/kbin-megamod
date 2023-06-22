# Adding a script

1. Add the script to the /mods directory
2. Add the script's absolute path to the includes (`@require`)
3. Update the arrays in the preamble with user-facing strings
- `mmLabels` array contains the human-readable feature labels
- `mmDescs` contains the human-readable feature descriptions
4. Set the mod classname and entry point
- `mmFuncs` contains a unique identifier used as a classname when injecting the checklists into the DOM
- `funcObj` contains a mapping from the classname to the script's entry point function
5. Add necessary @grants to megamod.user.js
6. Submit a PR

# Specifications

- Prefer 4 space indentation
- Prefer [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)
- Script entry point must accept a boolean toggle (true = setup, false = teardown)


# TODO
- Contributors
- Update this README
- JSON manifest

