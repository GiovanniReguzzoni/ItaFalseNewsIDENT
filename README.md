# ItaFalseNewsIDENT
Italian False News Identification Classification Dataset


# Motivation
La motivazione che ha portato alla creazione del dataset e data dalla crescente popolarità nell’uso dei social network per condividere notizie e le conseguenze che questo puo portare. Un fenomeno interessante da analizzare e quello per cui gli utenti sempre di piu` commentano e condividono una notizia leggendo solo il titolo. 
Questo puo portare ad una conoscenza solo parziale o errata non approfondendo e quindi non verificando la notizia. In effetti, circa il 59% dei link
condivisi sui social media di notizia non viene mai aperto, le persone quindi condividono notizie senza neanche leggerle.
Alcune possibili soluzioni per contrastare la continua diffusione virale di fake news e quella 
di effettuare analisi di fact checking sui contenuti specifici delle notizie: effettuare una verifica
delle fonti e, in generale, una presa di coscienza e aumento delle competenze da parte dei lettori,
unita a un lavoro di verifica e segnalazioni da parte di fornitori internet e governi.
Uno studio lessicale, del vocabolario utilizzato, e morfologico, della struttura della frase,
puo essere un punto di partenza e di supporto nell’aiutare l’identificazione di una fakenews,
senza prescindere da uno studio di verifica di fatti e fonti. Questa analisi lessicale e morfolo gica potrebbe essere effettuata attraverso modelli automatizzati di elaborazione del linguaggio
naturale NLP. In particolare il dataset creato contiene esclusivamente titoli di articoli di testate
giornalistiche e blog online. Per i titoli collegati a fakenews si e scelto fonti che fossero chiaramente ed apertamente informazioni inventate e distorte. Alcuni dei siti selezionati ricadono
nella categoria di notizie burla, create per fini satirici; questo per semplificare il processo di
raccolta e catalogazione delle notizie. Rimane interessante comprendere quanto i sistemi NLP
siano in grado di distinguere una notizia vera da una falsa a prescindere dal fine per cui la notizie falsa sia stata creata, e tenendo in considerazione che in ogni caso una notizia falsa puo`
essere scritta, utilizzando un linguaggio e una struttura ingannevole, e di come un modello di
classificazione automatica sia da considerare di supporto.

# Dataset and data
Il dataset e composto di 13599 titoli di articoli di giornale raccolti da database o ricavati attraverso tecniche di data scraping, di estrazione direttamente dai siti web. Per evitare un processo
manuale lungo di catalogazione e classificazione labelling degli articoli, si e scelto di procedere attraverso un approccio ibrido, dove vi e stata una selezione iniziale attiva dei siti dai quali reperire le notizie false. Questa catalogazione e avvenuta anche tramite la consultazione di 
cataloghi online di fact checking che offrono “black list” di siti di disinformazione, di bufale,
false testate giornalistiche satiriche e siti clickbait. Durante il processo di data scraping vi è
stato un ulteriore controllo attivo sulle notizie e veridicita. Per quanto riguarda le notizie vere,
esse sono state prese dal database “Leipzig Corpora Collection”, un progetto dell’Universita di 
Lipsia che offre svariati corpus in diverse lingue, suddivisi per fonti e contenuti. In questo caso
e stato usato una parte di corpus ricavato attraverso la raccolta di ` feed RSS e titoli dei principali
giornali italiani.

# Task
Il task prevede, al momento, un singolo compito , ovvero quello, partendo dal dataset di train,
di offrire un modello di classificazione delle notizie vere e false del dataset di test, un problema
che si puo ricondurre a una ` sentiment analysis con classificazione binaria 1, 0. (0 per le notizie
vere, 1 per quelle false).


