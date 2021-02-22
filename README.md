
# Olympus DAO Manifesto

> Functional DAO for Open Source cryptocurrency projects.

## Reading

To read the whitepaper you can find the latest:

- [Website](https://oly.tech/dao/dao_en.pdf)
- [Github](https://github.com/olympus-protocol/dao-manifesto/releases/latest)

## Building

To build from the source, you will need to have a LaTeX compiler for your OS.

Please read further on: `https://www.latex-project.org/get/`

### Building main file

To build the whitepaper first clone the repository:

```bash
git clone https://github.com/olympus-protocol/dao-manifesto && cd dao-manifesto
```

Make sure you have LaTeX compiler and run:

```bash
pdflatex -interaction=nonstopmode dao_en.tex
```

This will create a file named `dao_en.pdf`

### Building all the languages

To build the manifesto on all languages first clone the repository:

```bash
git clone https://github.com/olympus-protocol/dao-manifesto && cd dao-manifesto
```

And run the build script

```bash
./build.sh
```

This will create a `release` folder with all the pdf for all translations.
