Wsparcie matematyczne w programie Sphinx.
-----------------------------------------

Rolę ``:math:`` używa się dla zapisania wzoru wewnątrz wiersza.
Od czasów Pitagorasa wiadomo, że :math:`\quad a^2 + b^2 = c^2`.

Dyrektywa ``.. math::`` dla wzoru eksponowanego:

.. math::

   (a + b)^2 = a^2 + 2ab + b^2

   (a - b)^2 = a^2 - 2ab + b^2

Każde takie równanie jest tworzone w środowisku ``split``,
co oznacza, że wyrażenia w równaniach można wyrównywać do znaku '&' i rozdzielać używając '\\\': 

.. math::

   (a + b)^2  &=  (a + b)(a + b) \\
              &=  a^2 + 2ab + b^2

Kiedy wyrażenie matematyczne jest tylko jedną linijką tekstu, może być podane jako argument dyrektywy:

.. math:: (a + b)^2 = a^2 + 2ab + b^2

Istnieje również opcja `nowrap` która nie dopuszcza do zawijania tekstu w wyrażeniach matematycznych:

.. math::
   :nowrap:

   \begin{eqnarray}
      y    & = & ax^2 + bx + c \\
      f(x) & = & x^2 + 2xy + y^2
   \end{eqnarray}

Rola ``:eq:`` służy do numerowania równań:

.. math:: e^{i\pi} + 1 = 0
   :label: euler

Wzór Eulera :eq:`euler` jest uważany za jedną z najpiękniejszych formuł matematycznych.
