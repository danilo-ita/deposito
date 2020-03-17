# deposito
\documentclass[a4paper]{article}
\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage[italian]{babel}
\usepackage{amsmath,amssymb,amsthm}
\usepackage{microtype}
\newtheorem{esercizio}{Esercizio}
\newcommand{\ton}[1]{( \, {#1} \, )}

\begin{document}

\author{Danilo D'Eugenio \\ Matricola 588985} 
\title{Esercizi del corso di ETI} 
\date{\today}
\maketitle

\newpage

\begin{esercizio}
Se $X$ \`e una coppia ordinata allora esiste ed \`e unico un elemento $a$ che appartiene ad ogni elemento di $X$.
\end{esercizio}
\begin{proof}
$X$ \`e coppia ordinata, per cui, tale che $\exists a, \exists b \quad X=\{\{a\},\{a,b\}\}.$
$ \forall c \,\, \bigl( ( \, c\!\in\!x \quad \forall x\!\in\!X \, ) \Leftrightarrow ( \, c\!\in\!x \quad \forall x\!\in\!\{\{a\},\{a,b\}\} \, ) \Leftrightarrow (( \, c\!\in\!\{a\} \, ) \land ( \, c\!\in\!\{a,b\} \, )) \Leftrightarrow ( \, c = a \land ( \, c = a \lor c = b \, )) \Leftrightarrow ( \, c = a  \, ) \bigr) $
\end{proof}

\bigskip

\begin{esercizio}
$ ( \, a,b \, ) = ( \, a, b' \, ) \implies b = b' $
\end{esercizio}
\begin{proof}
$ \bigl( ( \, a,b \, ) = ( \, a,b' \, ) \bigr) \Leftrightarrow \ton{ \{\{a\},\{a,b\}\} = \{\{a\},\{a,b'\}\}} \Leftrightarrow \ton{ \forall t \,\, t\!\in\!\{\{a\},\{a,b\}\} \Leftrightarrow t\!\in\!\{\{a\},\{a,b'\}\}} $
\end{proof}



\end{document}


