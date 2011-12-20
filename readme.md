README
======
Benutzung
---------
Diese LaTeX-Vorlage ist mit Beispiel-Inhalten gefüllt, die angepasst werden müssen.  
Wichtig hierbei sind die `KomaVars` in der Datei bretschner.lco.  
Es kann eine eigene lco-Datei angelegt werden. Es muss lediglich der documentclass-Befehl angepasst werden:  
	`\documentclass[bretschner, ownlco]{scrlttr2} `
### LCO-Datei ###

	\ProvidesFile{bretschner.lco}[DINmtext]
	\KOMAoptions{fromalign=right, foldmarks=h, fromphone, fromemail}
	\setkomavar{fromname}{Max~Muster}
	\setkomavar{fromaddress}{Musterstra{\ss}e~12\	\01234~Musterstadt}
	\setkomavar{fromphone}{+49\,123\,45~678~901}
	\setkomavar{fromemail}{info@example.com}
	\endinput



Kontakt
-------

Bei Fragen, Problemen, Anregungen und Kritik kann man mich über meinen [Blog](http://blog.kanedo.net) erreichen.   

## Abhängigkeiten
Um diese Vorlage unter Unix-System zu verwenden, muss das `ltabelx`-Paket installiert werden. Zu finden ist es auf der [Projektseite](http://ctan.org/tex-archive/macros/latex/contrib/ltablex) und wird wie folgt installiert (Mac OS X):

	$ cd /usr/local/texlive/texmf-local/tex/latex/local
	$ open .

Entpakter ZIP-Ordner in den geöffneten Ordner kopieren und mittels 

	sudo texhash

die LaTeX-Installation erneuern.	 
