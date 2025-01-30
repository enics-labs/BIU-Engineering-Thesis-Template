# BIU Engineering Thesis Template
LaTeX Templates for writing your thesis or research proposal.

The templates adhere to the BIU definitions at:
*    MSc Thesis:   https://graduate-school.biu.ac.il/node/1773
*    PhD Thesis:   https://graduate-school.biu.ac.il/node/1793


To start an Overleaf project based on this template, just make a copy of the project at https://www.overleaf.com/read/bkyntscbfhzz#51915d

# How to Use the Template?

## Configuration

The templates are defined inside the Main.tex file.

At the header of the template file, you will find the configuration variable: "doctype". 
You need to select the appropriate "doctype" for your submission:
* MSc Research Proposal: "msc-proposal"
* PhD Research Proposal: "phd-proposal"
* MSc Thesis: "msc-thesis"
* PhD Thesis: "phd-thesis"

## Auxiliary Pages

We have provided MSWord templates for the front and backmatter of the thesis under the AuxiliaryPages folder. There are .docx files that you can edit with the info about your work (Name, Title, etc.). Save these as PDF files and include them in the appropriate place in the .tex file. We have included example PDFs for you to see how to include them and what the results will look like.



## Folders and files:

The following template files are included within the noted folders:
* **packages/basic_packages.sty**: Includes commonly used LaTeX packages and definitions.
* **packages/macros.tex**: Some useful macros that you are encouraged to use.
* **newcommands/units.tex**: Includes shortcuts for SI units, using the siunitx package.
* **newcommands/this_glossary**: A file to define your \newcommands and \newacronyms.
* **Figures/**: A folder for storing your figures.
* **Figures/matlab_figure.m** and **Figures/python_figure.m**: Some code templates for creating figures and exporting them as PDF for MATLAB and Python, respectively.
* **bibliography/this_bibliography.bib**: A file for adding your BibTeX entries to.
* **AuxiliaryPages**: As noted before, these are .docx templates for the front and back matter of the thesis.

## MS Word Users:
If you prefer to use MS Word instead of LaTeX, you can find the following templates under the **"MSWord Templates"** folder:
* **MSc_Proposal.docx**: Template for MSc Research Proposal
* **PhD_Proposal.docx**: Template for PhD Research Proposal
* **MSc_Thesis.docx**: Template for MSc Thesis
* **PhD_Thesis.docx**: Template for PhD Thesis
* **MSc_Project.docx**: Template for Final Project in the Non-Thesis Track



