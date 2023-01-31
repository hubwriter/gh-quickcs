# gh-quickcs

A GitHub CLI extension that lets you quickly create a new codespace for a preconfigured repository.

Before using this extension, change the value of `REPO` in [the gh-quickcs file](https://github.com/hubwriter/quickcs/blob/main/gh-doccs) to the URL `OWNER/REPO-NAME` of your repo - for example:

```
REPO="your-name/your-repo"
```

You can also change any of the other settings for the codespace in that file.

## 📦 Installation

1. If you haven't already, install the `gh` CLI - see the [installation](https://github.com/cli/cli#installation)

   _Installation requires a minimum version (2.0.0) of the the GitHub CLI that supports extensions._

1. bls:

   ```shell{:copy}
   gh ext install https://github.com/hubwriter/gh-quickcs
   ```

## ⚡️ Usage

Run
```sh
gh quickcs
```
Then enter a display name for the codespace. Don't use quote marks around the name. The name can include spaces and hyphens.

For example:<br>
<img width="514" alt="image" src="https://user-images.githubusercontent.com/54933897/214870852-ea3e1845-2122-45e1-8df4-b9d23a411cd5.png">

<img width="600" alt="image" src="https://user-images.githubusercontent.com/54933897/214872075-4ce2bb50-12ed-4c49-b8a3-d857a13baf37.png">


   ```
