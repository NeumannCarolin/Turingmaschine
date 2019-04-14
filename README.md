# Turingmaschine
Deterministische Turingmaschine   erstellt mit Hilfe von Latex und Tikz  eine Slideshow wie die eingegebene determinisitsche Turingmaschine feststellt ob sie mit dem Eingabewort und allen weiteren Eingaben terminiert oder nicht.

## main.py
	Eingaben:
		Bandinhalt, z.B. 1,0,1,0 
		Datei mit Turingmaschine, sollte folgendermaßen formatiert sein:
			Anzahl an Bändern|Anzahl an Zuständen|Eingabealphabet|Bandalphabet|Leerzeichen|akzeptierende Zuständen
			derzeitiger Zustand,gelesenes Zeichen > nächster Zustand, zu schreibendes Zeichen, Bewegung des Bandes

			z.B. algo3:
				1|3|0,1|0,1,?|?|0
				q0,0>q0,0,R
				q0,1>q1,1,R
				....
		gewünschter PDFviewer, mit d wird der Defaultviewer benutzt

## tm.py
	erstellt die einzelnen Schritte die die Turingmaschine abläuft

## visual.py
	erstellt mit Hilfe von Latex und Tikz 
	eine Slideshow wie die determinisitsche Turingmaschine
	feststellt ob sie mit dem Eingabewort terminiert oder nicht.

	Visualisierung ist nur für eine 1 Band TM möglich
