# Architectuur

`python-chess` beheert het bord, de legale zetten en de speluitkomst. Ik bouw de bot en de tips zelf. De spelmodule past zetten toe. De zoekmodule evalueert kandidaatstellingen vanuit een vast perspectief. De tipfunctie toont legale kandidaten met een reden die aansluit op de berekening, zoals materiaalwinst of mat. De Tkinter-interface tekent het bord en de stukken op een Canvas. Ik klik op een stuk en daarna op het doelvak. De spelmodule valideert de zet. De knop Tip toont kandidaten en licht een aanbevolen zet uit zonder die toe te passen.

Ik begin met een desktopvenster dat de beginstelling toont. Daarna voeg ik selectie, markeringen en een promotiekeuze toe. Bij langere zoekopdrachten houd ik het venster responsief en verwerk ik het resultaat in de GUI-eventloop.

[Bord en legale zetten in python-chess](https://python-chess.readthedocs.io/en/latest/core.html)

Ik voeg modules aan `src/chess_game/` toe zodra ik ze nodig heb. Met `unittest` controleer ik de spelregels en beslissingen zonder een venster te openen.
