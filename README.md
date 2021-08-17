# porta_ingresso
Gestione porta ingresso con avvisi su dot, accensione luci al rientro, e gestione antifurto

Occorrete:
Sensore porta/finestre
Tasto smart

Logica di funzionamento.

Ogni volta che la porta viene aperta, viene emesso un annuncio "porta ingresso aperta" su gruppo "in casa" dei dot.
Se la porta non viene chiusa, ogni tot secondi viene dato l'annuncio "attenzione, la porta ingresso è rimasta aperta".
Viene gestito l'apertura "incerta" della porta, che potrebbe causare un ripetersi accidentale dei messaggi.
L'annuncio di porta ingresso aperta viene inibito se ad entrare in casa è il proprietario che torna da fuori.
Viene associato uno un tasto smart che alla sua pressione, inibisce l'annuncio di porta aperta.
Il tasto smart si preccupa anche di disinserire temporaneamente l'allarme di casa (nel caso fosse inserito) per permettere l'apertura della porta senza annuncio e senza far scattare l'allarme, per poi dopo un tot ripristinare tutto.
Rincasando dopo il tramonto, all'apertura della porta, se nessuno è in casa viene accesa una luce.
