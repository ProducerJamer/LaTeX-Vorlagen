# LaTeX-Vorlagen
Hier werden TeX Dokumente veröffentlicht, die dem Lernen der LaTeX Syntax dienen.

Hallo, 
danke, dass du dich dazu entschieden hast dein LaTex wissen zu teilen.
Damit alle Seiten dieses Kanales uniform sind und bleiben, bitte ich dich, dich diesen Doc-Start zu verwenden:

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
\pgfplotsset{compat=1.17}
\usetikzlibrary{arrows,calc}
\usepackage{uarial}
\renewcommand{\familydefault}{\sfdefault}
\usepackage{blindtext}
\usepackage{fancyhdr}
\usepackage{MnSymbol}
\usepackage{esvect}
\usepackage{array}
\usepackage{spath3}
\usepackage{bigdelim}

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
