### Vergleich von 3 Passwortmanagern

|                 | **Keepass**         | Wertung | **Lastpass** | Wertung       | **Bitwarden** | Wertung |
|-----------------|-------------------|---------|----------|---------------|------------|---------|
| Link     | [keepass.info](https://keepass.info/)   || [lastpass.com](https://www.lastpass.com/de)  ||[bitwarden.com](bitwarden.com)| 2 |
| Verschlüsselung | AES-256, ChaCha20 | erfüllt | AES-256  |erfüllt       | AES-256 | erfüllt |
| OpenSource      | Ja                | erfüllt  | Nein     | nicht erfüllt |Ja  | erfüllt |
|Ablageort Datenbank |  Lokal | erfüllt | Cloud | nicht erfüllt| Lokal/Cloud | erfüllt|
|Verfügbar auf Windows/IOS |  Nein | nicht erfüllt| Ja | erfüllt | Ja | erfüllt|

### Passwortmanager einrichten - Bitwarden

Überlegungen:

1. Was tue ich, wenn ich mein Master-Password vergesse?
    - Ich werde mir mein Master-Password auf einen Zettel aufschreiben und diesen in einen Tresor legen, welcher bei mir Zuhause ist.
2. Wie erstelle ich ein Backup von meiner Passwort-Datenbank?
    - Ich möchte Bitwarden auf einem lokalen Server hosten und werde von diesem Server regelmässig ein Backup machen (wöchentlich). Falls dies nicht möglich ist, werde ich regelmässig eine CSV Datei mit allen Passwörter von der Cloud beziehen, diese verschlüsseln und bei mir ablegen.