# Imported AI projects

This repository contains local snapshots of eight upstream projects selected for later use.

## Syrtsovk Toolkit snapshot

Upstream: https://github.com/syrtsovk/Syrtsovk_toolkit
Commit: `fec121592c6b65703d58d37385e2d3ac0649a3df`
Commit date: `2026-09-08T18:34:26+03:00`

Imported projects:
1. `competitor-intel`
2. `plugins/vibecheck`
3. `skills/pluginmaker`
4. `skills/humanvoice`
5. `skills/task-arena`
6. `skills/kp-writer`
7. `skills/promptmaker`

Original MIT license and NOTICE are preserved under `vendor/syrtsovk-toolkit/`.

## Compound Writing snapshot

Upstream: https://github.com/EveryInc/compound-writing
Commit: `18702f0ece9f2b852e305807e0271b2d550d9b4b`
Commit date: `2026-08-27T15:49:32-04:00`

The complete working tree is preserved under `vendor/compound-writing/`; only Git's internal `.git` database is excluded so it can live inside this repository normally. Its upstream license files are preserved in place.

## Updating

Run the GitHub Actions workflow **Import and sync AI projects** manually. It re-clones both upstream repositories and refreshes the local snapshots.
