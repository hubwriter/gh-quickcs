# gh-quickcs

A GitHub CLI extension that lets you quickly create a new codespace for a preconfigured repository.

## 📦 Installation

1. If you haven't already, install the `gh` CLI - see the [installation](https://github.com/cli/cli#installation)

   _Installation requires a minimum version (2.0.0) of the the GitHub CLI that supports extensions._

1. Use the GitHub CLI to install the extension:

   ```
   gh ext install hubwriter/gh-quickcs
   
   Cloning into '/Users/yourname/.local/share/gh/extensions/gh-quickcs'...
   remote: Enumerating objects: 35, done.
   remote: Counting objects: 100% (35/35), done.
   remote: Compressing objects: 100% (30/30), done.
   remote: Total 35 (delta 6), reused 24 (delta 3), pack-reused 0
   Receiving objects: 100% (35/35), 9.65 KiB | 4.83 MiB/s, done.
   Resolving deltas: 100% (6/6), done.
   ✓ Installed extension hubwriter/gh-quickcs
   ```

## ⚡️ Usage

1. Run

   ```sh
   gh quickcs
   ```

1. _On first run only:_ The first time you use the extension it will ask you to input configuration options. This is a one-time operation. The values you enter are stored in `~/.gh-quickcs.cfg`. You can edit this file if you need to change the values, but the rationale of this script is that you want to create the same kind of codespace for the same repository, so you won't need to change these values once you've set them.
1. Enter a display name for the codespace you want to create. Don't use quote marks around the name. The name can include spaces and hyphens.
1. _Optionally (depending on your configuration settings):_ Enter the name of a new branch you want to create, or press Enter to use the default branch.

For example:<br>
<img width="1057" alt="image" src="https://user-images.githubusercontent.com/54933897/216063640-2d773aae-595e-45c2-9f07-05ce256dc50c.png">

<img width="580" alt="image" src="https://user-images.githubusercontent.com/54933897/216062894-b88986a4-39e8-49ea-969c-93704c81c8d6.png">

## ⭐ If you like it, star it!

If you like this CLI extension, please star the repo by clicking **☆ Star** top right of this page.

This helps raise the profile of this extension. Thanks.
