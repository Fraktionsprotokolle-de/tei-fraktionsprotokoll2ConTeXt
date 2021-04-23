# tei-fraktionsprotokoll2ConTeXt
Entwicklung einer ConTeXt-Umgebung, um TEI-P5 in der Variante der Fraktionsprotokolle direkt mittels ConTeXt setzen zu können.

Um es auszuprobieren, ist eine aktuelle Installation von ConTeXt notwendig (bspw. via https://www.tug.org/texlive/).

Sobald ConTeXt installiert ist, reicht der Aufruf von `context --environment=frakstil DATEINAME.xml` um ein PDF zu erzeugen.

Alle wichtigen Informationen werden als Text dargestellt. Sprechernamen sind fett, erwähnte Namen vom Typ Person sind kursiv. Organisationen, Bibliogrphien etc. werden aktuell nicht optisch hervorgehoben.



To-Do:
- der Inhalt des Elements Name Type=Organisation wird noch nicht angezeigt (vergessen)
- Inhalt des Elements für Orte (obsolet) muss noch angezeigt werden
- Metadaten aus dem teiHeader (Titel, Fraktion, Datum)
- Abkürzungen
- Layout & Mengensatz verbessern (Silbentrennung? Eventuell linksbündig setzen?)
- incidents? Wie darstellen?
