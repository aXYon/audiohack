# audiohack
Ein kollaboratives Projekt als Übung für das 5. Semester.

### mögliche Funktionen:
* Effekte
  * Delay
  * Reverb
  * Pitchshift
  * ...
* FadeIn, FadeOut
* Volume change, Normalize
* Cut
* Reverse
* Bitcrusher
* Gate
* ...

### Programmaufruf:
```
$ audiohack --input inputFile.wav --output outputfile.wav --action cut
$ audiohack -i inputFile.wav -o outputFile.wav -a cut
$ audiohack if.wav of.wav cut
```

### Funktionen
#### Gate
##### Aufruf:
```
$ audiohack if.wav of.wav -g <threshold> [<attack> <release>]
```

##### Parameter:
* threshold: Wert, ab dem das Gate greift. [0.0-1.0]
* [attack]: Anstiegszeit
* [release]: Abklingzeit

