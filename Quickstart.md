# Quickstart Guide for Tasty

This guide will help you install **Tasty**, run your first command, and verify that it works.

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

`Tasty init`

Expected output:

`✅ Tasty has been successfully installed!`

* * * * *

** Verify Installation 

To confirm Tasty is working, run:

`tasty status`

Expected output:

`Tasty is running in default mode.`

* * * * *

## Windows Installation

Tasty supports Windows via Chocolatey:

`choco install Tasty`

Then run the same first command:

`Tasty init`

* * * * *

## Troubleshooting

-   **Homebrew error:** If `brew install Tasty` fails, ensure Homebrew is installed and updated.

-   **Permission denied:** If `Tasty init` returns a permissions error, try:

`sudo Tasty init`

-   **Network issues:** Check your internet connection or proxy settings if downloads fail.

* * * * *

## Uninstallation

**macOS/Linux:**

`brew uninstall Tasty`

**Windows (Chocolatey):**

`choco uninstall Tasty`

* * * * *

## Next Steps


You're ready to start using **Tasty**.

This will download and install the latest version of Tasty. 

See the User Guide for advanced commands, workflows, and configuration tips.

* * * * *
