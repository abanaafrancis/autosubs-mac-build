# AutoSubs macOS build for DaVinci Resolve 21.2

This repository is used to build an **unsigned, unofficial** AutoSubs 3.11.0-compatible installer for Apple Silicon macOS. It uses community fix [PR #1045](https://github.com/tmoroney/auto-subs/pull/1045), pinned to commit `861dbfb470dfb5d190f7154cd54d393ad560197b`.

## Download
Open **Actions**, select **Build patched AutoSubs for Resolve 21.2 (Mac ARM)**, open the successful run, and download the installer from **Artifacts**. Do not install until the build succeeds and you trust the source.

**Cautions:** unsigned/unnotarized and not officially supported; may trigger macOS security approval. It has not been independently tested. The upstream post-install script modifies user-level Resolve integration and Adobe CEP settings. GitHub's standard hosted runners are free for public repositories.
