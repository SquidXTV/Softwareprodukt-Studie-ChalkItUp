## Test 1: Persönliches Leaderboard erstellen
Testen Sie, ob ein Benutzer ein neues Leaderboard mit einem benutzerdefinierten Name erfolgreich erstellen kann.
Nach Eingabe des Namens und Hinzufügen von mindestens zwei Spielern soll das Leaderboard gespeichert werden und
in der Leaderboard-Übersicht angezeigt werden.

## Test 2: Validierung bei zu wenigen Spielern
Testen Sie, ob eine aussagekräftige Fehlermeldung angezeigt wird, wenn der Benutzer versucht, ein Leaderboard mit weniger als
zwei Spielern zu erstellen. Überprüfen Sie außerdem, ob der "Erstellen"-Button in diesem Fall deaktiviert ist und keine Erstellung
möglich ist.

## Test 3: Filterung des Leaderboards
Testen Sie, ob das Leaderboard korrekt auf die gewählten Filter reagiert. Wird z.B. die Spielart "8-Ball" und der Spielmodus "Einzel" ausgewählt, sollen nur Spiele und Spieler
angezeigt werden, die diesen Kriterien entsprechen. Die Filteränderungen sollen die Daten dynamisch neu laden.