# CLAUDE.md

## Hard Rules — DO NOT VIOLATE

### Git Identity (this repo)

- user.name: suteny0r
- user.email: suteny0r@gmail.com
- Fork remote: https://github.com/suteny0r/Remote-ID-Spoofer

### Never push to upstream

- This is a fork. `upstream` points to the original repo (`colonelpanichacks/Remote-ID-Spoofer`) which we do **not** have write access to.
- **ALWAYS** push to `fork` (e.g., `git push fork master`), **NEVER** to `upstream`.
- The `upstream` push URL is intentionally set to a bogus value to prevent accidental pushes.
- When creating PRs, push the branch to `fork` first, then open the PR against upstream.

## Project Overview

Remote-ID-Spoofer is ESP32-based firmware that generates FAA Remote ID (Open Drone ID / ASTM F3411) beacon frames. It has single drone and swarm modes. Used for security research and testing drone detection systems like SKY-SPY-Aware.
