---
title: Ein Tutorial
---
![Garten](assets/tutorial.jpg)

### Deine erste Saat

Dies ist Ihre erste Notiz. Sie finden sie im Verzeichnis [`notes/`](https://github.com/maximevaillancourt/digital-garden-jekyll-template/tree/master/_notes).  

### Link Syntax

Um einen Link zu einer anderen Notiz zu erstellen, können Sie mehrere Syntaxen verwenden. Die folgenden vier verwenden die Notation "doppelte eckige Klammern" ([sehen Sie sich die Markdown-Quelldatei](https://github.com/maximevaillancourt/digital-garden-jekyll-template/blob/master/_notes/your-first-note.md#link-syntax) an, um die zugrunde liegende Syntax zu sehen).

- Verwendung des Notiztitels: [[a note about cats]]
- Verwenden des Dateinamens der Notiz: [[cats]]
- Verwenden des Titels der Notiz mit einer Beschriftung: [[A note about cats|link to the note about cats using the note title]]
- Verwendung des Dateinamens der Notiz mit einer Beschriftung: [[cats|link to the note about cats using the note's filename]]

Sie können Notizen in Unterverzeichnissen organisieren und normal verknüpfen. Zum Beispiel verweisen die obigen Links alle auf die `_notes/animals/cats.md` -Datei. Hier ist ein weiteres Beispiel: [[tigers]].

Nicht-lateinische Sprachen werden unterstützt: [[안녕하세요]]; Das Gleiche gilt für Akzente/diakritische Zeichen: [[bon appétit!]]

Bindestriche und Unterstriche in Dateinamen werden unterstützt und können in der Syntax für Klammerlinks weggelassen werden. Als Beispiel kann die `your-first-note.md`-Datei mit [[your first note]]oder [[your-first-note]] oder sogar [[yOuR-FiRsT Note]] verknüpft werden.

In allen Fällen, wenn der Link in doppelten Klammern nicht auf eine gültige Notiz zeigt, werden die doppelten Klammern trotzdem angezeigt, wie folgt: [[ Es gibt keine Notiz, die zu diesem Link passt]].

Alternativ können Sie die reguläre [Markdown-Syntax](https://www.markdownguide.org/getting-started/) für Links verwenden, mit einem relativen Link zur anderen Notiz, wie folgt: [Dies ist ein Markdown-Link zu der Notiz über Katzen](/cats){: .internal-link}. Vergessen Sie nicht, die Klasse `.internal-link` zu verwenden, um sicherzustellen, dass der Link als interner Link formatiert ist (ohne den kleinen Pfeil).  

Da sich im Web alles um HTML dreht, können Sie immer einfaches HTML verwenden, wenn Sie möchten, wie folgt: <a class="internal-link" href="/cats">Dies ist ein Link zum Hinweis über Katzen mit HTML</a>.

Natürlich können Sie auch auf externe Websites verlinken, wie z.B. hier: [Dies ist ein Link zu Wikipedia](https://de.wikipedia.org). Auch hier können Sie reines HTML verwenden, wenn Sie dies bevorzugen. Fußnoten werden ebenfalls unterstützt und wie interne Links behandelt._[^1]_ Sie können in Ihren Fußnoten auf andere Notizen verweisen._[^2]_

[^1]: Dies ist eine Fußnote. Weitere Informationen zur Verwendung von Fußnoten finden Sie im [Markdown Guide](https://www.markdownguide.org/extended-syntax/#footnotes). 
 
[^2]: Dies ist eine weitere Fußnote, die auf die Anmerkung über [[cats]] verweist. Du kannst auch auf [[ Notizen, die nicht existieren ]] zeigen, wenn du möchtest. 

### Einbetten von Tweets

Hinweis: Dieses Verhalten ist aus Datenschutzgründen standardmäßig deaktiviert. Weitere Informationen zum Aktivieren finden Sie im Abschnitt "Site-Konfiguration" weiter unten.

Sie können eine Tweet-URL in einer eigenen Zeile einfügen (wie unten), und sie wird durch eine offizielle Twitter-Einbettung ersetzt, wenn die Site-Konfiguration dies erfordert.

https://twitter.com/jack/status/20

### Einbetten von Medien

Sie können Mediendateien mithilfe von HTML5-Medien-Tags in eine Notiz einbetten. Hier ist ein Beispiel für eine Audiodatei:

"Jazzy Frenchy" von Benjamin Tissot von bensound.com
<audio controls>
  <source src="{{ site.baseurl }}/assets/jazzyfrenchy.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

### Site-Konfiguration

Einige Verhaltensweisen können durch Anpassen der `_config.yml`-Datei konfiguriert werden.

**`use_html_extension`**: Wenn Sie einen statischen Host verwenden, der keine URLs unterstützt, die nicht mit `.html` enden (z. B. Neocities), versuchen Sie, den Wert `use_html_extension` in der `_config.yml`-Datei auf `true` zu ändern und starten Sie den Jekyll-Server neu (oder erstellen Sie die Site neu). Dadurch wird eine `.html`-Erweiterung zum Merken von URLs hinzugefügt und Probleme mit Links möglicherweise behoben. Wenn Sie immer noch Probleme haben, empfehle ich Ihnen, Netlify zu verwenden, um Ihren digitalen Garten zu hosten: Es ist kostenlos, einfach zu bedienen und unterstützt die Funktionen dieser Vorlage vollständig von Haus aus.

**`open_external_links_in_new_tab`**: Wenn es auf `true` gesetzt ist, werden externe Links in neuen Tabs geöffnet. Legen Sie diesen Wert auf `false` fest, um alle Links im aktuellen Tab zu öffnen.

**interne Links in _neuem_ Tab öffnen:**
```<a class="internal-link" href="{{ site.baseurl }}/name/" target="_blank" rel="noopener">Name</a>```

Das funktioniert gut mit internen Seiten (auch mit Notizen?).  

**`embed_tweets`**: Wenn diese Option auf `true` gesetzt ist, werden Tweet-URLs in ihren eigenen Zeilen durch eine Twitter-Einbettung ersetzt. Der Standardwert ist `false`.

### Automatische bidirektionale Verknüpfungen

Beachten Sie den Abschnitt "Anmerkungen, in denen diese Notiz erwähnt wird". Hierbei handelt es sich um einen bidirektionalen Link, der automatisch erstellt wird, wenn Sie Links zu anderen Notizen erstellen.

### Link-Vorschau

Wenn Sie ein Gerät mit Mausunterstützung verwenden, versuchen Sie, mit der Maus über interne Links zu fahren, um eine Vorschau der Notizen anzuzeigen: [[ Eine Notiz über Katzen ]].  

Links, die in der Vorschau angezeigt wurden, werden zwischengespeichert, um redundante Anforderungen zu vermeiden.

### [[bilder|Images]] und andere Markdown-Goodies

Da Sie in dieser Vorlage über die volle Leistung von Markdown verfügen, können Sie die reguläre Markdown-Syntax für verschiedene Formatierungsoptionen verwenden.

Listen funktionieren wie erwartet:

- List element A
- List element B
- List element C

1. List element
2. List element
3. List element

Wenn Sie andere Personen zitieren möchten, sollten Sie die Verwendung von Zitatblöcken in Betracht ziehen:

> Lorem ipsum dolor sit amet

Und natürlich sehen Bilder toll aus:

<img src="{{ site.baseurl }}/assets/image.jpg"/>

Sie können auch ==einige Inhalte hervorheben==, indem Sie sie mit `==` umschließen.

Nicht-lateinische Sprachen werden ebenfalls unterstützt: ==你好==, ==안녕하세요==, ==こんにちは==.

### Hervorhebung der Codesyntax

Sie können Codeblöcke mit vollständiger Syntaxfarbhervorhebung hinzufügen, indem Sie Codeausschnitte in dreifache Backticks einschließen und den Typ des Codes angeben  (`js`, `rb`, `sh`, etc.):

```js
// Here's a bit of JavaScript:
if (a === b || c == d)
  console.log('hello!')
```

```rb
# And now some Ruby
def foo(bar)
  "baz"
end
```

```sh
$ cat /dev/urandom | grep "the answer to life" # shell scripts look nice too
```


### Nächste Schritte

Diese digitale Gartenvorlage ist kostenlos, quelloffen und [hier auf GitHub verfügbar](https://github.com/maximevaillancourt/digital-garden-jekyll-template).

Der einfachste Weg, Ihren eigenen digitalen Garten auf der Grundlage dieser Vorlage zu erstellen, besteht darin, diese [Schritt-für-Schritt-Anleitung, die erklärt, wie Sie dies von Grund auf neu einrichten](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll) zu lesen.

Gehen Sie los, haben Sie Spaß und lernen Sie jeden Tag etwas Neues! ✌️
