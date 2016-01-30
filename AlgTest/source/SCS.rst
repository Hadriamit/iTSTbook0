
Różne przykłady
...............

Nierozdzielny zapis różnych czcionek: this is \ *one*\ word  versus  this is *one* word

Przykład użycia dyrektywy sagecellserver:

.. sagecellserver::
   
   print "To jest próbny wydruk w oknie SageCellServer:"
   print '1 + 2 + 3 =', 1+2+3

Zbadamy, czy okna SCS są rzeczywiście połączone.
W tym oknie nadajemy wartości zmiennym :math:`a,\ b`:

.. sagecellserver::

   var('a,b')
   a=2; b=3
   print "a =", a, "b =", b

Sprawdzimy, czy w następnym (poniższym) oknie wartości te są aktualne:

.. sagecellserver::

   print "a =", a, "b =", b

