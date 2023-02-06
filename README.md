# Crypto-Daily-Report

### Questo programma è il progetto pratico del capitolo relativo a Python del corso Blockchain di [Start2Impact University](https://www.start2impact.it/master/blockchain-development/). ###

#### :hash: Si tratta di un sistema di reportistica sul mercato delle criptovalute che richiede un report di mercato a [CoinMarketCap](https://coinmarketcap.com/) (Il più importante sito di analisi sui prezzi delle criptovalute) tramite il suo servizio di API, ne elabora i dati e li conserva all'interno di un file json. Il programma inoltre è impostato per eseguire il report in automatico ogni giorno a una specifica ora, nel mio caso le 9:30.
Le richieste elaborate dal programma sono:

1. La criptovaluta con il volume maggiore in $ delle ultime 24 ore
2. Le migliori e peggiori 10 criptovalute per incremento % nelle ultime 24 ore
3. La quantità di denaro necessaria per acquistare un'unità di ciascuna delle prime 20 criptovalute in ordine per capitalizzazione di mercato
4. La quantità di denaro necessaria per acquistare un'unità di tutte le criptovalute il cui volume delle ultime 24 ore sia superiore a 76'000'000$
5. La percentuale di guadagno o perdita che avreste realizzato se aveste comprato un'unità di ciascuna delle prime 20 criptovalute il giorno prima (ipotizzando che la classifca non sia cambiata)


#### :hash: Ecco un'anteprima del programma in esecuzione e del file json generato:

![1](https://user-images.githubusercontent.com/122997887/215443693-ea6ad73d-5916-41ad-bb89-c90af43d8c2f.png)
![2](https://user-images.githubusercontent.com/122997887/215443711-5f9c4105-daee-487c-afb5-5d410105e822.png)
![3](https://user-images.githubusercontent.com/122997887/215443727-c846355e-5111-4cab-83dc-f262318654a8.png)



#### :hash: Cosa ti serve per provare il programma:

1. Creare un ambiente virtuale in python, trovi una guida a questo [link](https://youtu.be/S6LMNLKhaEM)
2. Installare al suo interno le librerie "requests" e "schedule", eseguendo "pip install schedule" e "pip install requests" nel terminale
3. Richiedere una chiave per il servizio API di coinmarketcap a questo [link](https://pro.coinmarketcap.com/)
4. Inserire la tua nuova chiave API nel file "main.py" alla riga 20 al posto di '---la tua chiave API---'

:arrow_right: Ora sei pronto per avviare il programma!
