---
output: 
  pdf_document:
    citation_package: biblatex
bibliography: [book.bib, test.bib]
biblio-style: verbose
link-citations: true
always_allow_html: true
geometry: "left=3cm,right=3.5cm,top=2cm,bottom=2cm"
header-includes:
  - \usepackage{setspace}
  - \onehalfspacing
  - \usepackage{tabu}
toc-title: Inhaltsverzeichnis
---

\renewcommand{\figurename}{Abbildung}
\renewcommand{\tablename}{Tabelle}
\renewcommand{\listfigurename}{Abbildungsverzeichnis}
\renewcommand{\listtablename}{Tabellenverzeichnis}

\pagenumbering{Roman}

\newpage{}

\listoffigures
\addcontentsline{toc}{section}{Abbildungsverzeichnis}

\newpage{}

\listoftables
\addcontentsline{toc}{section}{Tabellenverzeichnis}

\newpage{}

\pagenumbering{arabic}



# Einführung {#introduction}

Die Verwaltung von Messmitteln am Fachgebiet Fahrzeugantriebe der Technischen Universität Berlin gestaltet sich schwierig. Zurzeit werden Messmittel dezentral verwaltet. Die handelnden Personen besitzen wenig Information über den Ausleihzustand einzelner Messmittel über verschiedene Projekte hinweg. Daher hat sich das Fachgebiet entschlossen, im Rahmen des Moduls "Projekt Fahrzeugantriebe" eine Web-Applikation zur Verwaltung von Messmitteln zu erstellen. Diese Web-Applikation soll die Ausleihe und Rückgabe einzelner Messmittel über einen QR-Code realisieren. Darüber hinaus sollen Messmittel gruppiert, zusätzliche Informationen, wie zum Beispiel Datenblätter für Messmittel, bereitgestellt und der Bestand von Messmitteln erfasst werden. Um die unterschiedlichen Verantwortlichkeiten der Akteure zu berücksichtigen, ist zudem eine rechtebasierte Nutzerverwaltung vorzusehen.

Der Inhalt dieses Berichtes umfasst die Dokumentation des Arbeitsprozesses, die Beschreibung des finalen Produktes hinsichtlich technischer Umsetzung und Funktionalität und zeigt zusätzlich Anknüpfungspunkte für Folgeprojekte auf.

Messmittel = Sensor [@R-rmarkdown]
