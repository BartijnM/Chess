# Chess

Ik bouw een schaakspel waarin ik tegen een bot speel en tijdens mijn beurt om een onderbouwde zettip kan vragen. Ik speel in een eigen desktopvenster met een klikbaar bord, visuele schaakstukken en een knop Tip.

## Lokaal starten

Ik gebruik Python 3.11 of nieuwer. In PowerShell voer ik vanuit de hoofdmap uit:

```powershell
py -m venv .venv
.\.venv\Scripts\python.exe -m pip install -e .
.\.venv\Scripts\python.exe -c "import chess_game"
```

Ik controleer Tkinter met `.\.venv\Scripts\python.exe -m tkinter`. Dit opent een testvenster. Het spelvenster volgt in de eerste bouwstap. De eerste spelstap staat in de roadmap.

- [Architectuur](docs/architectuur.md)
- [Roadmap](docs/roadmap.md)
- [Voortgang](docs/voortgang.md)
