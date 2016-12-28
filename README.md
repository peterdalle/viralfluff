# viralfluff

Lista i CSV-format över nyhetssajter, bloggar och andra hemsidor med clickbait-artiklar.


## Ladda datan via R

Läs in datan från GitHub via R:

```r
url <- "https://raw.githubusercontent.com/peterdalle/viralfluff/master/svenska-virala-hemsidor.csv"
viralahemsidor <- read.csv(url, header=TRUE)
```

Och skapa en lokal kopia av filen:

```r
download.file(url, destfile="svenska-virala-hemsidor.csv")
```
