# WebAppForBugTracking

PLAN:
Saptamana 1: Interfata
Saptamana 2: REST API

SPECIFICATII:
- Baza de date in SQL
- Structura bazei de date:
    - users.sql: ID, userType, name, password
    - bugs.sql: ID, summary, asignee, severity, priority, description, commitLink
    - projects.sql: ID, name
- Tipuri de user: admin, MP, TST
    - MP: inregistrare proiect, vizualizare bug-uri, actualizare/inchidere bug-uri
    - TST: adaugare bug
    - admin: access complet la baza de date
- bug: id, summary, severitate, prioritate, descriere, link la commit, asignee(MP)
