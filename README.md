# anpr-dotnet
ANPR .NET SDK

### Finalità
Questo progetto nasce come contributo al progetto ANPR (Anagrafe Nazionale Persone Residenti), per facilitare lo sviluppo di applicazioni .NET scritte in C# che hanno necessità di utilizzare tale servizio.

Al momento è solo un primo esperimento di generazione delle classi C# a partire dalla documentazione wsdl contenuta nel progetto creato dal Team di Trasformazione Digitale: https://github.com/italia/anpr.

### Roadmap
Prima di poter fissare gli obiettivi e quindi il contenuto dell'SDK, vi sono alcune questioni aperte che sono state sottoposte al TTD:

- L'interfaccia ai servizi sarà necessariamente mediante Web Services SOAP o si può immaginare un ulteriore servizio di tipo RESTFull ?
- Nel caso in cui Web Service SOAP sia un requisito (tecnico / legale) non modificabile, è ipotizzabile lo sviluppo di un servizio RESTFull che sia affiancato (ovvero interfacciato direttamante con il database) o che funga da facade (ovvero interposto tra il client e il servizio Web Service SOAP) ?
- Ambiente di test
