# Web Accessibility

IND4IL Inclusive Design | 14.05.2025 | Wolfgang Hochleitner

Setzen Sie sich mit dem Thema barrierefreies Web auseinander, indem Sie die vorgegebene Portfolio-Seite nach den WCAG
2.2 mithilfe der WCAG-EM Methodik evaluieren. Stellen Sie fest, ob die Webseite Level A der Guidelines erfüllt, oder ob
Sie Anpassungen vornehmen müssen.

## Accessibility – WCAG 2.2 Level A mit WCAG-EM

Überprüfen Sie, ob die vorgegebene Portfolio-Website Level A
der [Web Content Accessibility Guidelines 2.2 (WCAG 2.2)](https://www.w3.org/TR/WCAG22/) erfüllt. Verwenden Sie das
dafür vom W3C zur Verfügung gestellte WCAG-EM Report Tool und die Quick Reference und arbeiten Sie diese durch.

### Den Report vorbereiten

1. Öffnen Sie zunächst das [WCAG-EM Report Tool](https://www.w3.org/WAI/eval/report-tool/) und lesen Sie sich die
   Einleitung ("About this tool") auf dieser Seite dazu durch.
2. Klicken Sie rechts auf `Start New Report` und tragen Sie auf der folgenden Seite die grundsätzlichen Daten für die
   Evaluierung ein (Sie können dies auf Deutsch oder Englisch tun, das Report Tool selbst ist leider nicht auf Deutsch
   verfügbar):
    1. **Website name:** Der Name der Seite.
    2. **Scope of the website:** Hier wird eingetragen, welche Teile einer Webseite evaluiert werden. Da die Seite eine
       Singe-Page-Seite darstellt, genügt es hier einzutragen, dass Sie die gesamte Seite evaluieren.
    3. **WCAG Version:** WCAG 2.2.
    4. **Conformance target:** Level A.
    5. **Accessibility support baseline:** Hier werden die verwendeten Technologien aufgelistet. Tragen Sie hier den
       Browser ein, mit dem Sie testen. Wenn Sie einen Screenreader ausprobieren, geben Sie das hier ebenfalls an.
    6. **Additional evaluation requirements:** Beschreiben Sie hier eventuelle optionale Kriterien, dies kann auch leer
       gelassen werden.
3. Wählen Sie rechts unten `Next step: Explore Website` aus und tragen Sie die für die Webseite zutreffenden Details
   ein. Die Webseite zu erkunden ist bei der Portfolio-Webseite nicht sehr aufwändig.
    1. **Web Technologies Relied Upon:** Wählen Sie hier die verwendeten Technologien aus. Auf jeden Fall HTML und CSS,
       falls Sie SVG-Grafiken verwenden auch SVG. Wenn JavaScript inkludiert ist, kreuzen Sie auch hier die Checkbox an.
    2. **Optional Exploration Notes – Essential functionality of the website:** Hier können Sie sich Notizen zur
       Funktionalität der Seite machen (z.B. "Portfolio und persönliche Informationen" oder "Ausfüllen eines
       Kontakt-Formulars").
    3. **Optional Exploration Notes – Variety of web page types:** Hier können Sie optional angeben, welche Typen von
       Unterseiten es zu evaluieren gibt. Da es nur eine Seite ist, kann dies leer gelassen oder mit einer Angabe wie
       "Portfolio Seite" ausgefüllt werden.
4. Wählen Sie `Next step: Select Sample` und geben Sie die Seiten an, die Sie evaluieren. Da sie nur eine Seite haben,
   ist dieser Prozess nicht sehr umfangreich.
    1. **Structured Sample Web Pages:** Klicken Sie `Add web page` und eben Sie beim strukturierten Sample die
       Hauptdatei (`index.html`) an. Nachdem Sie keinen URL haben, tragen Sie ins erste Feld (Short name) den Dateinamen
       ein und dann eine Beschreibung (z.B. "Hauptseite").
    2. **Randomly Selected Sample:** Hier wären *zusätzlich* zum strukturierten Sample noch Dateien zufällig
       auszuwählen. Da die Seite aber nur aus einer Webpage besteht, kann dies leer gelassen werden. Normalerweise muss
       das zufällige Sample aus 10 % des Gesamtsamples bestehen.
5. Klicken Sie auf `Next step: Audit Sample` und führen Sie die tatsächliche Evaluierung durch (siehe nächster
   Abschnitt). Tragen Sie die Ergebnisse im Report Tool entsprechend ein. Wenn Sie unter "Add results for pages" nichts
   auswählen, so bezieht sich der Report auf das gesamte Sample. Es läuft somit auf dasselbe hinaus.

### Die Webseite evaluieren

1. Beginnen Sie im Report Tool bei Erfolgskriterium *1.1.1 Non-text Content* und klappen Sie zunächst durch Klick auf
   `Show full description` die Beschreibung für dieses Kriterium aus, um es zu verstehen. Bei den Buttons
   `Understanding 1.1.1` und `How to meet 1.1.1` bekommen Sie noch weitere Informationen bzw. nützliche Tipps, wie sie
   dieses Kriterium erreichen können. Tipp: passen Sie sich die *How to Meet WCAG 2.2* Liste über den "Filter" Tab links
   an und wählen Sie Level A und nur HTML und CSS als Technologien. Die "Sufficient Techniques" sind in der Regel auch
   ausreichend.
2. Bewerten Sie nun, wie dieses Kriterium auf der Webseite erfüllt ist. Überprüfen Sie also, ob alle Bilder
   Alternativtext enthalten. Wenn dies der Fall ist, wählen Sie unter "Outcome" `Passed` und tragen Sie unter "
   Observations" einen Kommentar ein. Wenn es nicht erfüllt ist, wählen Sie `Failed` und notieren Sie, wo Probleme
   aufgetreten sind.
3. Fahren Sie nun mit Erfolgskriterium 1.2.1 fort. Wenn Sie hier etwa weder Audio noch Video in der Seite verwenden,
   wählen Sie `Not present` und fügen Sie einen kurzen Kommentar ein.
4. Evaluieren Sie nun die restlichen Punkte.
5. Wählen Sie nun `Next step: Report Findings` und tragen Sie die verbleibenden Daten ein:
    1. **Evaluation commissioner:** Die Person, die die Evaluierung in Auftrag gegeben hat. Entweder Sie selbst oder der
       Übungsleiter.
    2. **Evaluator:** Ihr Name.
    3. **Executive summary:** Geben Sie eine kurze Zusammenfassung zur Evaluierung an.
6. Wählen Sie nun `Next step: View Report` und sehen sie sich die Resultate ihrer Evaluierung an. Sie können die drei
   zur Verfügung gestellten Dateien (Report-HTML, Report-CSS und Reportdaten als JSON) herunterladen und abspeichern.
   Somit ist der Report jederzeit verfügbar.

Die Granularität Ihres Berichts bestimmen Sie. Der primäre Zweck ist, die WCAG praktisch einzusetzen und sich damit
auseinanderzusetzen, nicht einen perfekten Report zu verfassen. Es ist ebenso nicht wichtig, dass jeder Punkt `Passed`
aufweist. Vielmehr soll ehrlich evaluiert werden, um einen Überblick über den Barrierefreiheitsstatus der Webseite zu
bekommen. Ziel soll es lediglich sein, dass keiner der Punkte mehr den Status `Not checked` hat.

## Accessibility-Tools

Sie können zur Unterstützung diverse Tools und Validatoren verwenden, seien Sie sich allerdings bewusst, dass diese
selten alle Punkte finden bzw. überhaupt finden können (z.B. einfach gehaltene Sprache). Manche Validatoren überprüfen
auch nur Teilaspekte, oder halten sich nicht strikt an WCAG 2, sondern zeigen eher generell Probleme auf.

Die Accessibility-Tools lassen sich grob in Online-Tools und Browser-Extensions gliedern.

### Online-Tools

Online-Tools erlauben das Überprüfen einer Webseite, ohne dass etwas lokal installiert werden muss. Folgende
Online-Validatoren könnten nützlich sein:

- [MAUVE++ (WCAG 2.1)](https://mauve.isti.cnr.it/),
- [Ace it (WCAG 2.1 AA)](https://ace.useit.se/ax/aceit.php?lang=en),
- [WebAIM Wave](https://wave.webaim.org/) (für lokale Seiten nur mit Chrome- oder Firefox-Extension),
- [WebAIM Color Contrast Checker](https://webaim.org/resources/contrastchecker/).

### Browser-Extensions

Browser-Extensions ermöglichen detailliertere Ergebnisse, erfordern jedoch die Installation im eigenen Browser. Damit
die Tools funktionieren, muss die Webseite online sein oder lokal über den Webserver des
Docker-Containers (`fhooe-web-dock`) bzw. über PhpStorm und `localhost` (mithilfe der Browser-Buttons) aufgerufen
werden. Folgende Tools sind empfehlenswert:

- [Lighthouse](https://developer.chrome.com/docs/lighthouse/): In Chrome/Edge/Opera aufrufbar über F12 im Tab
  "Lighthouse". Analysiert verschiedenste Qualitätsaspekte der Webseite, darunter die Accessibility.
- [Accessibility Insights for Web](https://accessibilityinsights.io/): Verfügbar als Chrome/Edge Extension oder
  Desktop-Anwendung. Erlaubt eine "FastPass"-Evaluierung für die gängigsten Probleme oder eine detaillierte Evaluierung.
- [ARIA DevTools](https://chrome.google.com/webstore/detail/aria-devtools/dneemiigcbbgbdjlcdjjnianlikimpck?hl=en):
  Chrome Extension, das die semantische Struktur einer Webseite anzeigt und damit darstellt, wie Screenreader sie sehen.

Verwenden Sie mehr als nur ein Accessibility Tool, um auf eventuelle Probleme der Website aufmerksam zu werden.
Diese Tools sind nicht perfekt und sollten daher nur als Ergänzung zu einer händischen Evaluierung gesehen werden.
