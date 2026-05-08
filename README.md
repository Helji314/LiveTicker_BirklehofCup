<h1>User Guide</h1>
<p>Der Birklehof Cup Live Ticker ist eine Smartphone-optimierte live Darstellung der aktuellen Spielstände und Zeiten. </p>
<img width="745" height="1441" alt="image" src="https://github.com/user-attachments/assets/ab13f462-c73a-4fa3-8737-8e5f5bfc36c8" />
<br><br>
<p>Dafür sollten keine Änderungen an den Dateien "styles.css" oder "index.html" vorgenommen werden!</p>
<p>Wenn du für das Eintragen der Spielestände verantwortlich bist, öffne den Codeeditor (VS Code) auf dem bereitgestellten Gerät. Hier liegt die Datei <a href="schedule.json" >schedule.json</a> schon im Vordergrund.</p>
<p>Den Großteil der hier gegebenen Daten brauchst du nicht zu Verändern. Nur die Zeilen:<br><br>
      "results": {<br>
        "Birklehof": null,<br>
        "Bieberstein": null,<br>
        "St. Blasien": null<br>
      },<br>
sind für dich interessant. Dies ist die JSON-Datenbank, von der der Ticker live seine Daten nimmt - jede gespeicherte Veränderung beeinflusst also das Live-System!</p>
<p>Bitte verändere nichts an diesem Code, außer den Werten von "results" der einzelnen Schulen!</p>
<p>Auch die Zeit wird automatisch aktualisiert, jede außerplanmäßige Veränderung könnte das System zum Abbruch zwingen oder einen Fehler auslösen.<br>
Sollte dies der Fall sein, rufe mich bitte unter +49 159 060 43637 an. </p>
<p>Falls du dir nicht sicher bist, ob etwas außer den Werten des Spielstandes und der Gesammtwertung verändert ist, kannst du in der Kopfzeile des Codeeditors den Vergleich mit einer Sicherheitskopie betrachten. Für die Bearbeitung wechsle aber bitte zurück auf die Datei selber. </p>
<br><br>
<p>Ist ein Spiel beendet und der Spielestand kann online gestellt werden, speichere deine Ergebnisse und trage sie zur Sicherheit auch auf dem Papier ein!</p>
<p>Genauere Anweisungen zum Onlinestellen der Inhalte erhältst du vor Spielbeginn, es gibt aber auch online Dokumentationen wie <a href="https://github.com/orgs/community/discussions/43766">diese hier</a>.</p>
<p>Viel Spaß und Erfolg beim Birklehof Cup!</p>
