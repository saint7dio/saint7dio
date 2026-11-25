# Coding-Workflow mit Codex

1. Im passenden Git-Repository arbeiten. Zu Beginn `git status --short --branch` und das GitHub-Ziel prüfen. Für eine größere Änderung einen eigenen Branch verwenden.
2. Nur die zur Aufgabe gehörenden Dateien ändern und den Diff prüfen. Bei geänderter Einrichtung, Bedienung oder Architektur das README oder die Projektdokumentation im selben Schritt pflegen.
3. Relevante Tests ausführen. Befehle, Ergebnisse und ausstehende Prüfungen festhalten. Vor dem Commit und Push das Diff auf Secrets, Kundendaten und lokale Konfiguration prüfen.
4. Einen inhaltlich zusammenhängenden Commit mit erklärendem Titel erstellen. Für größere Änderungen einen Pull Request mit **Warum**, **Was geändert wurde** und **Wie geprüft** verwenden.
5. Den Branch zum vorgesehenen GitHub-Repository pushen, wenn der Auftrag das vorsieht. Nach dem Review gehört die Änderung per Merge in den Standardbranch.

## Damit GitHub Beiträge zuordnet

Die Git-Autoradresse muss in GitHub unter **Settings → Emails** hinterlegt sein. Alternativ die dort angezeigte GitHub-`noreply`-Adresse als `user.email` verwenden. Vor der ersten Arbeit an einem Repository `git config --get user.email` prüfen.

## Vorlage für einen Coding-Auftrag

> Arbeite im passenden Git-Repository. Prüfe und teste den Diff, aktualisiere bei Bedarf die Projektdokumentation und erstelle einen erklärenden Commit. Halte durchgeführte und ausstehende Tests fest. Nutze für größere Änderungen einen Branch und Pull Request. Prüfe vor dem Push die Zieladresse und den Diff auf sensible Inhalte.
