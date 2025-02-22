# Electrical and Electronic Circuits Lab 
<h3> Dept. of Electrical and Electronic Engineering <br>
Shahjalal University of Science and Technology, Sylhet </h3>

This repository contains a `.tex` template file for the lab manual of Electrical and Electronic Circuits lab offered by SUST, EEE as a minor course. To modify/add new experiments to the manual 

- Download this repository as a zip file
- Upload the zip file in [overleaf](https://www.overleaf.com/)
- In overleaf interface `main.tex` files will contain all the packages that we'll need and the inputs. The `references.bib` file will contain all the references that we'll use in the documents. The `files` folder contains all the experiment files and the `img` folder contains all the images used in this document.
- If you want to add a new experiment, create a new `expn.tex` file inside the `file` folder. This `expn.tex` file will contain a `\section` part (which will be the experiment's name), a `addcontentsline` part (which will add the experiments name to the table of contents), some `\subsections` will contain the headings inside each experiment and at last there will be a `\newpage` command to end this experiment and create a new page for another new experiment.
- To add the newly created `expn.tex` file to the document, go to `main.tex` file. Add `\input{files/expn.tex}` as a line.

> Most of the circuits used in this documents were drawn using [Inkscape](https://inkscape.org/). A popular circuit symbols for inkscape can be found [here](https://github.com/medwatt/circuitikz_symbols). for a tutorial, visit this [youtube channel].(https://youtu.be/uQDgtME-7DQ?si=AupBUdZqWn5uoSxw) 
> If you want to learn more about editing a tex file, visit the official [overleaf teaching page](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes) 
