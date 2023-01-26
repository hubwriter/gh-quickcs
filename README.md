# gh-doccs

A GitHub CLI extension to create a new codespace for docs work.

This extension creates a codespaces from the docs-internal repository (assuming you have access to it), and then opens the codespace so that you can start using it.

"doccs" = docs codespace



## 📦 Installation

1. If you haven't already, install the `gh` CLI - see the [installation](https://github.com/cli/cli#installation)

   _Installation requires a minimum version (2.0.0) of the the GitHub CLI that supports extensions._

1. Clone the repo by running either of these commands from the directory that you want to be the parent of your local copy of the repo:

   ```bash
   # git
   git clone https://github.com/hubwriter/gh-doccs

   # GitHub CLI
   gh repo clone hubwriter/gh-doccs
   ```

1. cd into it

   ```bash
   cd gh-doccs
   ```

1. Install it locally
   ```bash
   gh extension install .
   ```


## ⚡️ Usage

Run
```sh
gh doccs
```
Then enter a display name for the codespace. Don't use quote marks around the name. The name can include spaces and hyphens.

