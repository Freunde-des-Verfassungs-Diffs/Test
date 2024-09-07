# Diffs von Fedlex-Publikationen

Repository für das Testen von Diffs bei Gesetzesänderungen etc.

## Setup

Voraussetzung für ein lesbares Diff ist eine konsistente Formatierung. Dieses Repo verwendet [Node.js](https://nodejs.org/) mit [Prettier](https://prettier.io/) und [Prettier for XML](https://github.com/prettier/plugin-xml) für die Formatierung von XML-Exports aus [Fedlex](https://www.fedlex.admin.ch/).

1. `npm install` installiert die Node.js-Abhängigkeiten (getestet mit LTS-Version 20)
2. `npm run format` formatiert alle auffindbaren `.xml`-Dateien
