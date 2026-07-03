# Richieste

PERCHè CHIAMARE IL FILE INDEX.HTML ???

Quando apri un sito tipo https://eliaventurini.github.io/Richieste/, stai chiedendo al server "dammi la pagina principale di questa cartella". Ma tu non hai specificato quale file aprire — hai solo indicato la cartella. Il server deve quindi sapere quale file servire di default.

La regola, vecchia di decenni e usata da praticamente tutti i web server del mondo, è: "se non ti dicono quale file aprire, cerca un file chiamato index.html e servi quello". È il file "indice", il punto d'ingresso predefinito.

È nato negli anni '90: index perché storicamente era la pagina che faceva da "indice" dei contenuti del sito, un po' come l'indice di un libro che ti dice da dove cominciare. Il nome è rimasto come standard anche se oggi le homepage non sono più letteralmente degli indici.

Quindi quando il tuo file si chiamava richiesta_jonny_invaders.html, il server non lo trovava cercando index.html, e ripiegava sul README mostrando quella pagina bianca. Rinominandolo index.html gli hai detto "ecco, questa è la porta d'ingresso", e ha funzionato.

Piccola curiosità: se avessi voluto tenere il nome originale, avrei potuto comunque aprirlo scrivendo l'URL completo https://eliaventurini.github.io/Richieste/richiesta_jonny_invaders.html — funziona, ma è scomodo da condividere. index.html mi permette di avere l'URL pulito senza nome file in fondo.
