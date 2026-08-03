# Install in the profile repository

Copy this package into the root of the GitHub profile repository named `yassshhhh22`.
Keep the existing `assets/kakashi.gif` file and the existing Pac-Man workflow/output branch.

Expected structure:

```text
README.md
stats.svg
streak.svg
langs.svg
hd-about.svg
hd-stack.svg
hd-projects.svg
hd-stats.svg
assets/kakashi.gif
scripts/generate_stats.py
scripts/fonts/...
.github/workflows/stats.yml
```

Commit and push the package. The stats workflow is configured to run when its setup files are first pushed, once per day, and manually.

If the first run does not start, open the repository's Actions tab and run `refresh profile stats` manually.

If the workflow reaches the commit step but cannot push, check the repository's Actions workflow permissions and allow the workflow token to write repository contents.
