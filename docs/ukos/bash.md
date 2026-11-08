# Komendy UKOS
## W tym pliku poznasz:
- Komendy linux;
- Przykład użycia tych komend;
- Opisy tych komend;

[Źródło](https://pjmpr.github.io/WARP2627/laboratoria/lab-04.html)

| Polecenie | Przykład użycia | Opis |
| ----------- |--------------| -------------|
| pwd | pwd | Wyświetlanie ścieżki bieżącego katalogu. |
| ls | ls -ls | Listowanie plików, także ukrytych, w formacie szczegółowym. |
| cd | cd docs/ukos oraz cd .. | Przechodzenie do katalogu i katalogu nadrzędnego. |
| mkdir | mkdir -p docs/ukos | Tworzenie katalogu wraz z brakującymi katalogami nadrzędnymi. |
| touch | 	touch bash.md | Tworzenie pustego pliku lub aktualizacja czasu jego modyfikacji. |
| cp | cp bash.md bash-backup.md | Kopiowanie pliku; opcja -r dla katalogów. |
| mv | 	mv bash-backup.md archive.md | Przenoszenie i zmiana nazwy pliku. |
| rm | rm archive.md | Usuwanie pliku i ostrzeżenie, że operacja omija kosz. |
| cat | cat bash.md | Wyświetlanie zawartości pliku w terminalu. |
| clear | clear | Czyszczenie widoku terminala bez usuwania historii poleceń. |

Inne przykładowe komendy:
```bash
whoami
```
Wyświetla nazwe aktywnego użytkownika;
```bash
cd ~
```
Przechodzi do ścieżki bezwlędnej;
```bash
nano nazwapliku.txt
```
Tworzy plik nazwapliku.txt.