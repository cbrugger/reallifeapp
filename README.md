# Beispielanwendung für Openshift Origin (Real Life App)
Basiert auf dem JBoss Quickstart Projekt "kitchensink".
Veränderungen wurden lediglich an der persistence.xml vorgenommen.

Damit diese mit MySQL funktioniert mussten folgende Änderungen vorgenommen werden:

1. KitchensinkDS -> MySQLDS
2. Hibernate Property hibernate.dialect für MySQL wurde hinzugefügt

Anleitung (Deployments in Openshift) ist unter https://blog.doubleslash.de/neue-anwendungen-openshift-origin-erstellen/ verfügbar.
