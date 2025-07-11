Sfrutta una vulnerabilità nel servizio PostgreSQL di Metasploitable 2. Esegui l'exploit per ottenere una sessione Meterpreter sul sistema target. 
1) Una volta ottenuta la sessione Meterpreter, il tuo compito è eseguire un'escalation di privilegi per passare da un utente limitato a root utilizzando solo i mezzi forniti da msfconsole.
2) Esegui il comando getuid per verificare l'identità dell'utente corrente.

Bonus:
1) Usa il modulo post di msfconsole per identificare potenziali vulnerabilità locali che possono essere sfruttate per l'escalation di privilegi.
2) Esegui lʼexploit proposti e verifica ogni vulnerabilità trovata dal modulo sopracitato.
3) Per ogni vulnerabilità test l'escalation di privilegi eseguendo nuovamente getuid o tentando di eseguire un comando che richiede privilegi di root.
4) sempre usando msfconsole installa una backdoor e dimostra che puoi accedere ad essa in un momento successivo.
