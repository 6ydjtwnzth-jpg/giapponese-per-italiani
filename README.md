# Giapponese per italiani · イタリア人のための日本語

Corso di giapponese per italiani, dai kana al livello A2 (circa JLPT N5–N4): 23 lezioni, 3 ripassi, dialoghi da ascoltare e recitare, furigana sopra i kanji, rōmaji solo nelle prime lezioni, esercizi corretti in automatico (risposte in kana o in rōmaji), flashcard, coniugatore dei verbi, tabelle dei kana e schede di cultura giapponese a confronto con l'Italia.

Il sito è un unico file statico, `index.html`, generato da `build.py` a partire da `src/`. Per modificare il corso: cambiare i file in `src/`, eseguire `python3 build.py` e pubblicare.

## Formato del testo giapponese

Nei dati il giapponese si scrive con le parole separate da spazi e la lettura dei kanji tra parentesi quadre:

```
わたし は 日本[にほん] に 行[い]きます 。
```

Da questa forma il sito ricava la scrittura normale (わたしは日本に行きます。), i furigana, il rōmaji (watashi wa nihon ni ikimasu.) e il controllo delle risposte.
