
To wszystko jeszcze raz razem i więcej
--------------------------------------

Interpreted Text Roles - role interpretujące tekst
..................................................

Użycie roli domyślnej: `tekst interpretowany`.

Rola ``emphasis`` użyta dwojako:
:emphasis:`tekst interpretowany` oraz *tekst interpretowany*.

| Rola ``literal`` użyta dwojako:
| :literal:`tekst interpretowany` oraz
| ``tekst interpretowany``.

Rola ``strong`` użyta dwojako:
:strong:`tekst interpretowany` oraz **tekst interpretowany**.

Marker roli może wystąpić również `po`:emphasis:
`tekście interpretowanym`:strong:.

Rola ``subscript`` w pełnym brzmieniu: a :subscript:`2` b :subscript:`3`
i w skrócie: a :sub:`2` b :sub:`3`.

Usunięcie zbędnych spacji przed wskaźnikami:
a\ :sub:`2` b\ :sub:`3`; *E* = *mc*\ :sup:`2`.

W takim przypadku, dla większej czytelności, lepiej użyć dyrektywy substytucji:

Wzór chemiczny dla czystej wody dany jest przez |H2O|.

.. |H2O| replace:: H\ :sub:`2`\ O

``:title reference:`` is the default interpreted text role:

We have elaborated an interactive manual `Linear Algebra`.

Directives - dyrektywy
......................

Przykład dyrektywy wyświetlającej wzór matematyczny:

.. math::

   S = \pi r^2.

Ten sam wzór zapisany w wierszu z użyciem roli ``:math:`` :math:`S = \pi r^2`.

Inne przykłady
..............

this is \ *one*\ word  versus  this is *one* word

Przykład użycia dyrektywy sagecellserver:

.. sagecellserver::
   
   print "To jest próbny wydruk w oknie SageCellServer:"
   print '1 + 2 + 3 =', 1+2+3
















