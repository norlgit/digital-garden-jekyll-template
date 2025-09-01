---
title: 1. Das Internet
---

_(in Leichter Sprache)_  

<div class="toc">
  <h3 id="inhalt">Inhaltsverzeichnis</h3>
  <ul>
    <li><a href="#ueberschrift-1" class="toc-link">Computer sind miteinander verbunden</a></li>
    <li><a href="#ueberschrift-2" class="toc-link">Wozu kann man das Internet nutzen?</a></li>
    <li><a href="#ueberschrift-3" class="toc-link">Computer tauschen sich aus</a></li>
    <li><a href="#ueberschrift-4" class="toc-link">Wozu können Sie das Internet nutzen?</a></li>
    <li><a href="#ueberschrift-5" class="toc-link">Was ist das World Wide Web?</a></li>
    <li><a href="#ueberschrift-6" class="toc-link">Das Internet der Dinge</a></li>
  </ul>
</div>

<script>
document.addEventListener('click', function(e) {
  if (e.target.classList.contains('toc-link')) {
    e.preventDefault(); // Verhindert Standard-Link-Verhalten
    const targetId = e.target.getAttribute('href').substring(1);
    const targetElement = document.getElementById(targetId);
    if (targetElement) {
      targetElement.scrollIntoView({ behavior: 'smooth' });
    }
  }
});
</script>



<h2 id="ueberschrift-1">Computer sind miteinander verbunden</h2>

Die meisten [[überall-computer|Computer]] arbeiten nicht nur allein.  
Die meisten Computer sind mit anderen Computern verbunden.  
Wenn Computer miteinander verbunden sind, heißt das **Netzwerk**.  
  
Computer können mit Kabeln oder mit Funkwellen über die Luft miteinander verbunden sein.  
Wenn Computer mit Funkwellen miteinander verbunden sind, nennt man das **WLAN**.  
WLAN ist die Abkürzung für "Wireless Local Area Network".  
Das ist Englisch und heißt auf Deutsch "drahtloses lokales Netzwerk".  
Menschen haben Computer und alles was damit zusammenhängt erfunden.  
Sie bestimmen auch, wie Computer in Netzwerken arbeiten.  

![WLAN](assets/wlan.png)

<a href="#inhalt" class="toc-link">zurück zum Inhaltsverzeichnis</a>

<h2 id="ueberschrift-2">Wozu kann man das Internet nutzen?</h2>

Es gibt viele kleine Netzwerke, in denen Computer miteinander verbunden sind.  
Das erklären wir am Beispiel der Computer von Thomas und Esra.  

Die Computer in Thomas' Haus sind miteinander zu einem kleinen Netzwerk verbunden.  
Auch die Computer in Esras Haus sind zu einem Netzwerk verbunden.  
Es gibt viele kleine Netzwerke in vielen Häusern.  

Thomas und Esra haben verschiedene Internetanbieter.  
Auch die Computer von Esras und Thomas' Internetanbietern sind miteinander verbunden.  
Diese Computer bilden größere Netzwerke.  
Die Netzwerke aller Internetanbieter auf der Welt sind miteinander verbunden.

![Internet](assets/netzwerke1.png)  

<a href="#inhalt" class="toc-link">zurück zum Inhaltsverzeichnis</a>

## Computer tauschen sich aus <a id="ueberschrift-3"></a>

==Alle kleinen und großen Netzwerke zusammen bilden ein riesiges Netzwerk: Das Internet==.  

Über das Internet sind alle Computer in Netzwerken miteinander verbunden.  

Computer tauschen sich zum Beispiel miteinander aus, wenn Sie mit Ihrem Smartphone Bilder oder Texte an Ihre Freunde und Freundinnen schicken.  
Die Bilder und Texte kommen sofort an.  

Auch wenn Sie im Internet auf der Webseite des Paketdienstes nach Ihrem Postpaket suchen, tauscht sich Ihr Computer mit anderen Computern aus.  
Die Computer nutzen dabei die **Sprache der Computer**.  

> Sprache der Computer

> Computer tauschen sich miteinander in einer bestimmten Sprache aus.  
Die Sprache der Computer nennt man Binärcode.  
Die Sprache der Computer hat nur zwei Zeichen, nämlich die Zeichen 0 und 1.  
Der Computer wandelt zum Beispiel Bilder und Texte in viele Nullen und Einsen um.  
Diese können nun zwischen Computern hin und her geschickt werden.

---

Wie Computer sich austauschen, erklären wir mit der Geschichte von Thomas und Esra.

---

<div>
    <img src="/assets/austausch1.png">
    <p>
        Esra will das Bild einer Katze an Thomas schicken.<br>
        Dazu wandelt ihr Computer das Bild in ein Paket aus vielen Nullen und Einsen um.<br>
        Das Paket aus Nullen und Einsen wird dann über die Netzwerke von einem zum anderen Computer geschickt.
    </p>
</div>

---

<div>
    <img src="/assets/router1.png">
    <p>
        Dazu braucht man bestimmte Geräte: <strong>Die Router.</strong><br>
        Router sorgen dafür, dass die Pakete im Internet den richtigen Weg über die vielen Netzwerke finden.<br> 
        Alle Netzwerke haben Router.<br> 
        Auch die Netzwerke bei Esra und Thomas zu Hause und die größeren Netzwerke der Internetanbieter haben Router.
    </p>
</div>

---

<div>
    <img src="/assets/ip-adresse.png">
    <p>
        Dazu braucht man bestimmte Geräte: <strong>Die Router.</strong><br>
        Router sorgen dafür, dass die Pakete im Internet den richtigen Weg über die vielen Netzwerke finden.<br> 
        Alle Netzwerke haben Router.<br> 
        Auch die Netzwerke bei Esra und Thomas zu Hause und die größeren Netzwerke der Internetanbieter haben Router.
    </p>
</div>

---

<div>
    <img src="/assets/austausch2.png">
    <p>
        Das Bild wird nun nochmal in viele kleine Pakete aufgeteilt. Jedes Paket kennt die Adresse von Thomas' Computer.<br>
        Das Paket wird von einem zum anderen Router geschickt, so lange bis alle Pakete
        bei dem Computer von Thomas angekommen sind.<br>
        Dann werden die Pakete im Computer wieder zusammengesetzt und Thomas kann das Bild
        der Katze auf seinem Computer sehen.
    </p>
</div>

---

<div>
    <img src="/assets/austausch3.png">
    <p>
        Ungefähr so wie ein Brief:<br>
        Dieser wird zuerst in einen Briefkasten an der Straße geworfen.<br>
        Dann wird der Brief zu einem Postamt transportiert.<br>
        Von dort wird der Brief zu einem Postzentrum und dann wieder zu einem anderen
        Postamt transportiert.<br>
        Und irgendwann landet der Brief bei Ihnen im Briefkasten vor Ihrer Haustür.<br><br>
        Aber bei Computern kommt die Post sofort an.<br>
        Ähnlich wie Häuser haben Computer auch Nummern.
    </p>
</div>

---

Es gibt bestimmte Computer, die Server heißen.  
==Server== sind wichtig, wenn Computer sich austauschen.  

> **Server**  
> Server übernehmen für andere Computer wichtige Aufgaben.  
Zum Beispiel speichern sie Daten ab und stellen die Daten für andere Computer zur Verfügung.  
**Daten** bestehen aus Zeichen, wie zum Beispiel die Nullen und Einsen der Computersprache.  
Damit ein Computer weiß, ob es Zeichen für ein Bild oder einen Text sind, braucht er noch 
Erklärungen zu den Daten.  
Beides ist auf den Servern gespeichert.  
So wissen Computer, ob es Daten über Textdateien, Filme, Musik, eine Webseite oder etwas
anderes sind.  
**Auf Servern sind die Daten gespeichert, die Sie im Internet finden.**  
Zum Beispiel ist die Musik von einem Musikdienst auf einem Server gespeichert.  

<a href="#inhalt" class="toc-link">zurück zum Inhaltsverzeichnis</a>

## Wozu können Sie das Internet nutzen?  <a id="ueberschrift-4"></a>

Sie können das Internet für viele unterschiedliche Dinge nutzen.

---

![wikipedia](/assets/nutzen1.png) 
Sie können im Internet nach Informationen suchen.  
Bei Wikipedia können Sie sich zum Beispiel über eine Stadt oder eine Pflanze informieren.  

---

![lesen](/assets/nutzen2.png)
Sie können Artikel einer Zeitung oder Bücher im Internet lesen.  
Viele Zeitungen, die es gedruckt gibt, haben auch Artikel im Internet.  

---

![hören](/assets/nutzen3.png)
Sie können Radio und Musik hören oder Filme ansehen.

---

![kontakt](/assets/nutzen4.png)
Sie können über das Internet mit anderen Personen in Kontakt bleiben und Nachrichten
verschicken oder telefonieren.  

---

![einkaufen](/assets/nutzen5.png)
Sie können im Internet Kleidung oder andere Dinge kaufen.

---

![reisen](/assets/nutzen6.png)
Sie können auch ein Hotel für Ihren Urlaub suchen und Tickets für den Zug oder das 
Flugzeug buchen.

---

![wetter](/assets/nutzen7.png)
Sie können sich im Internet informieren, wie das Wetter wird.

---

![smarthome](/assets/nutzen8.png)
Sie können mit dem Smartphone Geräte im Haushalt steuern.

---

Und auch andere Dinge funktionieren, weil es das Internet gibt.  
Erklärungen dazu folgen.

<a href="#inhalt" class="toc-link">zurück zum Inhaltsverzeichnis</a>

## Was ist das World Wide Web? <a id="ueberschrift-5"></a>

Wir haben schon erklärt, was das Internet ist:  
Ein Netzwerk von Computern.  
Und wir haben erklärt, wie Sie das Internet nutzen können und was alles zum Internet gehört.  

Ein Teil des Internets sind Webseiten.  

- Viele Sportvereine haben eine eigene Webseite.
- Viele Firmen haben eine eigene Webseite.
- Auch Verwaltungen haben oft eine Webseite, zum Beispiel das Bürgeramt.  
  Bürger und Bürgerinnen können in vielen Städten im Internet einen Termin im Bürgeramt buchen.  
  
==Alle Webseiten auf der Welt zusammen sind das== **World Wide Web**.  
==Das ist Englisch und bedeutet auf Deutsch "weltweites Netz"==.  

Die Abkürzung für das World Wide Web ist www.  
Im World Wide Web können Sie auf Webseiten etwas lesen oder sich Bilder anschauen.  
Das Wechseln von Webseite zu Webseite nennt man **Surfen im Internet**.  

Sie können eine Webseite öffnen, indem Sie auf einen **Link** klicken.  
Eine Textzeile oder Wörter auf einer Webseite können ein Link sein.  
Auch ein Bild kann ein Link sein.  
Der Link führt zu einer anderen Webseite oder zu einem anderen Thema auf der gleichen Webseite.  

Wenn man darauf klickt, weiß der Browser, was er als nächstes anzeigen soll.  
Der **Browser** ist das Programm, mit dem Sie sich Webseiten ansehen können.  
Diese Programme haben Funktionen, die beim Surfen im Internet helfen.  
Man kann sich zum Beispiel mit Pfeilen vor und zurück bewegen.  
Dann werden die Webseiten angezeigt, die Sie schon besucht haben.  
Sie können auch Lesezeichen setzen und dann schnell auf Webseiten geleitet werden, die Sie sich oft anschauen.  

![im Internet surfen](/assets/internetsurfen1.png)

<a href="#inhalt" class="toc-link">zurück zum Inhaltsverzeichnis</a>

## Das Internet der Dinge <a id="ueberschrift-6"></a>

Computer sind in sehr vielen Geräten eingebaut.  
Immer mehr von diesen Geräten können sich auch mit dem Internet verbinden.  
Immer mehr Geräte können sich so miteinander austauschen.  

- Die Heizung im Haus kann mit dem Internet verbunden sein.  
  Die Heizung kann Informationen über die Temperatur im Haus an ein Smartphone schicken.  
  Mit dem Smartphone kann man dann die gewünschte Temperatur von überall einstellen.  
  
- Auch das Auto kann mit dem Internet verbunden sein.  
  So kann man Informationen über Staus oder das Wetter abfragen.  
  
![Internet der Dinge](/assets/internetderdinge1.png)

- Es gibt auch Uhren oder Armbänder, die man für seine Fitness nutzen kann.  
  Sie zählen zum Beispiel Schritte oder den Puls.  
  Die Uhren oder Armbänder können sich zum Beispiel merken, wie viele Schritte Sie an den unterschiedlichen Tagen der Woche gelaufen sind.  
  Diese Informationen können die Uhren oder Armbänder an das Smartphone weiterleiten.  
  Doch nicht nur an Ihre privaten Geräte können diese Informationen weitergeleitet werden.  
  Die Informationen können auch an die Firmen weitergeleitet werden, welche die Uhren oder Armbänder verkaufen.  
  Vielleicht finden Sie, dass Ihre Daten die Firmen nichts angehen.  
  
- Auch in Fabriken sind immer mehr Maschinen miteinander verbunden.  
  Maschinen in einer Fabrik können zum Beispiel überprüfen, ob ein Teil richtig gebaut wurde.  
  
==Immer mehr Gegenstände aus unserem Alltag und auf der Arbeit sind also miteinander über das Internet verbunden==.  
==Die Gegenstände tauschen sich miteinander aus==.  

==Das nennt man== **Internet der Dinge.**  

Manche finden, das Internet der Dinge sorgt dafür,
dass Menschen mehr Zeit haben.
Sie brauchen sich zum Beispiel nicht mehr darum kümmern,
dass die Heizung richtig eingestellt ist.
So können Energiekosten gespart werden.
Manche fürchten, dass die Daten nicht sicher genug sind.  

==Sie befürchten, dass immer mehr Menschen und Firmen Zugriff auf die Daten bekommen==.  
Manche haben zum Beispiel Sorge,
dass Daten eines Fitnessarmbands auch
von der Krankenversicherung gelesen werden kann.
Sie kann die Daten dann für ihre Zwecke nutzen.
Die Krankenversicherung weiß dann,
ob ein bestimmter Mensch viel oder wenig Sport macht.
Die Krankenversicherung könnte dann von Menschen,
die wenig Sport machen, mehr Geld verlangen.
Diese Menschen werden dann benachteiligt.  

==Viele Menschen befürchten auch, dass Menschen die Daten lesen könnten, die diese privaten Informationen nichts angehen==.  
Einbrecher könnten zum Beispiel herausfinden,
wann jemand schläft, aufwacht oder nicht zu Hause ist.
Zu den Zeiten könnten sie dann in das Haus einbrechen.  

weiter zum 2. Teil: [[einkaufen|Einkaufen im Internet]]


<a href="#inhalt" class="toc-link">zurück zum Inhaltsverzeichnis</a>



