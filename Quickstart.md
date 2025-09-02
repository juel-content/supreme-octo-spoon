# Quickstart Guide for tasty

This guide will help you install **tasty**, run your first command, and verify that it works.

Estimated time: **5 minutes**.

---

## Prerequisites

Before installing, make sure you have:

- macOS or Linux computer

- [Homebrew](https://brew.sh/) installed

- Internet connection

> **Windows users:** see [Windows Installation](#windows-installation).

---

## Installation (macOS/Linux)

Open your terminal and run:

```bash

brew install tasty

```

* * * * *

## First Command

-------------

After installation, run:

`tasty init`

Expected output:

`✅ tasty has been successfully installed!`

* * * * *

## Verify Installation 

To confirm tasty is working, run:

`tasty status`

Expected output:

`tasty is running in default mode.`

* * * * *

## Windows Installation

tasty supports Windows via Chocolatey:

`choco install tasty`

Then run the same first command:

`tasty init`

* * * * *

## Troubleshooting

-   **Homebrew error:** If `brew install tasty` fails, ensure Homebrew is installed and updated.

-   **Permission denied:** If `tasty init` returns a permissions error, try:

`sudo tasty init`

-   **Network issues:** Check your internet connection or proxy settings if downloads fail.

* * * * *

## Uninstallation

**macOS/Linux:**

`brew uninstall tasty`

**Windows (Chocolatey):**

`choco uninstall tasty`

* * * * *

## Next Steps


You're ready to start using **tasty**.

This will download and install the latest version of tasty. 

See the User Guide for advanced commands, workflows, and configuration tips.

* * * * *
