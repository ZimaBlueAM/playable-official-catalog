# Signed Web Game Releases

This directory contains immutable, first-party Playable Web game packages and
their independently signed index. The iOS app verifies the bundled P-256 trust
root, exact package content address, package signature, compatibility, review
metadata and resource budget before activation.

Private signing keys are never stored in this repository. Upload package files
before atomically replacing `index.json`; an existing match remains pinned to
its exact content address.
