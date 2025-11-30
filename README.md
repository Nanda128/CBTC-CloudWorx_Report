# Context Beyond The Code

This repository contains the LaTeX source code for my report going into the context behind the CloudWorx project.
It has an automatic build system using GitHub Actions to compile the LaTeX into a PDF whenever changes are pushed to the repository.

The main text of the report is in `src/main.tex`, with the .xlsx file stored in `src/23070854-CloudWorx-User Stories.xlsx`.
It'll compile and deploy to to https://github.com/Nanda128/CBTC-CloudWorx_Report/releases.

Check out `.github/workflows/build-CBTC.yml` for the build configuration.
Part of this implementation was taken from my FYP, available at https://github.com/Nanda128/Final-Year-Project

## Why did you use TeX?

- Easier to version control across my different devices.
- Looks really formal and is less sensitive to formatting issues compared to Word.

## How to Build Locally

1. Install a TeX distribution:
   - For Windows, you can use [MiKTeX](https://miktex.org/download).
   - For macOS, you can use [MacTeX](https://tug.org/mactex/).
   - For Linux, you can install TeX Live via your package manager (e.g., `sudo apt-get install texlive-full` for Debian-based systems).
   - Alternatively, you can use an online LaTeX editor like [Overleaf](https://www.overleaf.com/) to compile the document without installing anything locally.
2. Clone this repository to your local machine.
3. Open a terminal and navigate to the repository directory.
4. Navigate to `src/scripts` and run either `build_latex.ps1` or `build_latex.sh` depending on your operating system.

(Run PowerShell (.ps1) script on Windows, or Bash (.sh) script on Linux/macOS)

Check your `out` folder for the compiled PDF.
