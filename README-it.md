# Awesome NF-e

> Nota fiscale elettronica per chi integra: portali ufficiali, librerie per linguaggio, API di emissione e server MCP.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-sottoscrivi-111111?style=flat-square)](https://go.mymarketing.click/nfe-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/nfe-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/it.xml) ![35 elementi](https://img.shields.io/badge/elementi-35-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-6b6b6b?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Per chi deve emettere, ricevere o verificare la nota fiscale all'interno di un sistema. Si parte dai portali dove si trovano manuali e schemi, si passa per le librerie aperte di ogni linguaggio e si chiude con le API che emettono per tuo conto. Ogni indirizzo è stato aperto prima di essere inserito.

## Contenuto

- [Portali ufficiali](#portali-ufficiali)
- [Librerie PHP](#librerie-php)
- [Librerie Java](#librerie-java)
- [Librerie .NET](#librerie-net)
- [Librerie Python](#librerie-python)
- [Librerie JavaScript e TypeScript](#librerie-javascript-e-typescript)
- [Delphi e Lazarus](#delphi-e-lazarus)
- [API di emissione](#api-di-emissione)
- [Server MCP](#server-mcp)
- [Altre liste](#altre-liste)
- [Etichette](#etichette)
- [Come contribuire](#come-contribuire)
- [Altre liste](#altre-liste)
- [Realizzato da Ciro Cesar Maciel](#realizzato-da-ciro-cesar-maciel)
- [Licenza](#licenza)

## Portali ufficiali

Dove trovare manuali, schemi e note tecniche di ogni documento.

- [Portal Nacional da NF-e](https://go.mymarketing.click/nfe-portal-nacional-da-nf-e) - Manuali di orientamento, schemi XML, note tecniche e la consultazione di NF-e. `ufficiale` `gratis`
- [NFS-e Nacional](https://go.mymarketing.click/nfe-nfs-e-nacional) - Lo standard nazionale della fattura di servizio, con l'emittente pubblico e l'ambiente dati. `ufficiale` `gratis`
- [NFS-e Nacional: documentação técnica](https://go.mymarketing.click/nfe-nfs-e-nacional-documentacao-tecnica) - Manuali, layout e API della NFS-e Nazionale per chi integra. `ufficiale` `gratis` `API`
- [Portal da NFC-e](https://go.mymarketing.click/nfe-portal-da-nfc-e) - Documentazione della fattura al consumatore sul portale della SVRS, usato da vari stati. `ufficiale` `gratis`
- [Portal Nacional do CT-e](https://go.mymarketing.click/nfe-portal-nacional-do-ct-e) - Manuali e schemi del conhecimento de transporte eletrônico (CT-e). `ufficiale` `gratis`
- [Portal do MDF-e](https://go.mymarketing.click/nfe-portal-do-mdf-e) - Documentazione del manifesto elettronico dei documenti fiscali. `ufficiale` `gratis`
- [Portal do SPED](https://go.mymarketing.click/nfe-portal-do-sped) - Il Sistema Pubblico di Scrittura Digitale della Receita Federal: EFD, ECD, ECF e programmi di validazione. `ufficiale` `gratis`

## Librerie PHP

Attive, con attività nel repository nel 2026.

- [sped-nfe](https://go.mymarketing.click/nfe-sped-nfe) - La libreria più usata per generare, firmare e trasmettere NF-e e NFC-e alle SEFAZ. `open source`
- [sped-common](https://go.mymarketing.click/nfe-sped-common) - Le classi comuni di NFePHP per NF-e, CT-e e MDF-e: certificato, firma e comunicazione. `open source`
- [nfse-php](https://go.mymarketing.click/nfe-nfse-php) - SDK PHP per la NFS-e Nazionale. `open source` `SDK`
- [php-nfse](https://go.mymarketing.click/nfe-php-nfse) - Generazione e comunicazione di NFS-e con i comuni. `open source`
- [Cliente PHP da NFE.io](https://go.mymarketing.click/nfe-cliente-php-da-nfe-io) - SDK PHP di NFE.io per emettere NFS-e, senza dipendenze. `open source` `SDK`

## Librerie Java

Attive, con attività nel repository nel 2026.

- [Java_NFe](https://go.mymarketing.click/nfe-java-nfe) - NF-e e NFC-e in Java, con consultazione, invio, annullamento ed eventi. `open source`
- [wmixvideo/nfe](https://go.mymarketing.click/nfe-wmixvideo-nfe) - Fattura elettronica in Java, con il modello dati completo. `open source`

## Librerie .NET

Attive, con attività nel repository nel 2026.

- [DFe.NET](https://go.mymarketing.click/nfe-dfe-net) - Generazione di NF-e e NFC-e e utilizzo dei servizi della SEFAZ in C#. `open source`
- [ZeusFiscal](https://go.mymarketing.click/nfe-zeusfiscal) - Emissione e stampa di NF-e, NFC-e, MDF-e e CT-e in C#. `open source`
- [Unimake DFe](https://go.mymarketing.click/nfe-unimake-dfe) - DLL per integrare gli ERP con i documenti fiscali elettronici. `open source`
- [OpenAC.Net.NFSe](https://go.mymarketing.click/nfe-openac-net-nfse) - Emissione e trasmissione di NFS-e per vari standard municipali. `open source`
- [OpenAC.Net.NFSe.Nacional](https://go.mymarketing.click/nfe-openac-net-nfse-nacional) - Emissione di NFS-e nello standard nazionale in C#. `open source`

## Librerie Python

Attive, con attività nel repository nel 2026.

- [PyNFe](https://go.mymarketing.click/nfe-pynfe) - Interfaccia con il webservice della NF-e e della NFC-e in Python. `open source`
- [nfelib](https://go.mymarketing.click/nfe-nfelib) - Binding Python per leggere e generare l'XML di NF-e, NFS-e Nazionale, CT-e, MDF-e e BP-e. `open source`
- [Localização brasileira do Odoo](https://go.mymarketing.click/nfe-localizacao-brasileira-do-odoo) - I moduli fiscali brasiliani di Odoo, inclusa la NF-e. `open source`

## Librerie JavaScript e TypeScript

Attive, con attività nel repository nel 2026.

- [NFeWizard](https://go.mymarketing.click/nfe-nfewizard) - Libreria Node.js per i servizi della SEFAZ: emissione, consultazione, eventi e DANFE. `open source`
- [node-sped-nfe](https://go.mymarketing.click/nfe-node-sped-nfe) - Emissione e comunicazione di NF-e con le SEFAZ in Node.js. `open source`
- [Cliente Node.js da NFE.io](https://go.mymarketing.click/nfe-cliente-node-js-da-nfe-io) - SDK TypeScript di NFE.io per emettere NFS-e, senza dipendenze. `open source` `SDK`

## Delphi e Lazarus

Componenti per automazione commerciale per Delphi e Lazarus.

- [Projeto ACBr](https://go.mymarketing.click/nfe-projeto-acbr) - Componenti per automazione commerciale in Delphi e Lazarus, con NF-e, NFC-e, NFS-e, CT-e e SPED. `open source`
- [ACBr no GitHub](https://go.mymarketing.click/nfe-acbr-no-github) - Mirror del repository SVN del progetto ACBr. `open source`

## API di emissione

Servizi che emettono per te. In ordine alfabetico.

- [eNotas](https://go.mymarketing.click/nfe-enotas) - Emissione automatica di NFS-e e NF-e per chi vende online. `a pagamento` `API`
- [Focus NFe](https://go.mymarketing.click/nfe-focus-nfe) - API per NF-e, NFC-e, NFS-e, CT-e e MDF-e. `a pagamento` `API`
- [NFE.io](https://go.mymarketing.click/nfe-nfe-io) - API per l'emissione di NFS-e e NF-e e la consultazione di dati fiscali. `a pagamento` `API`
- [PlugNotas](https://go.mymarketing.click/nfe-plugnotas) - API di Tecnospeed per NF-e, NFC-e e NFS-e in migliaia di comuni. `a pagamento` `API`
- [Qive](https://go.mymarketing.click/nfe-qive) - Acquisizione e gestione delle fatture ricevute, già chiamata Arquivei. `a pagamento` `API`
- [Webmania](https://go.mymarketing.click/nfe-webmania) - API REST per NF-e, NFC-e e NFS-e. `a pagamento` `API`

## Server MCP

Per consentire all'agente IA di consultare e verificare documenti fiscali.

- [mcp-fiscal-brasil](https://go.mymarketing.click/nfe-mcp-fiscal-brasil) - Server MCP fiscale: CNPJ, NF-e, NFS-e, CT-e, SPED, eSocial e Simples Nacional. `open source`

## Altre liste

Attive, con attività nel repository nel 2026.

- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - Server MCP per servizi brasiliani, anche fiscali. `gratis`

## Etichette

Ogni voce spiega di cosa si tratta. Le etichette accanto aiutano a scegliere: ufficiale quando viene da chi definisce lo standard, open source quando il codice è pubblicato, gratis o a pagamento in base al modello d'uso, API e SDK in base al modo di integrare. Le voci con l'etichetta "dell'autore" sono realizzate da Ciro Cesar Maciel e seguono le stesse regole di tutte le altre.

## Come contribuire

Conosci qualcosa che manca, è cambiato o non funziona più? Apri una issue con il modulo di nuova inclusione oppure invia una pull request modificando data/list.json. Il README di ogni lingua viene generato a partire da questo file.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Altre liste

Liste curate nello stesso formato, in portoghese e in altre 14 lingue.

- [Awesome IA no trabalho](https://go.mymarketing.click/nfe-lista-ia-no-trabalho) - IA sul lavoro, per professione: assistenti, privacy, norme e fonti ufficiali per verificare ciò che l'IA ha scritto.
- [Awesome IA na advocacia](https://go.mymarketing.click/nfe-lista-ia-advocacia) - IA per avvocati: assistenti, privacy, norme sull'IA nell'avvocatura e nella magistratura, e le fonti ufficiali per verificare.
- [Awesome IA na contabilidade](https://go.mymarketing.click/nfe-lista-ia-contabilidade) - IA per commercialisti: assistenti, privacy, norme del CFC e le fonti dell'Agenzia delle Entrate, di eSocial e del Simples Nacional per verificare.
- [Awesome IA na sala de aula](https://go.mymarketing.click/nfe-lista-ia-sala-de-aula) - IA per insegnanti: assistenti, età minima e privacy di ciascuno, e le norme sull'istruzione per verificare.
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/nfe-lista-ia-atendimento-e-vendas) - IA per chi assiste e vende: assistenti, privacy, diritti dei consumatori e le regole di lavoro di chi sta al banco, alla cassa e al telefono.
- [Awesome IA no escritório](https://go.mymarketing.click/nfe-lista-ia-escritorio) - IA per segretari, assistenti e addetti amministrativi: assistenti, privacy, redazione ufficiale e truffe che arrivano via e-mail.
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/nfe-lista-ia-pequeno-negocio) - IA per il MEI e il piccolo imprenditore: assistenti, privacy, le regole del MEI e del Simples Nacional, del consumatore e della LGPD per chi è piccolo.
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/nfe-lista-ia-primeiro-trabalho) - IA per chi sta iniziando a lavorare: assistenti, privacy, dove cercare lavoro, i diritti del primo impiego e le truffe dell'offerta falsa.
- [Awesome Pix](https://go.mymarketing.click/nfe-lista-pix) - Pix per chi integra: norme, API, SDK, fornitori e strumenti, verificati uno per uno.
- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - Server MCP per servizi brasiliani: dati pubblici, CNPJ, fiscale, giuridico, mercato finanziario, commercio e pagamenti.
- [Awesome livros de IA](https://go.mymarketing.click/nfe-lista-livros-ia) - Libri sull'intelligenza artificiale in portoghese: dal primo utilizzo alla professione, da chi costruisce al dibattito.
- [Awesome ferramentas online](https://go.mymarketing.click/nfe-lista-ferramentas-online) - Strumenti gratuiti che si aprono nel browser, senza installare: immagini, PDF, testo, codice, siti, e-mail, video e vendite.
- [Awesome APIs Brasil](https://go.mymarketing.click/nfe-lista-apis-brasil) - API pubbliche brasiliane: CEP, CNPJ, Banco Central, IBGE, Legislativo, Judiciário, festività e dati aperti.
- [Awesome Claude Code BR](https://go.mymarketing.click/nfe-lista-claude-code-br) - Claude Code in portoghese: documentazione, corsi, skill, regole, plugin e server MCP realizzati in Brasile.
- [Awesome pagamentos Brasil](https://go.mymarketing.click/nfe-lista-pagamentos-brasil) - Pagamenti in Brasile per chi integra: norme, gateway, acquirer, boleto, abbonamenti, split e antifrode.
- [Awesome Open Finance Brasil](https://go.mymarketing.click/nfe-lista-open-finance-brasil) - Open Finance e Open Insurance in Brasile: norme, specifiche, dati aperti, aggregatori e codice aperto.
- [Awesome WhatsApp API](https://go.mymarketing.click/nfe-lista-whatsapp-api) - WhatsApp per gli integratori: l'API ufficiale di Meta, i provider, le librerie non ufficiali e il rischio di ciascuna strada.
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/nfe-lista-empresa-de-uma-pessoa) - Ciò che serve a una persona per gestire un'intera attività con agenti IA: mettere online, incassare, misurare, promuoversi e farsi trovare.

## Realizzato da Ciro Cesar Maciel

Usare ciò che faccio è anche un modo per sostenere queste liste.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-agents)

## Licenza

Questa lista è sotto CC0 1.0: copia, adatta e ridistribuisci come preferisci, senza chiedere permesso. Il codice del generatore è in awesome-kit, sotto licenza MIT.

<sub>Aggiornata il 2026-11-10.</sub>
