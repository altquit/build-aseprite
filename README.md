# build-aseprite

GitHub Actions workflow that builds Aseprite for Windows, macOS, and Linux.

## Run the workflow

1. Open the **Actions** tab of this repository.
2. Select the **Aseprite** workflow in the left sidebar.
3. Click **Run workflow**, choose the `main` branch, and click **Run workflow** again to confirm.
4. Open the new workflow run to follow its progress. It builds all three platforms; when complete, open this repository's **Releases** page to download the matching platform ZIP file.

The workflow can also run automatically when `BuildLog.md` is pushed to the `main` branch.

## Important: delete the release after downloading

**Download the build for your own use, then delete the GitHub release and its assets. Do not redistribute the compiled binaries.** Aseprite does not allow distribution of compiled binaries from this repository. Please make sure you have the right to build and use Aseprite, and follow the [Aseprite license and terms](https://www.aseprite.org/faq/#license).
