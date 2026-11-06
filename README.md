# build-aseprite

GitHub Actions workflow for building Aseprite on Windows and Linux.

## Use the workflow

1. Fork this repository to your GitHub account.
2. In your fork, open **Actions** and select the **Aseprite** workflow.
3. Click **Run workflow**, select the `main` branch, then confirm.
4. When the run finishes, download the ZIP for your platform from the release created in your fork.
5. After downloading, delete that release and its assets. Do not redistribute the compiled binaries. Ensure your use complies with Aseprite's [license and terms](https://www.aseprite.org/faq/#license).

The workflow also runs when `BuildLog.md` is pushed to the `main` branch.

## Disclaimer

This project is not affiliated with or endorsed by Aseprite or its developers. The contents of this repository are licensed under the [MIT License](LICENSE); that license does not apply to Aseprite or grant rights to its software. You are responsible for complying with Aseprite's terms.
