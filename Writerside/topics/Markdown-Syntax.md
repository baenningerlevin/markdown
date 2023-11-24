# Markdown Syntax

<show-structure depth="2"/>

## Titel und Überschriften

Um Titel und Überschriften hinzuzufügen benutzt man `#`.

```Markup
# Titel
## Überschrift 1
### Überschrift 2
...
###### Überschrift 6
```

## Absätze

Um Absätze zu erstellen, braucht man nichts Weiteres zu tun, als eine leere Zeile zwischen den gewünschten Absätzen zu lassen.

```Markup
Das ist ein Absatz.

Das ist ein weiterer Absatz.
```

## Aufzählungen

### Ungeordnete Liste

Um eine ungeordnete Liste zu erstellen, benutzt kann man `-`, `*` oder `+` benutzen.

- George Washington
- John Adams
- Thomas Jefferson

```Markup
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

```Markup
1. James Madison
2. James Monroe
3. John Quincy Adams
```

---

### Checkliste

Zudem kann man Checklisten in Markdown machen.

- [x] Issue #739
- [ ] Issue #741

```Markup
- [x] Issue #739
- [ ] Issue #741
```

## Text formatieren

### Dicker Text

Um Text **dick** zu machen, benutzt man `**`.

```Markup
**Dieser Text soll dick sein**
```

---

### Kursiver Text

Um Text *kursiv* zu machen, benutzt man `*`

```Markup
*Kursiver Text*
```

---

### Durchgestrichener Text

Um ~~durchgestrichenen~~ Text zu erstellen, benutzt man `~~`

```Markup
~~Durchgestrichener Text~~
```

## Code

### Codeblöcke

Um Codeblöcke darzustellen, benutzt man drei Backticks, dazwischen die Sprache für das Syntaxhighlighting und letztendliche der eigentliche Code.

````C
```C
int main() {
  printf("Hello World!");
}
```
````

---

### Keywords

Um `Keywords` hervorzuheben, kann man Backticks um den entsprechenden Ausdruck machen.

```Markup
`printf()`
```

## Zitate

Ausserdem kann man in Markdown Text zitieren mit `>`

> Dieser Text ist ein Zitat

```Markup
> Dieser Text ist ein Zitat
```

## Tabellen

### Pipes untereinander

Tabellen in Markdown haben eine eher spezielle Syntax.

| First Header | Second Header |
|--------------|---------------|
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

So sieht die Syntax aus:

```Markup
| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |
```

---

### Pipes nicht untereinander

Die Pipes müssen nicht zwingend untereinander stehen:

| Command      | Description                                        |
|--------------|----------------------------------------------------|
| `git status` | List all *new or modified* files                   |
| `git diff`   | Show file differences that **haven't been** staged |

```Markup
| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |
```

## Links

### Weblinks

In Markdown kann man Links erstellen: [GitHub](https://www.github.com/)

```Markup
[Github](https://www.github.com/)
```

---

### Relative Links

Man kann auch Dateien im Repository verlinken mit relativen Links.

Das ist der Link für [Markdown Dokumentation](Markdown.md)

```Markup
[](markdown)
```

## Bilder

Eine weitere Funktion von Markdown ist das Einfügen von Bildern.

![MarkDown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/312px-Markdown-mark.svg.png?20190322184628)

## Kommentare

<!-- Man kann ebenfalls Kommentare erstellen -->
Kommentare sind ebenfalls in Markdown verfügbar.

```Markup
<!-- Ein Kommentar -->
```
