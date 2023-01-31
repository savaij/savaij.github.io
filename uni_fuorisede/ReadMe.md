<b>Ciao!</b> Allooora spieghiamo un po' cosa sono questi file. <br>

fuorisede_per_uni.csv --> per ogni università presente nel database, vediamo quanti sono gli studenti che hanno la residenza in una provincia
diversa rispetto alla sede del proprio corso di studi. Questi sono i fuorisede (ovviamente quelli che vengono da province molto vicine sono pendolari
più che fuorisede, però vabbè per ora ignoriamo il problema). Visto che non ci interessano i numeri assoluti ma le proporzioni, poi il numero di fuorisede
in ogni università l'abbiamo diviso per il totale degli studenti di quella università ---> INOLTRE, ho inserito solo le uni più grandi, con più di 
20mila studenti.
<br><br>
province_accolgono_più_fuorisede.csv ----> qui non ragioniamo più per Uni ma per province. Per ogni provincia vediamo quanti sono gli studenti
che studiano in un ateneo con sede lì e allo stesso tempo hanno la residenza in un'altra. Questi sono i fuorisede che ARRIVANO nella provincia 
(vale lo stesso piccolo problema
di prima). Visto che non ci interessano i numeri assoluti ma le proporzioni, poi il numero di fuorisede in ogni provincia 
l'abbiamo diviso per il totale degli studenti che studiano in quella provincia. Una provincia con un rapporto molto alto, vuol dire che attira tanta gente
da altre province. Non sono disponibili dati per tutte le province.
<br><br>
province_accolgono_più_fuorisede.csv ----> qui non ragioniamo più per Uni ma per province. Per ogni provincia vediamo quanti sono gli studenti
che hanno la residenza in quella provincia e frequentano un ateneo in un'altra provincia. Questi sono i fuorisede che PARTONO dalla provincia
(vale lo stesso piccolo problema di prima). Visto che non ci interessano i numeri assoluti ma le proporzioni, poi il numero di fuorisede 
partiti da ogni provincia l'abbiamo diviso per il totale degli studenti che sono originari di quella provincia. 
Una provincia con un rapporto molto alto, vuol dire che lascia partire tanta gente verso altre province. Non sono disponibili dati per tutte le province.
