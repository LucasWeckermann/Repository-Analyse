# Repository-Analyse
Dieses Repository ist ein Beispiel-Repository und dient lediglich dazu, dass sich Studierende mit Basisfunktionalitäten des Versionsverwaltungssystems `git` vertraut machen.

## Diff
Mit dem `diff`-Werkzeug können Sie Unterschiede zwischen Unterschiedlichen Revisionen und Dateien angezeigt werden. Das ist sehr nützlich, insbesondere wenn man die Nadel im Heuhaufen sucht...

## Codewort
An dieser Stelle wird ein Codewort aufgeführt, welches keine weitere Relevanz oder Bezug zu etwas hat. Das Codewort lautet `Hannover`.

## Tipps und Tricks
Oftmals finden sich nützliche Hinweise und Shortcuts in der git-Dokumentation, der manuel page.
Überfliegen Sie doch mal die Hilfe-Seite des ein oder anderen Befehls. Sie können sich die Arbeit ggf. erleichtern, wenn Sie einen passenden Befehl und/oder Parameter kennen. Manche Tipps finden Sie auch im Tipp des Commits.

### Tipp des Commits
Gelegentlich möchte man nicht nur eine Datei mit sich selbst in einer anderen Revision vergleichen, sondern einfach zwei unterschiedliche Dateien (in der selben Revision). In diesem Fall kann der Parameter `--no-index` verwendet werden. So zeigt `git diff --no-index ./path/to/fileA ./path/to/fileB` die Unterschiede zwischen `./path/to/fileA` und `./path/to/fileB` an.