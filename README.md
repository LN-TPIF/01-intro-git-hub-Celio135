# :wave: Die Grundlagen von GitHub

## 🤓 Kursüberblick und Lernziele

Ziel dieses Kurses ist es, dir eine kurze Einführung in GitHub zu geben. Wir stellen dir auch Materialien für weiteres Lernen und ein paar Ideen für den Einstieg auf unserer Plattform zur Verfügung. 🚀

## :octocat: Git und GitHub

Git ist ein **verteiltes Versionskontrollsystem (VCS)**, was bedeutet, dass es ein nützliches Werkzeug ist, um Änderungen an deinem Code einfach zu verfolgen, zusammenzuarbeiten und zu teilen. Mit Git kannst du die Änderungen verfolgen, die du an deinem Projekt vornimmst, sodass du immer eine Aufzeichnung deiner Arbeit hast und bei Bedarf problemlos zu einer älteren Version zurückkehren kannst. Es erleichtert auch die Zusammenarbeit mit anderen – Gruppen von Personen können gemeinsam am selben Projekt arbeiten und ihre Änderungen in eine endgültige Quelle zusammenführen!

GitHub ist eine Möglichkeit, die gleiche Leistungsfähigkeit von Git online mit einer einfach zu bedienenden Oberfläche zu nutzen. Es wird in der gesamten Softwarewelt und darüber hinaus verwendet, um zusammenzuarbeiten und die Historie von Projekten zu pflegen.

GitHub beherbergt einige der fortschrittlichsten Technologien der Welt. Egal, ob du Daten visualisierst oder ein neues Spiel entwickelst, auf GitHub gibt es eine ganze Community und eine Reihe von Tools, die dich zum nächsten Schritt bringen können. Dieser Kurs beginnt mit den Grundlagen von GitHub, aber wir werden uns später mit dem Rest befassen.

## :octocat: Das GitHub-Flow verstehen

Der GitHub-Flow ist ein leichtgewichtiger Workflow, der es dir ermöglicht, einfach an deinen Projekten zu experimentieren und zusammenzuarbeiten, ohne das Risiko, deine bisherige Arbeit zu verlieren.

### Repositories (Projekte)

Ein Repository ist der Ort, an dem deine Projektarbeit stattfindet – betrachte es als deinen Projektordner. Es enthält alle Dateien deines Projekts und die Revisionshistorie. Du kannst innerhalb eines Repositories alleine arbeiten oder andere einladen, mit dir an diesen Dateien zusammenzuarbeiten.

### Klonen

Wenn ein Repository mit GitHub erstellt wird, wird es remote in der ☁️ gespeichert. Du kannst ein Repository klonen, um eine lokale Kopie auf deinem Computer zu erstellen und dann Git zu verwenden, um die beiden zu synchronisieren. Dies erleichtert das Beheben von Problemen, das Hinzufügen oder Entfernen von Dateien und das Pushen größerer Commits. Du kannst auch das Bearbeitungswerkzeug deiner Wahl anstelle der GitHub-Benutzeroberfläche verwenden. Das Klonen eines Repositories lädt auch alle Repository-Daten herunter, die GitHub zu diesem Zeitpunkt hat, einschließlich aller Versionen jeder Datei und jedes Ordners für das Projekt! Dies kann hilfreich sein, wenn du mit deinem Projekt experimentierst und dann feststellst, dass dir eine frühere Version besser gefallen hat.
Um mehr über das Klonen zu erfahren, lies ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Committing und Pushing

**Committing** (Festschreiben) und **Pushing** (Hochladen) sind die Methoden, mit denen du die Änderungen, die du auf deinem lokalen Rechner vorgenommen hast, zum Remote-Repository in GitHub hinzufügen kannst. Auf diese Weise können dein Lehrer und/oder deine Teamkollegen deine neueste Arbeit sehen, wenn du bereit bist, sie zu teilen. Du kannst einen Commit erstellen, wenn du Änderungen an deinem Projekt vorgenommen hast, die du "prüfen" möchtest. Du kannst auch eine hilfreiche **Commit-Nachricht** hinzufügen, um dich selbst oder deine Teamkollegen daran zu erinnern, welche Arbeit du erledigt hast (z. B. "README mit Informationen über unser Projekt hinzugefügt").

Sobald du einen oder mehrere Commits hast, die du deinem Repository hinzufügen möchtest, kannst du den Befehl `push` verwenden, um diese Änderungen zu deinem Remote-Repository hinzuzufügen. Das Committing und Pushing mag sich anfangs neu anfühlen, aber wir versprechen dir, dass du dich daran gewöhnen wirst 🙂.

## 💻 Wichtige GitHub-Begriffe

### Repositories

Wir haben Repositories bereits erwähnt, sie sind der Ort, an dem deine Projektarbeit stattfindet, aber lass uns ein wenig mehr über die Details sprechen! Wenn du mehr auf GitHub arbeitest, wirst du viele Repositories haben, was sich anfangs verwirrend anfühlen kann. Glücklicherweise hilft dir dein ["GitHub-Dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard), einfach zu deinen Repositories zu navigieren und nützliche Informationen über sie zu sehen. Stelle sicher, dass du angemeldet bist, um es zu sehen!

Repositories enthalten auch **README**-Dateien. Du kannst eine README-Datei zu deinem Repository hinzufügen, um anderen Leuten mitzuteilen, warum dein Projekt nützlich ist, was sie damit machen können und wie sie es verwenden können. Wir verwenden diese README, um dir die Grundlagen von Git und GitHub zu vermitteln. 😄
Um mehr über Repositories zu erfahren, lies ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) und ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes).

### Branches (Zweige)

Du kannst Branches auf GitHub verwenden, um Arbeiten zu isolieren, die du noch nicht in dein endgültiges Projekt zusammenführen möchtest. Branches ermöglichen es dir, Funktionen zu entwickeln, Fehler zu beheben oder sicher mit neuen Ideen in einem abgegrenzten Bereich deines Repositories zu experimentieren. In der Regel erstellst du einen neuen Branch aus dem Standard-Branch deines Repositories – `main`. Dadurch wird eine neue Arbeitskopie deines Repositories erstellt, mit der du experimentieren kannst. Sobald deine neuen Änderungen von einem Teamkollegen überprüft wurden oder du zufrieden damit bist, kannst du deine Änderungen in den Standard-Branch deines Repositories mergen.
Um mehr über Branching zu erfahren, lies ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks (Abzweigungen)

Ein Fork ist eine andere Möglichkeit, ein Repository zu kopieren, wird aber normalerweise verwendet, wenn du zu einem Projekt einer anderen Person beitragen möchtest. Das Forken eines Repositories ermöglicht es dir, frei mit Änderungen zu experimentieren, ohne das Originalprojekt zu beeinflussen, und ist sehr beliebt, wenn du zu Open-Source-Softwareprojekten beiträgst!
Um mehr über das Forken zu erfahren, lies ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo).

### Pull Requests (Pull-Anfragen)

Bei der Arbeit mit Branches kannst du eine Pull-Anfrage verwenden, um anderen über die Änderungen zu informieren, die du vornehmen möchtest, und um Feedback zu bitten. Sobald eine Pull-Anfrage geöffnet ist, kannst du die potenziellen Änderungen mit deinen Mitarbeitern besprechen und überprüfen und bei Bedarf weitere Änderungen hinzufügen. Du kannst bestimmten Personen als Reviewer deiner Pull-Anfrage hinzufügen, um zu zeigen, dass du ihr Feedback zu deinen Änderungen wünschst! Sobald eine Pull-Anfrage fertig ist, kann sie in deinen Haupt-Branch gemergt werden.
Um mehr über Pull-Anfragen zu erfahren, lies ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Issues (Probleme)

Issues sind eine Möglichkeit, Verbesserungen, Aufgaben oder Fehler für deine Arbeit auf GitHub zu verfolgen. Issues sind eine großartige Möglichkeit, alle Aufgaben zu verfolgen, an denen du für dein Projekt arbeiten möchtest, und andere wissen zu lassen, woran du zu arbeiten planst. Du kannst Issues auch verwenden, um ein Open-Source-Projekt über einen Fehler zu informieren, den du gefunden hast, oder über eine Funktion, die deiner Meinung nach eine großartige Ergänzung wäre!

Bei größeren Projekten kannst du viele Issues auf einem Projektboard verfolgen. GitHub Projects hilft dir, deine Arbeit zu organisieren und zu priorisieren, und du kannst mehr darüber im Dokument "About Project boards" lesen. Du wirst wahrscheinlich kein Projektboard für deine Aufgaben benötigen, aber sobald du zu noch größeren Projekten übergehst, sind sie eine großartige Möglichkeit, die Arbeit deines Teams zu organisieren!
Du kannst auch Pull-Anfragen und Issues miteinander verknüpfen, um zu zeigen, dass eine Korrektur in Arbeit ist, und das Issue automatisch zu schließen, wenn jemand die Pull-Anfrage mergt.
Um mehr über Issues und deren Verknüpfung mit deinen Pull-Anfragen zu erfahren, lies ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues).

### Dein Benutzerprofil

Deine Profilseite erzählt die Geschichte deiner Arbeit anhand der Repositories, an denen du interessiert bist, der Beiträge, die du geleistet hast, und der Gespräche
