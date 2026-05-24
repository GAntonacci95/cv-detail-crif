# cv-detail-crif (2022 - 2025)

## EN 🇬🇧

### CreMA for LegalTech

The batch project aimed at building a state machine to produce a final json
including enrichment data coming from external providers (business information, financial statement,
people diligence and investigation, real estate information, GenAI language model APIs), and model forecasts related to risk over credit portfolios.

The solution strategy involved:

- Data and artifact stack: data was stored into s3 datalakes as partitioned parquets including timestamps to create a history, the data loaded from the database followed an ETL pipeline and exploited schemas and a data lineage strategy;
- Infrastructure stack: the application run through flow automated and orchestrated lambda functions;
- Software stack: the lambdas dynamically loaded wheels, packages, and layers designed for independence and modularity to grant quality, usability and maintainability.
Logs and e-mails were introduced to monitor executions and metrics.
    
The solution expected results include: reduced enrichment time, reduced human error, enhanced operators productivity, and support for legal action decisions. However, we designed no quantitative kpi to highlight the process improvements.

Hard skill: athena, sql, git, zeep, xmltojson, networkx, jsonpointer, cython, setuptools, simple email service, cloudwatch;

Soft skill: creativity, detail and goal orientation, determination, focus, speed, independence, reflection, team-work beginner, information handling beginner.

### CreMA Scoring

The batch project aimed at building a produzionalization AWS architecture for the scoring and visualization of batch portfolios using machine learning models.

The architecture was customized based on markets and customers dimensions.
What is more, the challenge involved the development of a
custom framework fitting the MLOops (CL-CI-CD) practices in order to automatize processes (see prediction, validation, back-testing), and leading the autonomy of data scientists towards a more structured coding approach.

The solution strategy involved:
- Data and artifact stack: data was stored into s3 datalakes as partitioned parquets including timestamps to create a history;
- Infrastructure stack: the application run in a docker image tagged into ECR and loaded by a step-function. The step-function delt with the flow and dynamically loaded an always up-to-date code-commit repository;
- Software stack: the pipelines were built upon abstraction to meet client and market dimensions, so to have a custom execution depending on incoming data.
    
The solution expected results include: reduced deployment time thanks to pipelines abstraction, and easiness of usage by the team working on model updates via sagemaker.

Hard skill: python, aws, triggers, events, schedules, quicksight, pandas, code-commit, sagemaker.

### Single-deal APIs for insurance and business customers

Two more project streams involved the development of single-deal API in order to provide risk scores of credit portfolio entries with the guarantee of the ACID property.

To do so, models were dynamically loaded in case of need and an input, intermediate, output and enrichment history was hold for sake of traceability.
The intermediate and output results were analysed in the UAT stage to validate model performances.

Hard skill: pymee, pydantic, pickle, logger, log stream, stochastic finite state machine architecture;

Soft skill: market separation, brewer and nash model in communications, logs and storage.

### Other less significant projects

- Usage of azure databricks, pyspark notebooks, power bi, dax;
- Porting of local notebooks on azure infrastructure, intuition of hr processes and people analytics;


## IT 🇮🇹

### CreMA per LegalTech

Progetto batch che mirava alla costruzione di una macchina a stati per produrre un json contenente dati di arricchimento provenienti da diversi provider esterni (informazioni di business, dati di bilancio, diligence e rintracci, informazioni mobiliari ed immobiliari, GenAI, API verso LLM) e previsioni di modelli relativi al rischio su portafogli di credito.

La strategia risolutiva incorporava:

- Stack dati ed artefatti: i dati erano salvati in datalake s3 come parquet partizionati ed includevano timestamp per creare uno storico. Il caricamento dati da database seguiva una pipeline ETL, sfruttava schemi ed utilizzava una strategia di lineage elementare;
- Stack infrastrutturale: l'applicazione eseguiva tramite un flusso di lambda function automatizzato tramite un orchestratore;
- Stack applicativo: le lambda caricavano dinamicamente wheels, pacchetti e layer progettati per indipendenza e modularità al fine di garantire qualità, usabilità e manutenibilità.
Inoltre, sono stati introdotti log e metriche per monitorare le esecuzioni.

I risultati attesi dalla soluzione includono: tempi di arricchimento ed errore umano ridotti, migliore produttività degli operatori e supporto per decisioni in merito ad azionabilità legale. Tuttavia non sono stati definiti kpi quantitativi per valutare i miglioramenti dello stream progettuale.

Skill verticali: athena, sql, git, zeep, xmltojson, networkx, jsonpointer, cython, setuptools, simple email service, cloudwatch;
 
Skill orizzontali: creatività, orientamento a dettaglio e gol, determinazione, concentrazione, velocità, indipendenza, riflessività, principio di lavoro di squadra e gestione informativa.

### CreMA Scoring

Progetto batch che mirava alla costruzione di un'architettura AWS per emulare la messa in produzione di modelli di machine learning per lo scoring e la visualizzazione di portafogli di credito.

L'architettura era personalizzata dipendentemente dalle dimensioni mercato e cliente.
Inoltre, la sfida prevedeva lo sviluppo di un framework custom che aderisse a principi di MLOps (CL-CI-CD) al fine di automatizzare processi (quali predizione, validazione, back-testing) e di guidare l'autonomia dei data scientists verso un approccio di sviluppo più strutturato.

La strategia risolutiva prevedeva:

- Stack dati ed artefatti: i dati erano salvati in datalake s3 come parquet partizionati per creare uno storico;

- Stack infrastrutturale: l'applicazione eseguiva in una docker image taggata in ECR. Questa era caricata da una step function che si occupava della gestione del flusso d'esecuzione e del caricamento dinamico di codice da una repository code-commit sempre aggiornata;

- Stack applicativo: le pipeline per mercato e cliente erano costruite implementando astrazioni in modo da garantire un'esecuzione personalizzata dipendenemente dai dati in arrivo.

I risultati attesi della soluzione includono: riduzione del tempo di deployment e semplicità di utilizzo da parte del team che lavora su aggiornamenti di modello tramite sagemaker.

Hard skill: python, aws, triggers, events, schedules, quicksight, pandas, code-commit, sagemaker.

### API single-deal per clienti assicurativi e business

Un paio di ulteriori stream progettuali riguardavano lo sviluppo di API single-deal per fornire score di rischio credito relativo a portafogli garantendo la proprietà ACID.

Per farlo, i modelli erano caricati dinamicamente al bisogno e si teneva storico di informazioni d'ingresso, intermedie, d'arricchimento e d'uscita a fini di tracciabilità.
I risultati intermedi e d'uscita sono stati analizzati in fase di UAT per validare le performance di modello.

Skill verticali: pymee, pydantic, pickle, logger, log stream, architettura macchina a stati finiti stocastica;

Skill orizzontali: separazione di mercati, modello di comunicazione brewer and nash, monitoraggio e mantenimento logs.

### Altri progetti meno significativi

- Uso di azure databricks, pyspark notebooks, power bi, dax;

- Porting di notebook locali su infrastruttura azure, intuizione del funzionamento di processi hr e di analisi personale;



