\documentclass[12pt,twoside]{report}
\usepackage[utf8]{inputenc}
\usepackage{amsmath,amsfonts,graphicx,amsthm}
\usepackage{epsfig,amssymb}
\usepackage{caption}
\usepackage{fancyhdr}
\usepackage{lipsum}

\newtheorem{defn}[subsection]{Definition}
\newtheorem{note}{Note}
\newtheorem{notation}[subsection]{Notation}
\newtheorem{thm}[subsection]{Theorem}
\newtheorem{corollary}[subsection]{Corollary}
\newtheorem{eg}[subsection]{Example}
\newtheorem{lemma}[subsection]{Lemma}
\newtheorem{result}[subsection]{Result}
\newtheorem{problem}[subsection]{Problem}
\newtheorem{sol}{Solution}
\newtheorem*{sol*}{Solution}
\newtheorem{remark}[subsection]{Remark}
\newtheorem{prop}[subsection]{Proposition}

\makeatletter
\newcommand*{\rom}[1]{\expandafter\s_lo_wr_om_an_ca_p\r_om_an_nu_me_ra_l #1}
\makeatother

\widowpenalties 1 10000
\raggedbottom
\setlength{\parindent}{0pt}

\begin{document}

\tableofcontents
\newpage
\pagenumbering{arabic}

\Chapter{Definitions and Theory}
\line(1,0){360} \\

\begin{defn}[Random Sample]
Let $X$ be a random variable with a pdf or pmf $f$, and let $X_1, X_2, ..., X_n$ be iid random variables with the common pdf or pdf $f$. 

Then the collection $X_1, X_2, ..., X_n$ is called a random sample of size $n$ from the population $f$.
\end{defn}


\newpage
\addcontentsline{toc}{chapter}{Bibliography}
\begin{thebibliography}{9}
    \bibitem{latexcompanion}
        (Schaum’s Outlines) John Schiller, R. Alu Srinivasan, Murray Spiegel - Probability and Statistics-McGraw-Hill Education (2012)
    \bibitem{latexcompanion}
        \lipsum[2][1-3]
    \bibitem{latexcompanion}
        \lipsum[3][1-3]
    \bibitem{latexcompanion}
        \lipsum[4][1-3]
    \bibitem{latexcompanion}
        \lipsum[5][1-3]
    \bibitem{latexcompanion}
        \lipsum[6][1-3]
\end{thebibliography}
\end{document}

