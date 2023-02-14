# blog.acamat.de

## 0 – Übersicht

* [1 – Antrieb und Anspruch](#01)
* [2 – Design](#02)
* [2.1 – Grafikdesign](#0201)
* [2.1.1 – Hervorhebungsfarbe](#020101)
* [2.1.2 – Hintergrundfarbe](#020102)
* [2.1.3 – Das a-Element](#020103)
* [2.1.? – Ausblicke](#0201__)
* [2.2 – Typographie](#0202)
* [3 – Grundgerüst](#03)
* [3.1 – Hauptseite](#0301)
* [3.2 – Übersicht](#0302)
* [3.3 – Beiträge](#0303)
* [3.4 – Formular](#0304)
* [3.5 – Impressum](#0305)

## <div id="01">1 – Antrieb und Anspruch

Nach reiflicher Überlegung habe mich dazu entschlossen, einen Blog zu betreiben und wünsche mir einen professionellen Auftritt. Dabei verfolge ich keinerlei finanzieller Interessen. Ich möchte Beiträge über mich, meine reichhaltigen Interessen, meine Meinungen und Bekenntnisse, meine Empfehlungen, meine Muttersprache und über die Erfolge meiner Arbeit am Computer veröffentlichen und somit mit der Allgemeinheit teilen. Möglicherweise findet der eine oder andere Interesse an und für sich Verwertbares in meinen Beiträgen. Ich erhoffe mir – gerne auch kritische – Rückmeldungen. 

Mein Auftritt soll meine Persönlichkeit unterstreichen: schlicht aber edel, nüchtern aber stilvoll, intellektuell, selbstbewusst und charakteristisch.  

Entscheidend für Professionalität ist vornehmlich dessen Inhalt, die Qualität meiner Beiträge. Mir ist sehr bewusst, wie wichtig auch das Grafikdesign und die Typographie dabei ist. Für den letztgenannten Bereich fühle ich mich ausreichend befähigt; dabei kann ich auf meine ausreichenden Kenntnisse in Html 5 und Css 3 bauen, die ich gerne bereit bin, zu vertiefen, falls es erforderlich wird.

Für die Frequenz meiner Beiträge peile ich einen Zyklus von etwa einem Beitrag pro Woche an. Das sollte mir ausreichend Zeit geben meiner eigenen Forderung nach Gründlichkeit und Qualität zu entsprechen.

Besonders großen Wert lege ich auf die Kommunikation mit meinen Besuchern.

Für das primäre Format zur Texterfassung plane ich [Markdown](https://de.wikipedia.org/wiki/Markdown) zu verwenden. Für diesen Zweck den Html-Quelltext zu verwenden, ist mir zu unübersichtlich und Markdown stellt einen guten Kompromiss zwischen der technischen Notwendigkeit der Auszeichnung und der erforderlichen Lesbarkeit dar. Das nachträgliche Feindesign (beispielsweise das Zuweisen der vorgesehenen Css-Klassen und die Silbentrennung) kann ich aber auch im Html-Dokument selbst vornehmen, nachdem der Inhalt feststeht. Mittlerweile habe ich ein Werkzeug gefunden, das Markdown auch in das Htm-Format überführt: [Pandoc](https://trello.com/c/M3zHcchM/25-bash-mdtohtm).

## <div id="02">2 – Design

### <div id="0201">2.1 – Grafikdesign

Ich wünsche mir ein dunkles Design, möchte aber kein reines Schwarz als Hintergrund­farbe verwenden. Auch möchte ich kein reines Weiß als Vordergrundfarbe nehmen. Ich nenne Ihnen einige Beispiele, die mir gut gefallen. Ich hoffe, dass reicht Ihnen aus, sich einen Eindruck von meinen Vorstellungen zu verschaffen.

* [Mein WebHoster](https://netbuild.net/)
* [Zeever](https://wordpress.org/themes/zeever/)  
Die konsequente Verwendung der Hervorhebungsfarbe gefällt mir. Das müsste man lediglich an meinen Farbton anpassen. Auch die deutliche Hervorhebung des aktiven Elements durch Invertieren der Farben ist eine Überlegung wert.
* [Blockline](https://wordpress.org/themes/blockline/)  
Dieser Entwurf kommt meinen Vorstellungen schon recht nahe. Besonders das Farbschema; der Blauton des Hintergrund sollte zu meiner Hervorhebungsfarbe schon recht gut passen.
* [Building-Construction](https://wordpress.org/themes/building-construction/)  
An diesem Entwurf gefällt mir die grafische Absetzung der einzelnen Elemente durch eine leicht geänderte Hintergrundfarbe. Dies könnte als Vorlage für die Zusammenfassung meiner neusten Beiträge auf der Hauptseite dienen. Wichtig ist mir übrigens: Die grafische Repräsentation der Elemente durch Verwendung einer Svg?-Grafik (wie hier das stilisierte „W“). Für die Linienfarbe der Symbole würde ich meine Hevorhebungsfarbe bevorzugen, wie bei [Zeever](https://wordpress.org/themes/zeever/).
* [Spice-Software-Dark](https://wordpress.org/themes/spice-software-dark/)  
Gefällt mir ebenso; besonders die Darstellung des Datum des Beitrags.

 #### <div id="020101">2.1.1 – Hervorhebungsfarbe
 
 Ich wünsche mir eine einheitliche Hervorhebungsfarbe zu verwenden und möchte sie für die folgenden Textelemente verwenden:

 * Überschriften (h1 und h2; h3 und h4 finden erst später ihre Verwendung)
 * [Initiale](https://de.wikipedia.org/wiki/Initiale)
 * Fettmarken
 * Rahmenfarbe zur Hervorhebung des aktuellen Elementes
 * Interne Verlinkungen
 
 Ich würde gerne die meiner jetzigen Präsenz weiterverwenden: `#FFA51E`. Dazu benötige ich einen passenden Dunkelblauton als Hintergrund. Es wäre Ihre Aufgabe, eine entsprechende Abstimmung vorzunehmen.

#### <div id="020102">2.1.2 – Hintergrundfarbe

Ich stelle mir für die Hintergrundfarbe einen sehr dunklen Blauton in verschiedenen Abstufungen vor. Dabei möchte ich auf Farbverläufe verzichten. Diese Abstufen sollen mir als grafische Unterstützung der Strukturierung dienen. Der Blauton von [Blockline](https://wordpress.org/themes/blockline/) kommt meinen Vorstellungen schon recht nahe. Lässt sich das ästhetisch mit der angestrebten Hervorhebungsfarbe vereinbaren?

#### <div id="020103">2.1.3 – Das a-Element

Als Einleitung meiner Recherche über das Thema _Suchmaschinenoptimierung_ habe ich eine Sitzung mit „ChatGgt“ abgehalten, um mir einen ersten Überblick zu verschaffen. Der Automat riet mir unter anderem:

* Bauen Sie Backlinks von anderen hochwertigen Websites auf, um die Glaubwürdigkeit Ihrer Website zu stärken.

Das möchte ich gerne umsetzen. Dabei gefällt mir die Umsetzung bei „Trello“. Ich möchte das „favicon“ der Site aber einen eigenen Anzeigetext (Ubuntu Condensed?) verwenden. Besonders wichtig erscheint mir das Vorschaufenster beim „Mouse-Over“, das mir beispielweise bei Artikel der Wikipedia vorbildlich gepflegt zu sein scheint. Der Besucher muss die verlinkte Seite nicht erst besuchen, um sich einen ersten Eindruck zu verschaffen.

Sind Sie mit der technischen Gegebenheiten soweit vertraut, dass Sie das für mein Design nachstellen können?

Für site-interne Verlinkungen würde ich gerne diese an [Spice-Software-Dark](https://wordpress.org/themes/spice-software-dark/) anlehnen. Benötige ich eine gesonderte Vordergrundfarbe beim „Mouse-Over“ oder sollte ich wie in diesem Beispiel ebenfalls die Hervorhebungsfarbe als Hintergrundfarbe verwenden?

#### <div id="0201__">2.1.? – Ausblicke

Ich plane mittelfristig meine bisherige Internetpräsenz in das neue Design von Ihnen zu migrieren. Dazu benötige ich Ihre Hilfe für die

* Gestaltung meiner Tabellen  
In der jetzigen Form setzte ich viele, hoffentlich in der dafür vorgesehenen Weise, Tabellen ein. Deren Gestaltung benötigt eine Auffrischung.

* Gestaltung der Dokumention meiner Software-Bibliotheken  
Auch hier wäre ein Zuschneiden Ihres Designs auf die besonderen Anforderungen erforderlich. Neben Verwendung einer „monospaced“-Schriftart (Ubuntu Mono?) benötige eine neue Farbklasse für die Hervorhebung von Schlüsselworten. Anlehnen möchte mich an die [.Net-Dokumentation](https://learn.microsoft.com/de-de/dotnet/api/system.dateonly.-ctor?view=net-7.0#system-dateonly-ctor(system-int32-system-int32-system-int32)).

Für beide Vorhaben werde ich Ihnen gesonderte Aufträge erteilen.

### <div id="0202">2.2 – Typographie

Ich wünsche als Grundschriftart [Ubuntu](https://design.ubuntu.com/font) zu verwenden. Diese kann ich nach meinen In­formationen lizenzfrei einsetzen. Ich plane den Einsatz der Schrifttypen „Condensed“, „Mono“ und „Regular“. Allerdings kann ich nicht abschätzen, ob sich diese Schriftart auch den Einsatz im Web eignet; ich sehe es als Ihre Aufgabe an, mich in dieser Frage zu beraten. 

Für die Gestaltung meiner Beiträge möchte ich die Schriftfamilie [Warnock](https://www.linotype.com/de/48092/warnock-schriftfamilie.html) von Adobe zu verwenden. Eine diesbezügliche Lizenzierung habe ich bereits vorbereitet. Auch in diesem Fall dürfen Sie mich gerne beraten.

## <div id="03">3 – Grundgerüst

Mein Blog soll im ersten Schritt folgende fünf Seiten enthalten:

* Hauptseite
* Übersichtsseite für meine Beiträge jeder Kategorie
* Seite für den vollständigen Beitrag
* Formular für E-Mail-Nachrichten
* Impressum

Jede dieser Seiten soll im linken Bereich auf die Hauptseite, die Übersichtsseite, das E-Mail-Formular(?) und das Impressum verlinken.

### <div id="0301">3.1 – Hauptseite

Auf der Hauptseite benötige ich einen Titelbereich für meinen Nick, meinem Klar­textnamen, mein Profilfoto und möchte meinen Avatar und mein favicon weiterverwenden.

Ich plane auf dieser Seite etwa fünf meiner letzten Beiträge vorzustellen. Dort soll der Titel meines Beitrags, das Veröffentlichungsdatum, die Zusammenfassung und ein Zitat meines Beitrags in Form der reinen Absätze erscheinen; es entfällt also die Strukturierung der Beiträge. Insgesamt sehe ich eine Kürzung meines Beitrags auf einige Zeilen (fünf bis sieben) vor. Mir ist völlig bewusst, dass dies eine doppelte Pflege der Inhalte bedeutet. Das muss ich wohl oder übel in Kauf nehmen. Abschließend möchte ich eine Verlinkung auf den vollständigen Beitrag vornehmen. Dieses Element soll eine deutlich abgegrenz­te, gerahmte Einheit bilden.

### <div id="0302">3.2 – Übersicht

### <div id="0303">3.3 – Beiträge

Zunächst plane ich folgende Kategorien/Rubriken meiner Beiträge:

* Über mich und meine Interessen
* Meine Meinungen und Bekenntnisse
* Meine Empfehlungen
* Meine Muttersprache
* Meine Erfolge bei meiner Computerarbeit

Zunächst möchte ich eine Beschreibung der Beitragskategorie voranstellen. Sie soll erläutern, welcher Art die Beiträge hier vertreten sind und welchen Antrieb und welches Ziel ich damit verfolge.

Ich möchte mich bei der Gestaltung meiner Beiträge an dem Layout der Papierausgabe von _Die Zeit_ orientieren [Beispiel](https://github.com/AcamatAcubens/Blog/blob/main/documents/DieZeit_2306.pdf). Also

* Stichwort(e)
* Kategorie/Rubrik
* Überschrift
* Kurzfassung
* Text

Die Stichworte würde ich gerne, ähnlich wie Tags mit einem Rahmen mit abgerundeten? Ecken versehen. Dazu will ich die Schriftart „Ubuntu (Condensed?)“ einsetzen [Siehe](https://trello.com/c/xoHeElKt/28-style-das-span-element-f%C3%BCr-schl%C3%BCsselworte).

Für den ersten Absatz möchte ich ebenfalls Initiale verwenden. Bei den darauffolgenden Absätzen möchte ich die erste Zeile mit einem Einzug versehen. Auch möchte ich Zwischenüberschriften verwenden und die darauf folgenden Absätze sollen nicht einge­zogen werden.

Beiträge der Kategorie Empfehlungen enthalten auch Buch-Rezensionen. Dafür brauche eine Informationsbox für die Bezugsdaten. Auch brauche das Gleiche, oder Ähnliches für Zitate.

Noch nicht entschieden habe ich, ob ich auch das mehrspaltige Layout verwenden soll. Wohl eher nicht. Was ist Ihre Meinung dazu? Print ist schließlich nicht gleich Web.

### <div id="0304">3.4 – Formular

Ich bin tatsächlich unsicher, ob ich ein Formular verwenden soll. Nach meinem Empfinden, verzichte ich ungern auf meinen Texteditor bei der Erstellung meiner Texte (tatsächlich verwende ich ihn, lass ihn auf Korrektheit überprüfen und kopiere ihn dann in das Textfeld). Was mich aber stört, dass ich über keine Dokumentation verfüge, wann ich was geschrieben habe. Das ist bei einer E-Mail-Nachricht anders. Diese landet nach dem Versenden automatisch im „Gesendet“-Ordner

Vielleicht es besser, nur eine deutliche Angabe über Verlinkung mit der Verwendung von „mailTo“ anzubieten, bei dessen Folgen sich der E-Mail-Client des Anwender öffnet. Es erspart Platz und ermöglicht ein direkteren Kontakt, anstatt zunächst eine neue Seite öffnen zu müssen. Das Spam-Risiko dürfte etwa ähnlich sein, denn in beiden Fällen ist die verwendete E-Mail-Adresse über den Quelltext der Seite einsehbar.

### <div id="0305">3.5 – Impressum

Mir ist völlig bewusst, dass ich als Privatperson nicht verpflichtet bin, ein Impressum vorzu­weisen. Da ich gedenke, mich gelegentlich auch scharf-kritisch zu äußern möchte mich gegen etwaige Angriffe von Abmahnungsanwälten immunisieren, indem ich meine gesetzliche Pflicht übererfülle. Für Verweise auf die Dsgvo kann ich – zumindest im ersten Schritt – wohl vollkommen verzichten, da meine Site keine personen-gebunden Daten erhebt, verarbeitet oder speichert.
