## Build and run in Intellij IDEA under Windows

- Install `MikTeX`: https://miktex.org/download
- Update `MikTeX`
- Install `SumatraPDF` viewer: https://www.sumatrapdfreader.org/download-free-pdf-viewer
- Path to SumatraPDF: `C:\Program Files\SumatraPDF`
- Install `Intellij IDEA Ultimate`: https://www.jetbrains.com/idea/download/#section=windows
- Activate `Intellij IDEA Ultimate`
- Install `TeXiFy IDEA` plugin: https://plugins.jetbrains.com/plugin/9473-texify-idea
- Clone this repository locally: `https://github.com/kolosovpetro/github-latex-template.git`
- Open `github-latex-template` folder in `Intellij IDEA Ultimate` and configure as follows
    - LaTeX Configuration
      ![LaTeX Configuration](./img/latex_configuration.PNG "LaTeX Configuration")
    - BibTeX Configuration
      ![BibTeX Configuration](./img/bibtex_configuration.PNG "BibTeX Configuration")
- Configure Inverse Search in `Intellij IDEA` for SumatraPDF: `Tools -> LaTeX -> Configure Inverse Search`
- Compile document using `Shift + F10`
