<p align="center">
   <img alt="CienciaENaturaLogo" src="https://dl.dropboxusercontent.com/s/2y3obtp1dcg0h0ub3mab6/logo-ciencia-e-natura.jpg?rlkey=77vnaywv3t5oydoiqclnfu736&dl=0" width="70%">
    <br>
    <img alt="Issues" src="https://img.shields.io/github/issues/lobophf/conway-game-of-life.svg">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/centraldeperiodicos/template_tex_ciencia_e_natura">
    <img alt="License" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0%20Deed-brightgreen"><br>
    <a href="README.md">:us: English</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;
    <a href="README-pt-br.md">:brazil: Português</a>&nbsp;&nbsp;&nbsp;
    <br> 
    <a href="#about">About</a>&nbsp;&nbsp;|&nbsp;
    <a href="#requirements">Requirements</a>&nbsp;&nbsp;|&nbsp;
    <a href="#submission">Submission</a>&nbsp;&nbsp;|&nbsp;
    <a href="#license">License</a>	
    <h2 align="center">Ciência e Natura - LaTeX Repository</h2>
    <h4 align="center">Federal University of Santa Maria, Main Campus, Central Publishing Office at UFSM</h4>
</p>

## About:
This repository contains the `LaTeX` version of essential files needed for the submission process to the [Ciência e Natura journal](https://periodicos.ufsm.br/cienciaenatura/).

## For authors:

For those who will submit a paper to our journal, please read the [guidelines](https://periodicos.ufsm.br/cienciaenatura/about/submissions) and download the essential files by clicking [here](www.pudim.com.br).

### Requirements:

If you want to create your paper on your local machine, you must have `TeX Live 2022` or newer installed. However, this requirement does not apply if you want to use the [Overleaf](https://www.overleaf.com/) platform.

### Compiling the PDF:

To compile the PDF on local machines in any Operating System, use the following command. This can be done directly in the terminal/command prompt, or by configuring your LaTex editor for this.
```
$ latexmk -pdf paper.tex
```
If you prefer to use [Overleaf](https://www.overleaf.com), upload all files from this repository along with the downloaded ones and compile the PDF using their platform's cloud service.

Whichever method you choose, if everything works well, the `paper.pdf` file will be available.
From now on, all you have to do is edit the files to create your own version of the paper by compiling as many times you want.

### Submission:
Before proceeding with submission, please review our [Submission Preparation Checklist](https://periodicos.ufsm.br/cienciaenatura/about/submissions) and provide all required files on our platform, including the generated PDF file.

Also, consider running the following command to remove unnecessary files before uploading to our platform. Keep in mind many of these log or auxiliary files are only useful during the project editing phase.
```
$ latexmk -c
```

## For developers, maintainers and contributors:

We appreciate any type of contributions! If you want to improve the documentation or fix bugs, do so without any further discussion by opening a pull request on the develop branch. You can also check our contribution page.

However if you plan to contribute by adding new features, changing the template, please first open an issue and discuss it with us. Sending other types of pull requests without prior discussion may end up in rejection if we decide to take the project in another direction than you might be aware of.

## License:
This project is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/), as found in the [LICENSE](./LICENSE) file.
