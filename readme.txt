**Block 'er_anfrage' konfigurieren**
Seitenkontext = 'Überall auf der Webseite anzeigen'

**Rollen für Block 'LR-Anfrage' zuweisen**
*Rechte ändern*
moodle/block:edit  (Lecturer das Recht entziehen)

Authentifizierte/r Nutzer/in ist die Standardrolle, auf der Startseite. Diese Rolle haben ALLE User. Deshalb muss diese Rolle unbedingt das Recht 'view' haben.
Spezielle Rechte werden im Block Code definiert.

Sehen kann der Block 'er_Anfrage' nur die Rolle, die die Fähigkeit 
'moodle/course:update' besitzt (z.B. Lecturer)
