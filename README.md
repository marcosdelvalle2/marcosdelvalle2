```math
\documentclass{article}
\usepackage{graphicx}
\usepackage{tikz}

\begin{document}

\begin{tikzpicture}[remember picture,overlay]
    \node[inner sep=0pt,opacity=0.1] at (current page.center) {\includegraphics[width=130vw,height=100vh,keepaspectratio]{image.jpg}};
\end{tikzpicture}

Seu conteúdo aqui.

\end{document}


