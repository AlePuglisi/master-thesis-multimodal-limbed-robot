# master-thesis-multimodal-limbed-robot
Master Thesis and Executive Summary LaTeX source for my Master Thesis at Politecnico di Milano and Tohoku University: <br/>

### Motion Control and Manipulability Analysis of LIMBERO-GRIEEL: a Multimodal Limbed Robot for Unstructured Environments



## How I compile this (long) LaTeX document

### Thesis
Building `Thesis.tex` takes a while...the final output will be saved as `Thesis.pdf` on a temporary `.build/` folder (together with all the other building files).

I compile this long LaTeX file in VSCode on an Ubuntu 24.04 machine, with texlive installed 
```
sudo apt install texlive-full
sudo apt install texlive-latex-extra
```

and `LaTeX Workshop` extension installed on VSCode 
(the one by [James Yu](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop))

The user configuration that I use in VSCode to save all in the .build folder and make everything build as desired is defined in [settings.json](./thesis_tex/settings.json). <br/>
To set it up in VSCode just Open the user preferences with `CTRL+SHIFT+P` and go to `Preferences: Open User Settings (JSON)`.

Then finally it is possible to compile the pdf by opening [Thesis.tex](./thesis_tex/Thesis.tex) and saving (`CTRL+S`) or clicking on the "run" button that appear on the top right (green arrow).

This will take long...<br/>

**Overleaf?**<br/>
With a free overleaf account it will fail due to compilation time exceeded. If you try to compile it in a premium overleaf account, be sure to configure the compiler to xelatex in `File > Settings > Compiler > XeLaTeX`.

### Executive Summary
The same said above holds to compile the Executive Summary. In this case just open [executive_summary.tex](./summary_tex/executive_summary.tex) and compile it by saving or running the LaTeX Workshop compiler. 

**Overleaf?**<br/>
As for the main Thesis, the poor free version of overleaf reach Time out for this document.












