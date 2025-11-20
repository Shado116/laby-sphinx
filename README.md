README — Projekt: _Jack the Ripper: The Anatomy of a Legend_
============================================================

Opis projektu
-------------

Dokument zawiera materiały w formacie **reStructuredText (.rst)** dotyczące historii, kontekstu społecznego oraz znaczenia kulturowego sprawy Kuby Rozpruwacza (Jack The Reaper).Materiały są przygotowane do publikacji jako **plik HTML** lub **PDF** z wykorzystaniem **Sphinx**.

Dokument składa się z trzech głównych części, które omawiają:

*   Tło społeczne i warunki życia w londyńskim East Endzie,
    
*   Przebieg śledztwa i analiza ofiar,
    
*   Wpływ mediów, powstanie legendy i późniejszą kulturę związaną z postacią Rippera.
    

Format i sposób użycia
----------------------

Wszystkie rozdziały są zapisane w formacie .rst. W dokumentach użyto:

*   nagłówków i podrozdziałów,
    
*   akapitów opisowych,
    
*   wyliczeń,
    
*   tabel (np. zestawienie ofiar lub elementów śledztwa),
    
*   wstawionego obrazu z wyrównaniem.
    

Budowanie dokumentacji
----------------------

Do zbudowania HTML potrzebny jest motyw **Furo**.
`   pip install furo   `

Wygenerowanie HTML:

`   make html   `

Wynik znajdziesz w:
`   _build/html/   `

Struktura projektu
------------------

* source/
  * index.rst
  * r1/
    * r1.rst
    * jack.jpg
  * r2/
    * r2.rst
  * r3/
    * r3.rst
  * r4/
    * r4.rst
  * r5/
    * r5.rst
