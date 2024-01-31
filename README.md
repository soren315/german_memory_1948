# "Wie erinnert Deutschland? Eine computergestützte Analyse der Erinnerung an die Nakba/die Staatsg﻿ründung Israels 1948 in deutschen Zeitungen“
Dieses Github Repository betrifft meine Forschung zur deutschen Erinnerung an die Ereignisse von 1948 im historischen Palästina.
Um diese Erinnerung zu untersuchen, wurde ein Korpus des IDS

1948 war ein historisch bedeutsames Jahr für die Region zwischen dem Jordanfluss und dem Mittelmeer und darüber hinaus: Unter anderem wurde der Staat Israel gegründet und ein großer Teil der indigenen palästinensischen Bevölkerung wurde vertrieben. Es scheint, als gebe es eine Erinnerungskonkurrenz zwischen diesen beiden Erinnerungen. Es ist bisher nicht analytisch erforscht worden, mit welcher Form des Erinnerns Deutschland dieser Ereignisse gedenkt. Auf diese Frage soll diese Arbeit eine mögliche Antwort geben, indem ein Seeded Topic Model auf einen vorselektierten Korpus an Zeitungsartikeln, die sich mit den Ereignissen von 1948 im historischen Palästina zwischen 1998-2022 in deutschen Zeitungen befassen, angewendet wurde. Dabei wurde herausgefunden, dass in Deutschland kein Dialogisches Erinnern stattfindet. Die Form des Erinnerns unterscheidet sich aber je nach Zeitung. 

Hier sind alle R-Skripte zu finden, die ich genutzt habe.

Daten:
Die Daten für diese Forschung sind unter data_w_font1, ..., data_w_font_4 hinterlegt. Sie wurden mit "dereko_cleaning.Rmd" bereinigt und für die Analyse vorbereitet.


Analyse:
Das Topic Model wurde mit dem Code in "topicmodelling.Rmd" durchgeführt.
Das Seeded Topic Model wurde mit dem Code in "seeded_topicmodel.Rmd" durchgeführt.
Das Seeded Topic Model für die einzelnen Zeitungen wurde mit dem Code in "seeded_tm_all_newspaper.Rmd" durchgeführt.

Visualisierung:
Die Visualisierung deskriptiver Daten wurde mit dem Code in "frequencies.Rmd" durchgeführt.
