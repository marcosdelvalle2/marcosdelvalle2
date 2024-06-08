```math
\documentclass{article}
\usepackage{tikz}
\usetikzlibrary{positioning}
\usepackage{animate}

\begin{document}

\begin{animateinline}[autoplay, loop, poster=first, controls]{5}
    \multiframe{20}{i=0+1}{
        \begin{tikzpicture}[remember picture,overlay]
            \node[draw, circle, text=white, font=\huge, fill=red, text centered, minimum width=3cm, minimum height=3cm] (node) at (current page.center) {x0000};
        \end{tikzpicture}
    }
\end{animateinline}

\end{document}
