# LaTeX-Vorlagen
Hier werden TeX Dokumente veröffentlicht, die dem Lernen der LaTeX Syntax dienen.
Danke, dass du dich dazu entschlossen hast, dein LaTeX Wissen zu teilen.

## Doc-Start
Damit erstellte Dokumente uniform und übersichtlich sind und bleiben bitte ich dich, diesen Doc-Start zu verwenden.

```tex
\documentclass[a4paper, 15pt]{article}
\usepackage[utf8]{inputenc}
\usepackage[ngerman]{babel}
\usepackage[T1]{fontenc}
\usepackage{graphicx}
\usepackage[left=2cm,right=2cm,top=2cm,bottom=2cm]{geometry}
\usepackage{amsmath}
\usepackage{amsfonts}
\usepackage{multicol}
\usepackage{tabularx}
\usepackage{tikz}
\usepackage{pgfplots}
\usepackage{uarial}
\renewcommand{\familydefault}{\sfdefault}
\usepackage{blindtext}
\usepackage{fancyhdr}
\usepackage{MnSymbol}
\usepackage{esvect}
\usepackage{array}
\usepackage{spath3}
\usepackage{bigdelim}
\pgfplotsset{compat=1.17}
\usetikzlibrary{arrows,calc}

\pagestyle{fancy}
	\lhead{\slshape Titel}
	\chead{\slshape Autor}
	\rhead{\slshape Datum}
\renewcommand{\headrulewidth}{0.2pt}
	\title{Titel}
	\date{\slshape Datum}
	\author{\slshape Autor}
\cfoot{\thepage}
\renewcommand{\headrulewidth}{0.4pt}

\begin{document}
Inhalt
\end{document}
```
