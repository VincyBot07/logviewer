<div align="left">
    <h1>Visualizzatore log per VincyBot07</h1>
    <strong><i>Un web server semplice per vedere i log del VincyBot07 self-hostato.</i></strong>
    <br>
    <br>


<a href="https://heroku.com/deploy?template=https://github.com/VincyBot07/logviewer">
    <img src="https://img.shields.io/badge/deploy_to-heroku-997FBC.svg?style=for-the-badge" />
</a>

</div>
DEPRECATO! Usa [StrapBot](https://github.com/Ergastolator1/StrapBot.git) se vuoi usare un bot usabile e mantenuto. Non richiede il logviewer!
## Che cosa è questo?

Per vedere i tuoi log hostati da te, devi fare un deploy di questa applicazione. Prima di fare un deploy dell'applicazione, crea una variabile di configurazione chiamata `MONGO_URI` e metti il tuo URI di connessione MongoDB dalla precedente sezione nel campo valore. Prendi l'url di quest'app dopo che hai fatto il deploy e inseriscila come variabile di configurazione `LOG_URL` nell'app bot VincyBot07.

## Aggiornamenti

Puoi aggiornare automaticamente il logviewer sul tuo account Heroku quando ulteriori modifiche saranno effettuate a questa repo.

Per attivare autoaggiornamenti, copia questa repo e [installa l'app Pull sulla tua copia](https://github.com/apps/pull). Poi vai sul tab di Deploy nella tua app Heroku, seleziona GitHub e connetti la tua copia. Attiva l'auto-deploy per il branch master.

## Contribuire

Se puoi effettuare migliorie al design e alla presentazione dei log, per favore crea una richiesta pull con i cambiamenti.
