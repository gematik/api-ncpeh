# NCPeH Mock-Umgebung

Diese Umgebung stellt eine lokale Mock-Infrastruktur für die NCPeH Schnittstellen bereit, inklusive eines rudimentären API-Gateways (nginx) und OpenAPI-Mock-Servern (prism).

Für die einfache und bequeme Orchestrierung der Container sowie das Ausführen der Tests wird der Command Runner `just` verwendet.

## Installation von just

### Linux
Viele Linux-Distributionen haben `just` bereits in ihren offiziellen Paketquellen:
* **Ubuntu/Debian:** `sudo apt install just`
* **Arch Linux:** `sudo pacman -S just`
* **Fedora:** `sudo dnf install just`

### macOS
Die einfachste Möglichkeit unter macOS ist die Installation über Homebrew oder MacPorts:
* **Homebrew:** `brew install just`
* **MacPorts:** `sudo port install just`

### Windows
Unter Windows kann `just` bequem über Paketmanager wie Scoop, Chocolatey oder Winget installiert werden:
* **Winget:** `winget install just`
* **Scoop:** `scoop install just`
* **Chocolatey:** `choco install just`
* **Cargo (Rust):** `cargo install just`


## Nutzung von just zum Starten der Mock-Umgebung

In Verzeichnis (`src/infrastructure/local/mock`) und `just` gefolgt von einem der definierten Rezepte ausführen.

Nur `just` in die Konsole eingeben für eine Liste aller verfügbaren Befehle.

Die im `justfile` enthaltenen Befehlen können natürlich auch manuell im CLI ausgeführt werden.
