# carbi-trivia

This repo feeds [Carbi's Trivia](https://github.com/natejnixon/carbi-trivia) widget. StreamElements downloads the live list from:

https://raw.githubusercontent.com/natejnixon/carbi-trivia/main/questions-current.txt

`questions-current.txt` is one question per line:

```
Question | Correct | Wrong 1 | Wrong 2 | Wrong 3
```

Lines starting with `#` are comments and are ignored. The file is refreshed weekly. Do not edit it by hand during a stream.
