# StudentsBook
Aplikacja - elektroniczny dziennik

1. Projekt (2xRAR)
2. Dokumentacja (PDF)
3. Backup bazy - MS SQLServer (bak)

Aplikacja działa na lokalnym serwerze (localhost:5000), więc należy przywrócić bazę z pliku bak, oraz dostosować Connection String w pliku appsettings.json.

"DbConnS": "Server=(LocalDb)\\MSSQLLocalDB;Database=SchoolBook;Trusted_Connection=True;MultipleActiveResultSets=True"
