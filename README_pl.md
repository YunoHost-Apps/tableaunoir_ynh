<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Tableaunoir dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/tableaunoir)](https://ci-apps.yunohost.org/ci/apps/tableaunoir/)
![Status działania](https://apps.yunohost.org/badge/state/tableaunoir)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/tableaunoir)

[![Zainstaluj Tableaunoir z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tableaunoir)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Tableaunoir na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Tableaunoir is an online collaborative blackboard tool with fridge magnets available in many languages. "Tableau noir" means blackboard in French. Contrary to plenty of other collaborative boards on the Internet, with Tableaunoir you can create interactive animations via the use of fridge magnets.

### Features

- Of course, you can draw and erase, with your mouse or a graphic tablet. You can draw shapes.
- Collaborate edit the same board at the same time (need a server for that), does not require an account
- Backgrounds: staffs for teaching music, grid, images and PDF documents
- You can also use kind of predefined fridge magnets that you can move on the board, to make animation e.g. for illustrating sorting algorithms, graphs algorithms etc (and even playing Go!).
- Create your own fridge magnets for interactive courses, by importing any image, or by transforming a part of the board (Ctrl + X).
- Color palette for chalk (c, 7 colors black/white #000000, yellow #FFFF00, orange #FFA500, blue #64ACFF, red #DC143C, pink #DDA0DD, green #32CD32),
- Draw interative graphs : vertices are magnets, labels of vertices and edges are handwritten but are updated when vertices are moved,
- Change the color of magnets' background,
- Load/Save the current board,
- Export in PNG or PDF,
- Add texts (Enter and type), and move texts. Supports LaTeX (using MathJax)!
- Switch to a whiteboard instead of a blackboard, or any background color
- Change from right-handed (default) to left-handed cursor,
- Divide yourboard in half. Ideal for teaching. Add as many new half-board as you need, going right with → and then left/right with ←/→ keyboard arrows,
- Make slides, record animations. This can be used to prepare slides for a talk or for a video.


**Dostarczona wersja:** 0.1~ynh1

**Demo:** <https://tableaunoir.github.io/>

## Zrzuty ekranu

![Zrzut ekranu z Tableaunoir](./doc/screenshots/screenshot.jpg)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://tableaunoir.github.io/>
- Repozytorium z kodem źródłowym: <https://github.com/tableaunoir/tableaunoir>
- Sklep YunoHost: <https://apps.yunohost.org/app/tableaunoir>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/tableaunoir_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/tableaunoir_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tableaunoir_ynh/tree/testing --debug
lub
sudo yunohost app upgrade tableaunoir -u https://github.com/YunoHost-Apps/tableaunoir_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
