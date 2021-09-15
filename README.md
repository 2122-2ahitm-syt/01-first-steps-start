# First Steps

## Task 1: Git Version

Auf einem Schulrechner:

- Klone das Remote-Repository auf den lokalen Rechner: 

  ```bash
  git clone <web url des github repos>
  ```

- Gib die installierte Git-Version auf der Konsole aus: 

  ```bash
  - git --version
  ```

- Speichere einen Screenshot der Konsolenausgabe als `git-pc-version.jpg` im Repository-Verzeichnis.

- Füge die neue Datei zur Staging-Area des Local-Repository hinzu: 

  ```bash 
  git add git-pc-version.jpg
  ```

- Sichere die gestagte Änderung endgültig im Local-Repository: 

  ```bash
  git commit -m "task 1 (stable): screenshot of git version on school pc"
  ```

- Lade die Änderung in das Remote-Repository hoch:

  ```bash
  git push
  ```

## Task 2: Hello World

Auf einem Schulrechner:

- Öffne das Repository-Verzeichnis mit Visual Studio Code.

- Erstelle darin die Datei `app.js`.

- Füge in `app.js` folgende Anweisung ein: 

  ```javascript
  console.log('Hello World');
  ```

- Öffne die Konsole und führe das Programm aus: 

  ```bash
  node app.js
  ```

- Speichere einen Screenshot der Konsolenausgabe als `hello-world.jpg` im Repository-Verzeichnis.

- Füge alle neuen Dateien zur Staging-Area hinzu:

  ```bash
  git add .
  ```

- Sichere die gestagten Änderungen endgültig im Local-Repository: 

  ```bash
  git commit -m "task 2 (stable): print hello world"
  ```

- Lade die Änderungen in das Remote-Repository hoch.

Die letzten drei Schritte werden künftig mit *Add, Commit & Push* abgekürzt.

## Task 3: Git Installation

Auf deinem Notebook:

- Installiere die neueste Version von [Git](https://git-scm.com/downloads).

- Konfiguriere deinen Usernamen und deine Email-Adresse:

  ```bash
  git config --global user.name "your-username"
  git config --global user.email your-email-address
  ```

- Klone das Remote-Repository auf dein Notebook.

- Gib die installierte Git-Version auf der Konsole aus.

- Speichere einen Screenshot der Konsolenausgabe als `git-nb-version.jpg` im Repository-Verzeichnis.

- Add, Commit & Push: `"task 3 (stable): screenshot of git version on notebook"`

## Task 4: VS Code Installation

Auf deinem Notebook:

- Installiere die neueste Version von [Visual Studio Code](https://code.visualstudio.com/download).

- Gib die installierte Version von VS Code auf der Konsole aus:

  ```bash
  code --version
  ```

- Speichere einen Screenshot der Konsolenausgabe als `code-version.jpg` im Repository-Verzeichnis. 

- Add, Commit & Push: `"task 4 (stable): <your own short description>"`

## Task 5: Node.js Installation

Auf deinem Rechner:

- Installiere die neueste LTS-Version von [Node.js](https://nodejs.org/en/).

- Gib die installierte Node-Version auf der Konsole aus:

  ```bash
  node --version
  ```

- Speichere einen Screenshot der Konsolenausgabe als `node-version.jpg` im Repository-Verzeichnis.

- Add, Commit & Push: `"task 5 (stable): <your own short description>"`

## Task 6: Hello 10 Worlds

Auf deinem Rechner:

- Öffne das Repository-Verzeichnis mit VS Code.

- Gib in `app.js` auch deinen Namen auf der Konsole aus:

  ```bash
  hello world
  my name is john
  ```

- Add, Commit & Push:`"task 6 (started): <your own short description>"`

- Füge in `app.js` eine Schleife ein, sodass `Hello World` 8x ausgegeben wird.

- Add, Commit & Push:`"task 6 (unstable): <your own short description>"`

- Ändere die Schleife, sodass `Hello World` 10x ausgegeben wird.

- Speichere einen Screenshot der Konsolenausgabe im Repository: `hello-10-worlds.jpg`

- Add, Commit & Push:`"task 6 (stable): <your own short description>"`
