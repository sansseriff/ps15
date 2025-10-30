# ps15

Brief description: Replace this paragraph with a short overview of your dataset and experiment goals. Include links to data sources if public, and summarize the key questions you answer.

## Quick install

<!-- QUICK_INSTALL_START -->

Run one of these commands in a terminal to clone and set up the project (requires that git is installed):

⚠️ Warning: Only use single line installers like these if you trust the creator of this repository. 

macOS/Linux (curl):

```zsh
curl -fsSL https://sansseriff.github.io/ps15/dl.sh | bash
```

macOS/Linux (wget):

```zsh
wget -qO- https://sansseriff.github.io/ps15/dl.sh | bash
```

Windows (PowerShell):

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -Command "iwr -UseBasicParsing https://sansseriff.github.io/ps15/dl.ps1 | iex"
```

### Security: Verify before running

To verify the integrity of `dl.sh` before running it:

```zsh
# Download the script without executing
curl -o dl.sh https://raw.githubusercontent.com/sansseriff/ps15/main/dl.sh

# Verify SHA256 hash matches the one below
shasum -a 256 dl.sh

# Inspect the script content
cat dl.sh

# Inspect what will be installed
curl -s https://raw.githubusercontent.com/sansseriff/ps15/main/dl-util/install_and_sync.sh | less

# If everything looks good, run it
sh dl.sh
```

Integrity (SHA256 of dl.sh):

```text
1182e4048ea67aa872bae8c1fde10eb31ac8e442328c554c2793936f5281f23f
```

<!-- QUICK_INSTALL_END -->

## Project notes

- Data: Describe where data comes from and any preprocessing requirements.
- Experiment: Outline the main analysis/experiment steps and expected outputs.
- Environment: Dependencies are managed with uv (see dl-util/install_and_sync.sh for details).

## Next steps

- Edit this README to document your specific analysis.
- See the original template guide in README.template.md for advanced usage and maintenance tips.
- Optionally delete the template_images/ folder in dl-util/ and the README.template.md. (but don't delete other files in dl-util/)
