# navigator-rzeszow-maneuvers
Bezpieczne, wersjonowane audyty manewrow dla aplikacji Navigator Rzeszow.

Plik `maneuvers-<sha256>.json` jest publikowany tylko po automatycznym audycie
zgodnosci aktualnej paczki GTFS z siecia drogowa OSRM. Aplikacja pobiera wylacznie
plik o odcisku SHA-256 identycznym z aktualnie uzywanym GTFS.
