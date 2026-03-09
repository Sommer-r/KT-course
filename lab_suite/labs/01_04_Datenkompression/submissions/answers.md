# Fragebogen: Wort-Entropie (word_dictionary.py)

Nach dem Ausführen von `word_dictionary.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

```
Analyze the file:  C:\_git\KT_course\lab_suite\labs\01_04_Datenkompression\submissions\sidedata/sampletext.txt
Total number of words:     245
Number of different words: 179

-------Table of words:-----------------------------------------
                            die | cnt= 16    p=0.065   H=3.937 bit/word   H_av=0.257 bit/word
                             es | cnt=  4    p=0.016   H=5.937 bit/word   H_av=0.097 bit/word
                            und | cnt=  4    p=0.016   H=5.937 bit/word   H_av=0.097 bit/word
                            wir | cnt=  4    p=0.016   H=5.937 bit/word   H_av=0.097 bit/word
                            der | cnt=  4    p=0.016   H=5.937 bit/word   H_av=0.097 bit/word
                            wie | cnt=  3    p=0.012   H=6.352 bit/word   H_av=0.078 bit/word
                             um | cnt=  3    p=0.012   H=6.352 bit/word   H_av=0.078 bit/word
                          Sonne | cnt=  3    p=0.012   H=6.352 bit/word   H_av=0.078 bit/word
                           eine | cnt=  3    p=0.012   H=6.352 bit/word   H_av=0.078 bit/word
                            auf | cnt=  3    p=0.012   H=6.352 bit/word   H_av=0.078 bit/word
                            Was | cnt=  3    p=0.012   H=6.352 bit/word   H_av=0.078 bit/word
                            uns | cnt=  3    p=0.012   H=6.352 bit/word   H_av=0.078 bit/word
                      Universum | cnt=  3    p=0.012   H=6.352 bit/word   H_av=0.078 bit/word
                            sei | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                          hielt | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                          einen | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                        Vortrag | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                          Ã¼ber | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                           Erde | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                            den | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                          einer | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                            von | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                         kreist | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                           alte | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                           Dame | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                            ist | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                            Und | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                         werden | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                            ein | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
              SchildkrÃ¶tenturm | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                             zu | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                         wissen | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                            das | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                      Antworten | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                          diese | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                             so | cnt=  2    p=0.008   H=6.937 bit/word   H_av=0.057 bit/word
                            Ein | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                      namhafter | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                wissenschaftler | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           (man | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           sagt | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                       Bertrand | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        Russell | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                       gewesen) | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         einmal | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                  Ã¶ffentlichen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                     Astronomie | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                             Er | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                     schilderte | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                     ihrerseits | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                    Mittelpunkt | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                       riesigen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                     Ansammlung | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        Sternen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         unsere | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        Galaxis | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         nennen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            Als | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        beendet | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            war | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          stand | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         hinten | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                             im | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           Saal | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         kleine | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                     erklÃ¤rte: | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            Sie | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                             da | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                       erzÃ¤hlt | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          haben | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         stimmt | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          alles | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          nicht | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                             In | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                   Wirklichkeit | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           Welt | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         flache | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        Scheibe | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
             RiesenschildkrÃ¶te | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            dem | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        RÃ¼cken | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                       getragen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           wird | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            Mit | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          einem | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                   Ã¼berlegenen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                       LÃ¤cheln | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                Wissenschaftler | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            ihr | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                      entgegen: | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         worauf | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          steht | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                  SchildkrÃ¶te? | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          -Sehr | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         schlau | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         junger | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           Mann | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                       parierte | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            Ich | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          werds | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          Ihnen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         sagen: | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                             Da | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         stehen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         lauter | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                  SchildkrÃ¶ten | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                    aufeinander | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            Die | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        meisten | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                       Menschen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                    Vorstellung | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          unser | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                    unendlicher | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           Kopf | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                     schÃ¼tteln | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           Doch | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          woher | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         nehmen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                   Ãœberzeugung | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         besser | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        wissen? | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            vom | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          wieso | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            es? | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          Woher | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          kommt | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          wohin | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                     entwickelt | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          sich? | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          Hatte | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                       wirklich | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        Anfang? | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           wenn | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            was | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        geschah | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         davor? | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          Zeit? | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           Wird | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            sie | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                             je | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           Ende | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        finden? | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         Neuere | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                   Erkenntnisse | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                             in | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         Physik | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                      teilweise | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                 phantastischen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          neuen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                   Technologien | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                      verdanken | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           sind | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          legen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         einige | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          alten | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         Fragen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           nahe | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          Eines | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          Tages | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                     vielleicht | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
            selbstverstÃ¤ndlich | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                     erscheinen | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                       Tatsache | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                             12 | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           daÃŸ | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            â€“ | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           oder | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                    lÃ¤cherlich | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                            Nur | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        Zukunft | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           (was | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           auch | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          immer | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           sein | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           mag) | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                           kann | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                        Antwort | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                         darauf | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
                          geben | cnt=  1    p=0.004   H=7.937 bit/word   H_av=0.032 bit/word
-----------------------------------------------------------------

Average Entropy H = 7.202 bit/word
Total Entropy of 245 words H=1764.437 bit (221 bytes)
Size of text file: 1642 bytes
```


---

**2. Deine Kommentierung**

- Wie unterscheidet sich die Wort-Entropie von der Zeichen-Entropie (entropy1.py)?  
  
Die Wort-Entropie ist höher, weil es viel mehr verschiedene Wörter als Zeichen gibt.

- Was sagt die Entropie in Byte im Vergleich zur tatsächlichen Dateigröße aus?  

Die berechnete Entropie (≈221 Byte) ist das Minimum, auf das man den Text komprimieren könnte. Die tatsächliche Dateigröße ist deutlich größer mit 1642 Byte. Das zeigt, dass der Text viel Redundanz enthält und theoretisch stark komprimiert werden könnte.
