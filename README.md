# MachadoDJ_Resume

## What is inside?

Enclosed, you will find the resume of Denis Jacob Machado, Ph.D., written in LaTeX using ModernCV's casual style.

## How to compile?

To produce the final PDF file, navigate to the leading directory and run the following command:

```bash
$ pdflatex MachadoDJ_Resume.tex
```

The command above should create the file `MachadoDJ_Resume.pdf`.

## How can I get the dependencies?

### moderncv

You will need **moderncv**, a modern curriculum vitae class for LaTeX available from [GitHub](https://github.com/moderncv).

### Other dependencies in macOS

In macOS, you can get pdflatx with [brew](https://brew.sh/):

```bash
$ brew cask install mactex
```

Check to see if you can find pdflatex:

```bash
$ which pdflatex
```

If the location ios empty, try to relaunch the terminal app.

### Other dependencies in Ubuntu

On Linux Ubuntu, you may install LaTeX using `apt`:

```bash
$ sudo apt-get install texlive-latex-extra
```

## How can I modify this project?

The main file is `MachadoDJ_Resume.tex`. It calls for different sections of the CV, each one in a different file inside the `tex/` directory. All `.tex` files contain comments that may help modify this CV at your will.
