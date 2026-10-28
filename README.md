# Mijn keuken

Mijn verzameling favoriete gerechten, als website via GitHub Pages.

## Een recept toevoegen

1. Open de map `_recepten`.
2. Maak een nieuw bestand aan, bijvoorbeeld `lasagne.md` (kleine letters, geen spaties).
3. Kopieer de inhoud van een bestaand recept en pas die aan.
4. Sla op met **Commit changes**. Na een minuutje staat het recept op de site.

## Een foto toevoegen

1. Open de map `fotos` en kies **Add file → Upload files**.
2. Upload je foto, bijvoorbeeld `hutspot.jpg`, en tik op **Commit changes**.
3. Open het recept en zet bovenaan, tussen de `---` regels, een regel erbij:
   `foto: hutspot.jpg`
   Let op: de naam moet precies hetzelfde zijn, ook hoofdletters.

## De kleuren aanpassen

Open `assets/style.css`. Bovenaan staan de kleuren:
- `--accent`: de hoofdkleur (balk bovenaan, titels)
- `--tekst`: de kleur van de tekst
- `--zacht`: de achtergrond
- `--lijn`: randjes en lijnen

## Hoe het werkt

- `_config.yml` bevat de instellingen, zoals de naam van de site.
- `_recepten/` bevat de recepten, één bestand per gerecht.
- `fotos/` bevat de foto's.
- `_layouts/` bepaalt hoe de pagina's eruitzien.
- `assets/style.css` bevat de kleuren en lettertypes.
