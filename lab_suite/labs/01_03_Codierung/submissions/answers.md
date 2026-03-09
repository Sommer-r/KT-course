# Fragebogen: Huffman-Codierung (huffman.py)

Nach dem Ausführen des Skripts und **Einfügen der Konsolenausgabe** (Merge-Symbol in der Task-Card):

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

```
Enter the string to compute Huffman Code Tree: sadffaeggdfgaeag
---------------------------------------------------------
Dictionary of Characters with char frequency:       {'s': 1, 'a': 4, 'd': 2, 'f': 3, 'e': 2, 'g': 4}
Dictionary converted into a list:                   dict_items([('s', 1), ('a', 4), ('d', 2), ('f', 3), ('e', 2), ('g', 4)])
List of characters sorted to descending frequency:  [('a', 4), ('g', 4), ('f', 3), ('d', 2), ('e', 2), ('s', 1)]
Huffman Code Dictionary:                            {'f': '00', 'g': '01', 'a': '10', 'd': '110', 's': '1110', 'e': '1111'}

 Char | Huffman code
----------------------
 'a'  |          10
 'g'  |          01
 'f'  |          00
 'd'  |         110
 'e'  |        1111
 's'  |        1110
```


---

**2. Deine Kommentierung**

- Was zeigen die ausgegebenen Huffman-Codes?

Die Tabelle zeigt, welches Binärcodewort jedem Zeichen zugeordnet wurde. Häufig vorkommende Zeichen wie "a", "g" haben kurze Codes, während seltene Zeichen wie "s" längere Codes haben.

- Warum haben häufigere Zeichen kürzere Codewörter?  

Es werden häufige Zeichen mit kürzeren Codes codiert, damit die durchschnittliche Länge der gesamten Nachricht möglichst klein wird. Dadurch kann der Text effizienter komprimiert werden.
