
# LaTeX Cheatsheet

### Figures: 
```latex
\begin{figure}[htb]
    \centering
    \includegraphics[width=10cm]{graphics/}
    \caption[List of Figures Caption]{The actual caption\footnotemark}
    \label{abb:label}
\end{figure}
\footnotetext{Included in:~\cite[][]{}}
```

### Tables: 
```latex
\begin{table}[h]
    \centering
    \begin{tabular}{|c|c|}
        \hline
        \textbf{Column 1} & \textbf{Column 2} \\
        \hline
        x1 &  \cellcolor{green!20} x2 \\    
        \hline
        x3 & x4 \\
        \hline
    \end{tabular}
    \caption[List of Tables Caption]{Actual Caption, includes in \cite[][p. xy]{Ancuti}}
    \label{tab:table}
\end{table}
```

### References: 
```latex
% normal citation
\cite{reference}
\cite[][p. xy]{reference}

% footnote citation
\footcite[Cf.][p. xy]{reference}
```

### Useful Commands: 
```latex
\textcolor{red}{text}
\textcolor{blue}{text}

\textbf{bold text}
\textit{italic text}

\enquote{quote}

\ac{abb.}

\begin{itemize}
    \item item 1
    \item item 2
\end{itemize}

\begin{enumerate}
    \item item 1
    \item item 2
\end{enumerate}

```

