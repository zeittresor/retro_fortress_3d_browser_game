# Retro Fortress 3D

Ein kleiner browserbasierter 2.5D-Raycaster im Stil klassischer 90er-Shooter.

## Start

Einfach `index.html` im Browser öffnen.

Falls dein Browser lokale Audio-/Asset-Dateien bei `file://` zickig behandelt, starte alternativ den lokalen Mini-Server:

Windows:
```bat
run_local_server.bat
```

Oder manuell:
```bash
python -m http.server 8000
```

Dann im Browser öffnen:
```text
http://localhost:8000
```

## Steuerung

- WASD: bewegen / strafen
- Maus: umsehen per Pointer-Lock nach Klick ins Spielfeld
- Linke Maustaste: feuern
- Enter: alternativ feuern
- Leertaste: springen / Kamerahub
- E: Tür vor dir öffnen
- P: Pause
- ESC: Mausfang lösen
- Gamepad:
  - Linker Stick: Bewegung
  - Rechter Stick: drehen
  - A: springen
  - RT/X: feuern
  - Start: Pause

## Inhalte

- `index.html`: Spielcode
- `assets/audio`: Menü-/Ingame-Musik und Soundeffekte als WAV
- `assets/gfx/textures`: Wand-, Tür-, Ausgang- und Boden-Texturen
- `assets/gfx/sprites`: Gegner-, Pickup- und Muzzle-Flash-Sprites

Alle mitgelieferten Grafiken und Sounds sind eigenständig/prozedural erzeugt und nicht aus kommerziellen Spielen kopiert.
