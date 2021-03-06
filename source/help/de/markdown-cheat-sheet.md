---
Title: Markdown-Spickzettel
---
Markdown ist eine praktische Art um Webseiten zu bearbeiten.

## Grundlagen

Text formatieren:

    Normal **Fettschrift** *Kursiv* ~~Durchgestrichen~~ `Code`

Eine Liste erstellen:

    * Punkt eins
    * Punkt zwei
    * Punkt drei

Eine sortierte Liste erstellen:

    1. Punkt eins
    2. Punkt zwei
    3. Punkt drei

Eine Aufgabenliste erstellen:

    - [x] Punkt eins
    - [ ] Punkt zwei
    - [ ] Punkt drei

Eine Überschrift erstellen:

    # Überschrift 1
    ## Überschrift 2
    ### Überschrift 3

Zitate erstellen:

    > Zitat
    >> Zitat im Zitat
    >>> Zitat im Zitat im Zitat

Links erstellen:

    [Link zu Seite](/de/help/how-to-make-a-website)
    [Link zu Datei](/media/downloads/yellow.pdf)
    [Link zu Webseite](https://datenstrom.se/de/)

Ein Bild hinzufügen:

    [image photo.jpg]
    [image photo.jpg Beispiel]
    [image photo.jpg "Dies ist ein Beispielbild"]

Ein Bild hinzufügen, alternatives Format:

    ![image](photo.jpg)
    ![image](photo.jpg "Beispiel")
    ![image](photo.jpg "Dies ist ein Beispielbild")

## Extras

Tabellen erstellen:

    | Kaffee     | Milch | Stärke  |
    |------------|-------|---------|
    | Espresso   | nein  | stark   |
    | Macchiato  | ja    | mittel  |
    | Cappuccino | ja    | schwach |

Fußnoten erstellen:

    Text mit einer Fußnote[^1] und noch weiteren Fußnoten.[^2] [^3]
    
    [^1]: Hier ist die erste Fußnote
    [^2]: Hier ist die zweite Fußnote
    [^3]: Hier ist die dritte Fußnote

Quellcode anzeigen:

    ```
    Quellcode wird unverändert angezeigt.
    function onLoad($yellow) {
        $this->yellow = $yellow;
    }
    ```

Absätze erstellen:

    Hier ist der erste Absatz. Der Text kann über mehrere Zeilen gehen
    und kann durch eine Leerzeile vom nächsten Absatz getrennt werden.

    Hier ist der zweite Absatz.

Zeilenumbrüche erstellen:

    Hier ist die erste Zeile⋅⋅
    Hier ist die zweite Zeile⋅⋅
    Hier ist die dritte Zeile⋅⋅
    
    Leerzeichen am Zeilenende sind dargestellt durch Punkte (⋅)

Hinweise erstellen:

    ! Hier ist ein Hinweis mit Warnung
    
    !! Hier ist ein Hinweis mit Fehler
    
    !!! Hier ist ein Hinweis mit Tipp

CSS benutzen:

    ! {.class}
    ! Hier ist ein Hinweis mit benutzerdefinierter Klasse.
    ! Der Text kann über mehrere Zeilen gehen
    ! und Markdown-Formatierung beinhalten.

HTML benutzen:

    <strong>Text mit HTML</strong> kann wahlweise benutzt werden.
    <a href="https://datenstrom.se/de/" target="_blank">Link in einem neuen Tab öffnen</a>.

## Abkürzungen

`[image photo.jpg Beispiel - 50%]` = [Miniaturbild hinzufügen](https://github.com/datenstrom/yellow-extensions/tree/master/source/image)  
`[gallery photo.*jpg - 20%]` = [Bildergalerie hinzufügen](https://github.com/datenstrom/yellow-extensions/tree/master/source/gallery)  
`[slider photo.*jpg]` = [Bildergalerie mit Schieber hinzufügen](https://github.com/datenstrom/yellow-extensions/tree/master/source/slider)  
`[youtube fhs55HEl-Gc]` = [Youtube-Video einbinden](https://github.com/datenstrom/yellow-extensions/tree/master/source/youtube)  
`[soundcloud 101175715]` = [Soundcloud-Audio einbinden](https://github.com/datenstrom/yellow-extensions/tree/master/source/soundcloud)  
`[twitter datendeveloper]` = [Twitter-Nachrichten einbinden](https://github.com/datenstrom/yellow-extensions/tree/master/source/twitter)  
`[instagram BISN9ngjV2-]` = [Instagram-Foto einbinden](https://github.com/datenstrom/yellow-extensions/tree/master/source/instagram)  
`[googlecalendar de.german#holiday]` = [Google-Kalender einbinden](https://github.com/datenstrom/yellow-extensions/tree/master/source/googlecalendar)  
`[googlemap Stockholm]` = [Google-Karte einbinden](https://github.com/datenstrom/yellow-extensions/tree/master/source/googlemap)  
`[blogchanges /blog/]` = [neuste Blogseiten anzeigen](https://github.com/datenstrom/yellow-extensions/tree/master/source/blog)  
`[wikichanges /wiki/]` = [neuste Wikiseiten anzeigen](https://github.com/datenstrom/yellow-extensions/tree/master/source/wiki)  
`[fa fa-envelope-o]` = [Icons und Symbole anzeigen](https://github.com/datenstrom/yellow-extensions/tree/master/source/fontawesome)  
`[ea ea-smile]` = [Emoji und bunte Bilder](https://github.com/datenstrom/yellow-extensions/tree/master/source/emojiawesome)  
`[yellow]` = [Webseite-Version anzeigen](https://github.com/datenstrom/yellow-extensions/tree/master/source/core)  
`[edit]` = [Webseite im Webbrowser bearbeiten](https://github.com/datenstrom/yellow-extensions/tree/master/source/edit)  
`[toc]` = [Inhaltsverzeichnis anzeigen](https://github.com/datenstrom/yellow-extensions/tree/master/source/toc)  
`[--more--]` = [Seitenumbruch hinzufügen](https://github.com/datenstrom/yellow-extensions/tree/master/source/blog)  

## Einstellungen

`Title` = Seitentitel  
`TitleContent` = Seitentitel der im Inhalt angezeigt wird  
`TitleNavigation` = Seitentitel der in der Navigation angezeigt wird  
`TitleHeader` = Seitentitel der im Webbrowser angezeigt wird  
`TitleSlug` = Seitentitel zum Speichern der Seite  
`Description` = Beschreibung der Seite  
`Author` = Autoren der Seite, durch Komma getrennt  
`Email` = E-Mail des Seitenautors  
`Language` = Sprache der Seite  
`Layout` = Layout der Seite  
`LayoutNew` = Layout um eine neue Seite zu erzeugen  
`Theme` = Thema der Seite  
`Parser` = Parser der Seite  
`Status` = Status für Arbeitsablauf  
`Image` = Bild der Seite  
`ImageAlt` = Alternative Bildbeschreibung der Seite  
`Modified` = Änderungsdatum der Seite, JJJJ-MM-TT Format  
`Published` = Veröffentlichungsdatum der Seite, JJJJ-MM-TT Format  
`Tag` = Tags zur Kategorisierung der Seite, durch Komma getrennt  
`Redirect` = Umleitung zu einer neuen Seite oder URL  
