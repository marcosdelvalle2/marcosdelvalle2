```math
\documentclass{article}
\usepackage{graphicx}
\usepackage{tikz}

\begin{document}

\begin{tikzpicture}[remember picture,overlay]
    \node[inner sep=0pt,opacity=0.1] at (current page.center) {\includegraphics[width=130mm]{image.jpg}};
\end{tikzpicture}

\begin{center}
    \Huge \textcolor{red}{x0000}
\end{center}

\end{document}


