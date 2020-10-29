# MachadoDJ_Resume

## What is inside?

Enclosed, you will find the resume of Denis Jacob Machado, Ph.D., written in LaTeX using the ModernCV's casual style.

## How to compile?

To produce the final PDF file, navigate to the leading directory and run the following command:

```bash
$ pdflatex MAIN.tex
```

The command above should create the file `MAIN.pdf`.

## How can I get the dependencies?

### macOS

In macOS, you can get pdflatx with [brew](https://brew.sh/):

```bash
$ brew cask install mactex
```

Check to see if you can find pdflatex:

```bash
$ which pdflatex
```

If the location ios empty, try to relaunch the terminal app.

## Ubuntu

On Linux Ubuntu, you may install LaTeX using `apt`:

```bash
$ sudo apt-get install texlive-latex-extra
```

## How can I modify this project?

The main file is `MAIN.tex`. It calls for different sections of the CV, each one at a different file inside the `tex/` directory. All `.tex` files contain comments that may help modifying this CV at your will.