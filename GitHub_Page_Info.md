# Aufsetzen einer GitHub Page für ein Repository

---

## Anforderungen:

- Aktuelle Version von Python
- PIP
- git/gitbash (optinal auch GitHub Desktop)
- MKDocs (https://www.mkdocs.org/)
- Material Theme (https://github.com/squidfunk/mkdocs-material)
- Öffentliches Repository/Projekt (https://pages.github.com/)

---

## Erklärungen

In mkdocs.yml wird der Name der späteren Github Page, die Navigation und das Design (Theme) festgelegt.

Im Ordner docs liegen die Ressourcen, sprich Bilder und Dokumente (in .md Format)

Lokale Tests sind mit den mkdocs Befehlen "build" und "serve" möglich.

Zum Bereitstellen für Github wird "mkdocs gh-deploy --clean" verwendet. Ohne "--clean" kann es passieren, das einige Seiten nicht korrekt aktualisiert werden und ggf, alte Designs beibehalten.  

Die Webadresse die beim "deploy" angegeben ist, ist nicht zwingend korrekt, das übliche Schema zum Aufruf für die Webadresse lautet: https://organisationsname.github.io/projektordner/site/

---

## Hinweis

Beim Verwenden des Material Themes kann es ohne manuellen Eingriff passieren, dass das Standard-Favicon von Material für GitHub Page verwendet wird. Hier kann ggf. nach dem "deploy" manuell in /site/assets/images das korrekte favicon eingesetzt werden bevor ein Commit gemacht wird.