# Quickstart Guide for MyTool

This guide will help you install **MyTool**, run your first command, and verify that it works.

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

brew install mytool

```

* * * * *

## First Command

-------------

After installation, run:

`mytool init`

Expected output:

`✅ MyTool has been successfully installed!`

* * * * *

** Verify Installation 

-------------------

To confirm MyTool is working, run:

`mytool status`

Expected output:

`MyTool is running in default mode.`

* * * * *

## Windows Installation

MyTool supports Windows via Chocolatey:

`choco install mytool`

Then run the same first command:

`mytool init`

* * * * *

## Troubleshooting

---------------

-   **Homebrew error:** If `brew install mytool` fails, ensure Homebrew is installed and updated.

-   **Permission denied:** If `mytool init` returns a permissions error, try:

`sudo mytool init`

-   **Network issues:** Check your internet connection or proxy settings if downloads fail.

* * * * *

## Uninstallation

--------------

**macOS/Linux:**

`brew uninstall mytool`

**Windows (Chocolatey):**

`choco uninstall mytool`

* * * * *

## Next Steps

----------

You're ready to start using **MyTool**.

This will download and install the latest version of MyTool. 

See the User Guide for advanced commands, workflows, and configuration tips.

* * * * *
