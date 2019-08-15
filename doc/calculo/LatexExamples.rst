
*********************
TikZ support in Read the Docs service
*********************



.. tikz:: A beautiful TikZ drawing which works in readthedocs.org.

   \draw[thick,rounded corners=8pt]
   (0,0)--(0,2)--(1,3.25)--(2,2)--(2,0)--(0,2)--(2,2)--(0,0)--(2,0);



.. tikz::

\def \n {5}
\def \radius {3cm}
\def \margin {8} % margin in angles, depends on the radius

\foreach \s in {1,...,\n}
{
  \node[draw, circle] at ({360/\n * (\s - 1)}:\radius) {$\s$};
  \draw[->, >=latex] ({360/\n * (\s - 1)+\margin}:\radius) 
    arc ({360/\n * (\s - 1)+\margin}:{360/\n * (\s)-\margin}:\radius);
}




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
