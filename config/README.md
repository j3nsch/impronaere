Die Termine können folgende Angaben enthalten.

* Datum im Format YYYY-MM-DD
* Zeit im Format HH:MM
* Titel
* URL für Titel (optional)
* Ort
* URL für Ort (optional)
* Beschreibung (optional)

Die Informationen müssen im JSON Format eingegeben werden. Dabei muss insbesondere auf die Kommas geachtet werden.

Beispiel:

```
[
  {
    "date": "2015-09-19",
    "time": "20:00",
    "title": {
      "text": "Was Ihr Wollt!",
      "url": ""
    },
    "location": {
      "text": "Varia Vineta",
      "url": ""
    },
    description: ""
  }
]
```

Für eine neue "Was Ihr Wollt!" Show kann einfach folgendes hinzugefügt werden:

```
  {
    "date": "2015-09-18",
    "show": "WasIhrWollt"
  }
```

Die restlichen Informationen sind in einer anderen Datei definiert. Der String "WasIhrWollt" dient dazu, die Show zu
identifizieren.
