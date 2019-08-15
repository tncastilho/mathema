
*********************
TikZ support in Read the Docs service
*********************

.. tikz::
   \begin{tikzpicture}
    \node[shape=circle,draw=black] (A) at (0,0) {A};
    \node[shape=circle,draw=black] (B) at (0,3) {B};
    \node[shape=circle,draw=black] (C) at (2.5,4) {C};
    \node[shape=circle,draw=black] (D) at (2.5,1) {D};
    \node[shape=circle,draw=black] (E) at (2.5,-3) {E};
    \node[shape=circle,draw=black] (F) at (5,3) {F} ;

    \path [->] (A) edge node[left] {$5$} (B);
    \path [->](B) edge node[left] {$3$} (C);
    \path [->](A) edge node[left] {$4$} (D);
    \path [->](D) edge node[left] {$3$} (C);
    \path [->](A) edge node[right] {$3$} (E);
    \path [->](D) edge node[left] {$3$} (E);
    \path [->](D) edge node[top] {$3$} (F);
    \path [->](C) edge node[top] {$5$} (F);
    \path [->](E) edge node[right] {$8$} (F);   
  \end{tikzpicture}

.. tikz:: A beautiful TikZ drawing which works in readthedocs.org.
   \begin{tikzpicture}
   \draw[thick,rounded corners=8pt]
   (0,0)--(0,2)--(1,3.25)--(2,2)--(2,0)--(0,2)--(2,2)--(0,0)--(2,0);
   \end{tikzpicture}





.. tikz:: [>=latex',dotted,thick] \draw[->] (0,0) -- (1,1) -- (1,0)
   -- (2,0);
   :libs: arrows



1. Increment :math:`x` by a very small value :math:`h (h = \Delta x)`

.. math::

  f(x + h) = (x + h)^2

*********************
Include HTML 
*********************

1. Planilha GeoGebra

.. raw:: html
   :file: SecanteTangente.html



2. Gráfico JSXgraph

.. raw:: html
   :file: JSXgraph.html
   
3. AQUI TERMINA! 

.. sidebar:: A code example

    With a sidebar on the right.
    
    
Teste Termina!!!


.. sidebar:: A code examplw
:file: JSXgraph.html
    
    
THE END!!!!
