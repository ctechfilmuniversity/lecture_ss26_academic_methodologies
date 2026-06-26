---
layout: default
title: Tutorial
nav_exclude: true
---


**Procedural Generation and Simulation**  

Prof. Dr. Lena Gieseke \| l.gieseke@filmuniversitaet.de  

## Tutorial - LaTeX with Overleaf


> The following tutorial has been written by Claude Code under my guidance and with several changes by me. 

## What is LaTeX?

LaTeX is a document preparation system widely used in academia. Instead of formatting text visually like in Word, you write plain text with markup commands, and LaTeX handles the typesetting. The result is consistently professional-looking documents, especially for papers with structured sections, references, and figures.

## What is Overleaf?

[Overleaf](https://www.overleaf.com) is a browser-based LaTeX editor — no installation required. You upload your files, edit in the browser, and compile to PDF with one click. It also supports collaboration.

---

## Setting Up the Course Template on Overleaf

### Step 1 — Create a New Project

1. Log in to [overleaf.com](https://www.overleaf.com) (free account is sufficient).
2. Click **New Project → Upload Project**.
3. Zip the entire `acsfubPublStyle_2026` folder and upload the zip file.

### Step 2 — Compile

Click the green **Recompile** button. The PDF preview on the right should show a two-column conference paper.

---

## Template File Structure

**Rule:** only edit files inside `work_files/`. Do not touch the style files in `acsfubPublStyle/`.


```
acsfubPublStyle_2026/
│
├── acsfubPublStyle/          ← class and style files
│   ├── acsfub.tex            ← MAIN FILE — sets up the document
│   ├── egpubl.cls            ← document class
│   ├── eg.sty                ← style package
│   └── ...                   ← other supporting files
│
└── work_files/               ← YOUR WORKING FOLDER
    ├── acsfub-body.tex       ← YOUR PAPER CONTENT goes here
    ├── acsfub-bib.bib        ← YOUR REFERENCES go here
    └── img/                  ← YOUR IMAGES go here
        ├── teaser.pdf
        └── ...
```


---

## Your Content File: `acsfub-body.tex`

This is where you write your paper. It is structured as follows.

### Name and Title

```latex
\title[ACS FUB \LaTeX\ Author Guidelines]%
      {\LaTeX\ Author Guidelines for the ACS FUB Proceedings Manuscripts}
```
Replace both title fields with your paper title. The short version in `[...]` appears in the header.

```latex
\author[K. Wolf ]
{
    \parbox{\textwidth}{\centering K. Wolf$^{1}$}
    \\
    {
        \parbox{\textwidth}{\centering $^1$Film University Babelsberg KONRAD WOLF, Germany\\}
    }
}
```
Replace `K. Wolf` with your name (or your submission ID for the anonymous review version).

### Abstract

```latex
\begin{abstract}
Your abstract text here. Aim for 100–150 words.
\end{abstract}
```

The abstract should stand alone: state the problem, why it matters, your approach, and what follows from it.

### Sections

```latex
\section{Introduction}
Your text...

\section{Related Work}
Your text...

\section{Your Main Content Title}
Your text...

\subsection{Method}
...

\subsection{Results}
...

\section{Conclusion}
...
```

Use `\section{}` for top-level headings and `\subsection{}` for sub-headings. Do not use `\subsubsection` — keep the structure flat.

### Bullet Points

```latex
\begin{itemize}
  \item First point,
  \item second point,
  \item third point.
\end{itemize}
```

### Figures

Single-column figure:

```latex
\begin{figure}[htb]
  \centering
  \includegraphics[width=.8\columnwidth]{work_files/img/yourimage.jpg}
  \caption{\label{fig:yourlabel} Your caption text.}
\end{figure}
```

Full two-column figure (use sparingly, e.g. for a wide teaser or overview):

```latex
\begin{figure*}[]
  \centering
  \includegraphics[width=.9\linewidth]{work_files/img/yourimage.jpg}
  \caption{\label{fig:yourlabel} Your caption text.}
\end{figure*}
```

Reference a figure in the text with `Figure~\ref{fig:yourlabel}`.  
Place image files in `work_files/img/`.

### Tables

```latex
\begin{table}[h!]
  \centering
  \begin{tabular}{|c | c c c|}
    \hline
    Header 1 & Header 2 & Header 3 & Header 4 \\ [0.5ex]
    \hline\hline
    A & 1 & 2 & 3 \\
    B & 4 & 5 & 6 \\
    \hline
  \end{tabular}
  \caption{Your table caption.}
  \label{tab:yourlabel}
\end{table}
```

Reference with `Table~\ref{tab:yourlabel}`.

### Equations

Inline math uses `$...$`:

```latex
The variable $x$ is defined as...
```

Display equations use `\begin{equation}`:

```latex
\begin{equation} \label{eq:yourlabel}
  E = mc^2
\end{equation}
```

---

## References and Bibliography

### Adding a Reference

Open `work_files/acsfub-bib.bib` and add a BibTeX entry. Examples:

**Journal article:**
```bibtex
@article{smith_2023_tit,
    author  = {Smith, Jane},
    title   = {The Title of the Article},
    journal = {Journal Name},
    volume  = {10},
    number  = {2},
    year    = {2023},
    pages   = {100--110},
    publisher = {Publisher},
}
```

**Conference paper:**
```bibtex
@inproceedings{jones_2022_tit,
    author    = {Jones, Bob},
    title     = {The Title of the Paper},
    booktitle = {Proceedings of the Conference Name},
    year      = {2022},
    pages     = {55--60},
    publisher = {Publisher},
}
```

**Book:**
```bibtex
@book{author_2021_tit,
    author    = {Author, Name},
    title     = {The Book Title},
    publisher = {Publisher},
    year      = {2021},
}
```

The citation key follows the convention `lastname_year_abbreviation` (e.g. `perlin_1985_ais`).

### Citing in the Text

```latex
% Citation at end of sentence:
This is a well-known result~\cite{smith_2023_tit}.

% Multiple citations:
Several approaches exist~\cite{smith_2023_tit, jones_2022_tit}.

% Citing by author name:
Smith~\cite{smith_2023_tit} shows that...

% More than two authors — use "et al.":
Jones et al.~\cite{jones_2022_tit} propose a method for...
```

The `~` before `\cite` prevents a line break between the text and the citation number.

> **Note:** Do not use footnotes. All references go into the bibliography.

---

## Special Characters

Some characters have special meaning in LaTeX and must be escaped:

| Character | LaTeX command |
| --------- | ------------- |
| `%`       | `\%`          |
| `&`       | `\&`          |
| `$`       | `\$`          |
| `_`       | `\_`          |
| `#`       | `\#`          |
| `{` `}`   | `\{` `\}`     |

Quotation marks: use ` `` ` to open and `''` to close — e.g. ` ``like this'' ` renders as "like this".

---

## Submitting

Export the compiled PDF from Overleaf: **Menu → Download PDF**.

Submit the PDF file named `am_paper_lastname.pdf` to your submissions folder.

---

## Compiling and Errors

Unlike Word, LaTeX does not update the document as you type. You must **compile** — Overleaf does this when you click **Recompile**. Only then will your changes appear in the PDF.

This also means errors work differently. In Word, bad formatting simply looks wrong. In LaTeX, a typo in a command can prevent the entire document from compiling, and you get no PDF at all. Overleaf shows a red error icon; click it to open the error log.

**Common errors and what they mean:**

| Error message                | Likely cause                                                  |
| ---------------------------- | ------------------------------------------------------------- |
| `Undefined control sequence` | Misspelled command name                                       |
| `File not found`             | Wrong path to an image or `.bib` file                         |
| `Missing $ inserted`         | Math character used outside math mode (e.g. bare `_` in text) |
| `Runaway argument`           | Unclosed `{` somewhere before this line                       |

**Practical tips:**

- Compile frequently — a short feedback loop makes errors easy to locate.
- When you see an error, check the **line number** in the log and look a few lines *above* it; LaTeX often reports the symptom, not the cause.
- If a compile that previously worked suddenly breaks, undo your last change and compile again to isolate the problem.
- Warnings (yellow) are usually harmless — errors (red) must be fixed before a PDF is produced.

---

![](./img/latex_01.jpg)   
[[imgur]](https://i.imgur.com/MfsSqWb.png)

*Happy LaTeXing!*
