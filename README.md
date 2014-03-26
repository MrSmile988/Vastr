<img src="http://www.vastr.de/img/logo.png" alt="Vastr" />
=====

The open source faster reading experience

http://www.vastr.de/anleitung.html

Vastr besteht aus einer Javascript-Datei, die einen HTML5 Canvas erzeugt und diesen in eure Seite lädt. Wurde die vastr.js Datei auf dem Server hochgeladen, muss zunächst die Javascript-Datei eingebunden werden. Achtet dabei auf den richtigen Pfad zu der Datei! Bei mir liegt die vastr.js in dem Ordner "js". Vastr setzt jQuery (1.9.1 oder höher) voraus, also achtet darauf, dass Vastr erst nach jQuery eingebunden wird! Beispiel:

<code>&lt;head&gt;<br />
&lt;!-- jQuery einbinden --&gt;<br />
&lt;script src="js/jquery.js"&gt;&lt;/script&gt;<br />
&lt;!-- Vastr nach jQuery einbinden --&gt;<br />
&lt;script src="js/vastr-0.4350.js"&gt;&lt;/script&gt;<br />
&lt;/head&gt;</code>

Weiterhin werden zwei DIV-Elemente benötigt. Einmal muss an einer beliebigen Stelle der Vastr-Reader eingefügt werden mit:

<code>&lt;div id="vastr"&gt;&lt;/div&gt;</code>

Der Text, der über den Vastr-Reader angezeigt werden soll, muss jetzt nur noch wie folgt markiert werden:

<code>&lt;div id="vastr-input"&gt;<br />
Hier kommt der Text für Vastr rein.<br />
&lt;/div&gt;</code>

Dabei können natürlich auch unterschiedliche Inhalte eingebunden werden, wie z.B. im folgenden Beispiel:

<code>&lt;div id="vastr-input"&gt;<br />
&lt;h1&gt;Hier ist meine Überschrift.&lt;/h1&gt;<br />
&lt;p&gt;Hier kommt der weitere Inhalt rein.&lt;/p&gt;<br />
&lt;/div&gt;</code>

Das ist alles! Wenn die Anleitung befolgt wurde, müsste Vastr nun erfolgreich der eigenen Seite / dem eigenen Projekt eingebunden sein.
