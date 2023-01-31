# gh-quickcs

A GitHub CLI extension that lets you quickly create a new codespace for a preconfigured repository.

After installing this extension, _before you use it,_ change the value of `REPO` in [the gh-quickcs file](https://github.com/hubwriter/quickcs/blob/main/gh-doccs) to the URL `OWNER/REPO-NAME` of your repo - for example:

```
REPO="your-name/your-repo"
```

You can also change any of the other settings for the codespace in that file.

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
   
1. Edit the `/Users/YOURNAME/.local/share/gh/extensions/gh-quickcs` file, changing the value of `REPO` to the owner and name that identifies the repository for which you want to create codespaces - for example: `my-name/my-repo`.

## ⚡️ Usage

Run
```sh
gh quickcs
```
Then enter a display name for the codespace. Don't use quote marks around the name. The name can include spaces and hyphens.

For example:<br>

<img width="567" alt="image" src="https://user-images.githubusercontent.com/54933897/215718987-45e4b2fa-4717-4dc0-a935-ce1498c3465a.png">

<img width="590" alt="image" src="https://user-images.githubusercontent.com/54933897/215719228-ffc3ddc0-4cb8-4c64-9e45-b6f701895277.png">

