- Ti ho caricato un collegamento a onedrive con un insieme di pubblicazionidi un set di ricercatori di mio interesse.
- Il dataset include anche delle variabili dummy per i field in cui i ricercatori pubblicanoi loro paper (per esempio, labor, econometrics, public economics, economic history,etc..). 
    -  Il valore della dummy  stato assegnato usando il valore della variabile JEL,ossia del JEL code che i ricercatori indicano nelle loro pubblicazioni. Possono esserci piu field, perchi field non sono mutualmente esclusivi.


PROBLEMA: 
La variabile JEL code  missing per piu o meno meta dataset. Per le pubblicazioni per le quali non c'è direttamente nella pubblicazione l'indicazione del JEL code, ossia per le pubblicazioni per cui il JEL code  missing, bisogna predire il valore di ogni dummy usando topic modelling. Ti allego il codice di Python che abbiamo preparato in passato con questo obiettivo.
Il tuo task è quello di assegnare usando questo codice il field alle diverse pubblicazioni per le quali il field non c'è di già.