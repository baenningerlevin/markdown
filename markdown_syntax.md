# Markdown Syntax

- [Markdown Syntax](#markdown-syntax)
  - [Titel und Überschriften](#titel-und-überschriften)
  - [Absätze](#absätze)
  - [Aufzählungen](#aufzählungen)
    - [Ungeordnete Liste](#ungeordnete-liste)
    - [Geordnete Liste](#geordnete-liste)
    - [Checkliste](#checkliste)
  - [Text formatieren](#text-formatieren)
    - [Dicker Text](#dicker-text)
    - [Kursiver Text](#kursiver-text)
    - [Durchgestrichener Text](#durchgestrichener-text)
  - [Code](#code)
    - [Codeblöcke](#codeblöcke)
    - [Keywords](#keywords)
  - [Zitate](#zitate)
  - [Tabellen](#tabellen)
    - [Pipes untereinander](#pipes-untereinander)
    - [Pipes nicht untereinander](#pipes-nicht-untereinander)
  - [Links](#links)
    - [Weblinks](#weblinks)
    - [Relative Links](#relative-links)
  - [Bilder](#bilder)
  - [Kommentare](#kommentare)

## Titel und Überschriften

Um Titel und Überschriften hinzuzufügen benutzt man `#`.

```md
# Titel
## Überschrift 1
### Überschrift 2
...
###### Überschrift 6
```

## Absätze

Um Absätze zu erstellen, braucht man nichts weiteres zu tun, als eine leere Zeile zwischen den gewünschten Absätzen zu lassen.

```md
Das ist ein Absatz.

Das ist ein weiterer Absatz.
```

## Aufzählungen

### Ungeordnete Liste

Um eine ungeordnete Liste zu erstellen benutzt kann man `-`, `*` oder `+` benutzen.

- George Washington
- John Adams
- Thomas Jefferson

```md
- George Washington
* John Adams
+ Thomas Jefferson
```

---

### Geordnete Liste

Für eine geordnete List benutzt man `1.`, `2.`, `3.`, etc.

1. James Madison
2. James Monroe
3. John Quincy Adams

```md
1. James Madison
2. James Monroe
3. John Quincy Adams
```

---

### Checkliste

Zudem kann man Checklisten in Markdown machen.

- [x] Issue #739
- [ ] Issue #741

```md
- [x] Issue #739
- [ ] Issue #741
```

## Text formatieren

### Dicker Text

Um Text **dick** zu machen benutzt man `**`.

```md
**Dieser Text soll dick sein**
```

---

### Kursiver Text

Um Text *kursiv* zu machen benutzt man `*`

```md
*Kursiver Text*
```

---

### Durchgestrichener Text

Um ~~durchgestrichenen~~ Text zu erstellen benutzt man `~~`

```md
~~Durchgestrichener Text~~
```

## Code

### Codeblöcke

Um Codeblöcke darzustellen benutzt man drei Backticks, dazwischen die Sprache für das Syntaxhighlighting und letztendliche der eigentliche Code.

````C
```C
int main() {
  printf("Hello World!");
}
```
````

---

### Keywords

Um `Keywords` hervorzuheben kann man Backticks um den entsprechenden Ausdruck machen.

```md
`printf()`
```

## Zitate

Ausserdem kann man in Markdown Text zitieren mit `>`

> Dieser Text ist ein Zitat

```md
> Dieser Text ist ein Zitat
```

## Tabellen

### Pipes untereinander

Tabellen in Markdown haben eine eher spezielle Syntax.

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

So sieht die Syntax aus:

```md
| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |
```

---

### Pipes nicht untereinander

Die Pipes müssen nicht zwingend untereinander stehen:

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

```md
| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |
```

## Links

### Weblinks

In Markdown kann man Links erstellen: [GitHub](htttps://www.github.com/)

```md
[Github](https://www.github.com/)
```

---

### Relative Links

Man kann auch Dateien im Repository verlinken mit relativen Links.

Das ist der Link für [Markdown Dokumentation](markdown.md)

```md
[Markdown Dokumenation](markdown.md)
```

## Bilder

Eine weitere Funktion von Markdown ist das Einfügen von Bildern.

![MarkDown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/312px-Markdown-mark.svg.png?20190322184628)

## Kommentare

<!-- Man kann ebenfalls Kommentare erstellen -->
Kommentare sind ebenfalls in Markdown verfügbar.

```md
<!-- Ein Kommentar -->
```
