# ffhs-gti-vigenere-johnny
Semesterarbeit (2017) in GTI: Vigenère-Chiffre mit Johnny (Simulator für Rechner mit Von-Neumann-Architektur)

## Ausgangslage
Bei der Vigenère-Chiffre handelt es sich um eine Verschiebechiffre bei der jeder Buchstabe eines Textes im Alphabet verschoben wird. Im Gegensatz zur Caesar-Verschlüsselung wird hierbei aber jeder Buchstabe aufgrund eines Schlüsselwortes und der Textposition verschoben. 

##	Schwierigkeiten
Der Johnny-Simulator erlaubt nur Mathematische Operatoren wie Addition, Subtraktion, Erhöhen einer Zahl um 1 sowie Verminderung um 1. Weiter können in den Speicheradressen nur Zahlen festgehalten werden. Es ist somit nötig, den zu ver-schlüsselnden Text, die Passphrase sowie das Ergebnis in Zahlenform abzuspei-chern und nicht, wie man es normalerweise erwarten würde, in Textform. Anstelle der Buchstaben wird daher der entsprechende ASCII-Wert herhalten müssen. 
