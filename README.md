Vastr
=====

The open source faster reading experience

http://www.vastr.de/anleitung.html

Vastr besteht aus einer Javascript-Datei, die einen HTML5 Canvas erzeugt und diesen in eure Seite lädt. Wurde die vastr.js Datei auf dem Server hochgeladen, muss zunächst die Javascript-Datei eingebunden werden. Achtet dabei auf den richtigen Pfad zu der Datei! Bei mir liegt die vastr.js in dem Ordner "js". Vastr setzt jQuery (1.9.1 oder höher) voraus, also achtet darauf, dass Vastr erst nach jQuery eingebunden wird! Beispiel:

<head>
<!-- jQuery einbinden -->
<script src="js/jquery.js"></script>
<!-- Vastr nach jQuery einbinden -->
<script src="js/vastr-0.4350.js"></script>
</head>

Weiterhin werden zwei DIV-Elemente benötigt. Einmal muss an einer beliebigen Stelle der Vastr-Reader eingefügt werden mit:

<div id="vastr"></div>

Der Text, der über den Vastr-Reader angezeigt werden soll, muss jetzt nur noch wie folgt markiert werden:

<div id="vastr-input">
Hier kommt der Text für Vastr rein. 
</div>

Dabei können natürlich auch unterschiedliche Inhalte eingebunden werden, wie z.B. im folgenden Beispiel:

<div id="vastr-input">
<h1>Hier ist meine Überschrift.</h1>
<p>Hier kommt der weitere Inhalt rein.</p>
</div>

Das ist alles! Wenn die Anleitung befolgt wurde, müsste Vastr nun erfolgreich der eigenen Seite / dem eigenen Projekt eingebunden sein.
