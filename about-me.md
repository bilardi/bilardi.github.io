---
layout: page
title: About me
title_it: Chi sono
permalink: /about-me/
pdf: true
author: Alessandra Bilardi
---

<div class="lang-en" markdown="1">

I bridge business needs and technology, turning complex data & AI challenges into reliable, production-ready solutions. From architecture to code, I help teams move from ideas and assessment to implementation and delivery.

## End-to-end data & AI architect

I help teams turn business needs into practical technical solutions, from assessment and architecture design to the planning of activities and migrations, up to PoCs and MVPs for presales or before committing development resources. I combine hands-on engineering with end-to-end ownership, and the mentoring of new people with knowledge sharing, to help teams grow and deliver reliable, maintainable solutions.

End-to-end for data & AI solutions means following projects that go from data ingestion and transformation to visualization for Ops and BI, or from data analysis to prediction or generative AI; from infrastructure to development, securely and with DataOps, DevOps, MLOps and LLMOps best practices. Examples can be a data flow from the assembly line to the cloud, to handle anomaly detection or predictive maintenance, a sales forecast, or else an agentic system for anything.

## How I work

I have [over 20 years of experience](https://s3.eu-west-1.amazonaws.com/cdn.bilardi.net/resume/about/Alessandra.Bilardi.CV.pdf) in data and software, over 15 in leadership roles and over 10 in on-premises and cloud operations: this gives me a 360-degree view. I prefer teamwork, from design to implementation, from deploy to monitoring: involving people makes them more aware and responsible. Those who worked with me as a lead describe me as a supportive figure, pragmatic and methodical, attentive to discussion and to software quality, with tests and documentation.

I automate and document my work, also because I have a terrible memory. I like experimenting with new tools and methodologies, sharing the experiences through [technical articles](https://dev.to/bilardi), [meetups and conferences]({{ site.baseurl }}{{ site.activities_url }}). I am comfortable wearing different hats and I prefer direct technical contribution, taking part in team coordination when needed.

## Examples

I have worked with AI in different contexts, from model training to SRE. I like tackling concrete problems, experimenting with alternatives and building AI solutions integrated into real processes. Here are the latest interesting projects of this year.

**Text classification.** Comparing a managed service with local algorithms pays off: in my experience, a linear model, preceded by a text vectorization with a cap on frequencies, can beat BlazingText, and the fine-tuning of an SLM reaches comparable results. Brought to production behind an API: the model requires an asynchronous handling of the responses, to prevent the cold start of the endpoint from exceeding the API timeout.

**Agentic code generation.** To query APIs with different data models and policies, an orchestrator gives an agent the question, the data model and the Python stubs of the APIs: the agent writes the code to call them and returns a JSON answer, checked by deterministic validations and by a relevance check; then a second agent adapts the answer to the user profile. Born locally with LangGraph and Langfuse, the same flow can be brought to AWS with Amazon Bedrock AgentCore.

**Adaptive browser automation.** Python scripts with Playwright can follow interfaces that change over time: pages are saved and compared, changes are detected and, when needed, an agentic flow with Claude Code and dedicated skills updates the code with a TDD process. The merge into production is preceded by a trial run with human review.

</div>

<div class="lang-it" markdown="1">

Faccio da ponte tra le esigenze di business e la tecnologia, trasformando sfide complesse di data & AI in soluzioni affidabili e pronte per la produzione. Dall'architettura al codice, aiuto i team a passare dalle idee e dall'assessment all'implementazione e al delivery.

## End-to-end data & AI architect

Aiuto i team a trasformare le esigenze di business in soluzioni tecniche concrete, dall'assessment e progettazione dell'architettura alla pianificazione delle attività, migrazioni, fino a PoC e MVP per il presales o prima di impegnare risorse di sviluppo. Unisco l'engineering hands-on alla responsabilità end-to-end, il mentoring di nuove figure alla condivisione delle conoscenze, per aiutare i team a crescere e a consegnare soluzioni affidabili e manutenibili.

End-to-end per soluzioni data & AI vuol dire seguire progetti che vanno dall'ingestion dei dati e loro trasformazione, alla visualizzazione per Ops e BI, o dall'analisi dei dati, alla predizione o all'AI generativa; dall'infrastruttura allo sviluppo, in sicurezza e con le best practice DataOps, DevOps, MLOps e LLMOps. Esempi possono essere un flusso di dati dalla catena di montaggio al cloud, per gestire anomaly detection o predictive maintenance, un forecasting per le vendite, oppure un sistema agentico per qualsiasi cosa.

## Come lavoro

Ho [oltre 20 anni di esperienza](https://s3.eu-west-1.amazonaws.com/cdn.bilardi.net/resume/about/Alessandra.Bilardi.CV.pdf) in data e software, oltre 15 in ruoli di leadership e oltre 10 nelle operations on-premises e cloud: questo mi permette di avere una visione a 360 gradi. Prediligo il gioco di squadra, dalla progettazione all'implementazione, dal deploy al monitoring: coinvolgere le persone le rende più consapevoli e responsabili. Chi ha lavorato con me come lead mi definisce una figura di supporto, pragmatica e metodica, attenta al confronto e alla qualità del software, con test e documentazione.

Automatizzo e documento il mio lavoro, anche perché ho una pessima memoria. Mi piace sperimentare nuovi strumenti e metodologie, condividendo le esperienze attraverso [articoli tecnici](https://dev.to/bilardi), [meetup e conferenze]({{ site.baseurl }}{{ site.activities_url }}). Mi trovo a mio agio con cappelli diversi e prediligo il contributo tecnico diretto, partecipando al coordinamento del team quando serve.

## Esempi

Ho lavorato con l'AI in contesti diversi, dall'addestramento di modelli all'SRE. Mi piace affrontare problemi concreti, sperimentare alternative e costruire soluzioni AI integrate nei processi reali. Seguono gli ultimi progetti interessanti di quest'anno.

**Classificazione di testi.** Confrontare un servizio gestito con algoritmi in locale ripaga: nella mia esperienza, un modello lineare, preceduto da una vettorializzazione testuale con un tetto massimo alle frequenze, può superare BlazingText, e il fine-tuning di uno SLM ottiene risultati comparabili. Portato in produzione dietro a un'API: il modello richiede una gestione asincrona delle risposte, per evitare che il cold start dell'endpoint superi il timeout dell'API.

**Generazione agentica di codice.** Per interrogare API con data model e politiche differenti, un orchestratore fornisce a un agente la domanda, il data model e gli stub Python delle API: l'agente genera il codice per chiamarle e restituisce una risposta JSON, sottoposta a validazioni deterministiche e a un controllo di pertinenza; poi un secondo agente adatta la risposta al profilo dell'utente. Nato in locale con LangGraph e Langfuse, lo stesso flusso può essere portato su AWS con Amazon Bedrock AgentCore.

**Automazioni browser adattive.** Script Python con Playwright possono seguire interfacce che cambiano nel tempo: le pagine vengono salvate e confrontate, le modifiche rilevate e, quando serve, un flusso agentico con Claude Code e skill dedicate aggiorna il codice con un processo basato su TDD. Il merge in produzione è preceduto da un'esecuzione di prova con revisione umana.

</div>
