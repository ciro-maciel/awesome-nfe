# Awesome NF-e

> Note fiscale électronique pour les intégrateurs : portails officiels, bibliothèques par langage, API d'émission et serveurs MCP.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-s'abonner-111111?style=flat-square)](https://go.mymarketing.click/nfe-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/nfe-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/fr.xml) ![35 éléments](https://img.shields.io/badge/%C3%A9l%C3%A9ments-35-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-6b6b6b?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Pour ceux qui doivent émettre, recevoir ou vérifier une note fiscale dans un système. On commence par les portails où se trouvent les manuels et les schémas, on passe par les bibliothèques ouvertes de chaque langage et on termine avec les API qui émettent pour vous. Chaque adresse a été ouverte avant d'être ajoutée.

## Contenu

- [Portails officiels](#portails-officiels)
- [Bibliothèques PHP](#bibliothèques-php)
- [Bibliothèques Java](#bibliothèques-java)
- [Bibliothèques .NET](#bibliothèques-net)
- [Bibliothèques Python](#bibliothèques-python)
- [Bibliothèques JavaScript et TypeScript](#bibliothèques-javascript-et-typescript)
- [Delphi et Lazarus](#delphi-et-lazarus)
- [API d'émission](#api-démission)
- [Serveurs MCP](#serveurs-mcp)
- [Autres listes](#autres-listes)
- [Étiquettes](#étiquettes)
- [Comment contribuer](#comment-contribuer)
- [Autres listes](#autres-listes)
- [Réalisé par Ciro Cesar Maciel](#réalisé-par-ciro-cesar-maciel)
- [Licence](#licence)

## Portails officiels

Où trouver les manuels, les schémas et les notes techniques de chaque document.

- [Portal Nacional da NF-e](https://go.mymarketing.click/nfe-portal-nacional-da-nf-e) - Manuels d'orientation, schémas XML, notes techniques et consultation de NF-e. `officiel` `gratuit`
- [NFS-e Nacional](https://go.mymarketing.click/nfe-nfs-e-nacional) - Le standard national de la facture de service, avec l'émetteur public et l'environnement de données. `officiel` `gratuit`
- [NFS-e Nacional: documentação técnica](https://go.mymarketing.click/nfe-nfs-e-nacional-documentacao-tecnica) - Les manuels, leiautes et API de la NFS-e Nationale pour les intégrateurs. `officiel` `gratuit` `API`
- [Portal da NFC-e](https://go.mymarketing.click/nfe-portal-da-nfc-e) - Documentation de la facture de consommateur sur le portail de la SVRS, utilisé par plusieurs États. `officiel` `gratuit`
- [Portal Nacional do CT-e](https://go.mymarketing.click/nfe-portal-nacional-do-ct-e) - Manuels et schémas du conhecimento de transporte eletrônico (CT-e). `officiel` `gratuit`
- [Portal do MDF-e](https://go.mymarketing.click/nfe-portal-do-mdf-e) - Documentation du manifeste électronique de documents fiscaux. `officiel` `gratuit`
- [Portal do SPED](https://go.mymarketing.click/nfe-portal-do-sped) - Le Système public de tenue de comptabilité numérique de la Receita Federal : EFD, ECD, ECF et programmes de validation. `officiel` `gratuit`

## Bibliothèques PHP

Actives, avec une activité dans le dépôt en 2026.

- [sped-nfe](https://go.mymarketing.click/nfe-sped-nfe) - La bibliothèque la plus utilisée pour générer, signer et transmettre NF-e et NFC-e aux SEFAZ. `open source`
- [sped-common](https://go.mymarketing.click/nfe-sped-common) - Les classes communes de NFePHP pour NF-e, CT-e et MDF-e : certificat, signature et communication. `open source`
- [nfse-php](https://go.mymarketing.click/nfe-nfse-php) - SDK PHP pour la NFS-e Nationale. `open source` `SDK`
- [php-nfse](https://go.mymarketing.click/nfe-php-nfse) - Génération et communication de NFS-e avec les municipalités. `open source`
- [Cliente PHP da NFE.io](https://go.mymarketing.click/nfe-cliente-php-da-nfe-io) - SDK PHP de NFE.io pour émettre des NFS-e, sans dépendances. `open source` `SDK`

## Bibliothèques Java

Actives, avec une activité dans le dépôt en 2026.

- [Java_NFe](https://go.mymarketing.click/nfe-java-nfe) - NF-e et NFC-e en Java, avec consultation, envoi, annulation et événements. `open source`
- [wmixvideo/nfe](https://go.mymarketing.click/nfe-wmixvideo-nfe) - Facture électronique en Java, avec le modèle de données complet. `open source`

## Bibliothèques .NET

Actives, avec une activité dans le dépôt en 2026.

- [DFe.NET](https://go.mymarketing.click/nfe-dfe-net) - Génération de NF-e et NFC-e et consommation des services de la SEFAZ en C#. `open source`
- [ZeusFiscal](https://go.mymarketing.click/nfe-zeusfiscal) - Émission et impression de NF-e, NFC-e, MDF-e et CT-e en C#. `open source`
- [Unimake DFe](https://go.mymarketing.click/nfe-unimake-dfe) - DLL pour intégrer les ERP aux documents fiscaux électroniques. `open source`
- [OpenAC.Net.NFSe](https://go.mymarketing.click/nfe-openac-net-nfse) - Émission et transmission de NFS-e pour plusieurs standards municipaux. `open source`
- [OpenAC.Net.NFSe.Nacional](https://go.mymarketing.click/nfe-openac-net-nfse-nacional) - Émission de NFS-e au standard national en C#. `open source`

## Bibliothèques Python

Actives, avec une activité dans le dépôt en 2026.

- [PyNFe](https://go.mymarketing.click/nfe-pynfe) - Interface avec le webservice de la NF-e et de la NFC-e en Python. `open source`
- [nfelib](https://go.mymarketing.click/nfe-nfelib) - Bindings Python pour lire et générer le XML de NF-e, NFS-e Nationale, CT-e, MDF-e et BP-e. `open source`
- [Localização brasileira do Odoo](https://go.mymarketing.click/nfe-localizacao-brasileira-do-odoo) - Les modules fiscaux brésiliens d'Odoo, y compris NF-e. `open source`

## Bibliothèques JavaScript et TypeScript

Actives, avec une activité dans le dépôt en 2026.

- [NFeWizard](https://go.mymarketing.click/nfe-nfewizard) - Bibliothèque Node.js pour les services de la SEFAZ : émission, consultation, événements et DANFE. `open source`
- [node-sped-nfe](https://go.mymarketing.click/nfe-node-sped-nfe) - Émission et communication de NF-e avec les SEFAZ en Node.js. `open source`
- [Cliente Node.js da NFE.io](https://go.mymarketing.click/nfe-cliente-node-js-da-nfe-io) - SDK TypeScript de NFE.io pour émettre des NFS-e, sans dépendances. `open source` `SDK`

## Delphi et Lazarus

Composants d'automatisation commerciale pour Delphi et Lazarus.

- [Projeto ACBr](https://go.mymarketing.click/nfe-projeto-acbr) - Composants d'automatisation commerciale pour Delphi et Lazarus, avec NF-e, NFC-e, NFS-e, CT-e et SPED. `open source`
- [ACBr no GitHub](https://go.mymarketing.click/nfe-acbr-no-github) - Miroir du dépôt SVN du projet ACBr. `open source`

## API d'émission

Services qui émettent à votre place. Par ordre alphabétique.

- [eNotas](https://go.mymarketing.click/nfe-enotas) - Émission automatique de NFS-e et NF-e pour les vendeurs en ligne. `payant` `API`
- [Focus NFe](https://go.mymarketing.click/nfe-focus-nfe) - API pour NF-e, NFC-e, NFS-e, CT-e et MDF-e. `payant` `API`
- [NFE.io](https://go.mymarketing.click/nfe-nfe-io) - API pour l'émission de NFS-e et NF-e et la consultation de données fiscales. `payant` `API`
- [PlugNotas](https://go.mymarketing.click/nfe-plugnotas) - API de Tecnospeed pour NF-e, NFC-e et NFS-e dans des milliers de municipalités. `payant` `API`
- [Qive](https://go.mymarketing.click/nfe-qive) - Capture et gestion des factures reçues, anciennement appelé Arquivei. `payant` `API`
- [Webmania](https://go.mymarketing.click/nfe-webmania) - API REST pour NF-e, NFC-e et NFS-e. `payant` `API`

## Serveurs MCP

Pour que l'agent IA consulte et vérifie des documents fiscaux.

- [mcp-fiscal-brasil](https://go.mymarketing.click/nfe-mcp-fiscal-brasil) - Serveur MCP fiscal : CNPJ, NF-e, NFS-e, CT-e, SPED, eSocial et Simples Nacional. `open source`

## Autres listes

Actives, avec une activité dans le dépôt en 2026.

- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - Serveurs MCP pour les services brésiliens, y compris fiscaux. `gratuit`

## Étiquettes

Chaque élément indique ce qu'il est. Les étiquettes à côté aident à choisir : officiel quand il vient de l'organisme qui définit la norme, open source quand le code est publié, gratuit ou payant selon le modèle d'utilisation, API et SDK selon la manière de l'intégrer. Les éléments portant l'étiquette « de l'auteur » sont réalisés par Ciro Cesar Maciel et suivent les mêmes règles que tous les autres.

## Comment contribuer

Vous connaissez quelque chose qui manque, qui a changé ou qui n'est plus en ligne ? Ouvrez une issue avec le formulaire d'ajout ou envoyez une pull request en modifiant data/list.json. Le README de chaque langue est généré à partir de ce fichier.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Autres listes

Listes organisées dans le même format, en portugais et dans 14 autres langues.

- [Awesome IA no trabalho](https://go.mymarketing.click/nfe-lista-ia-no-trabalho) - IA au travail, par métier : assistants, confidentialité, normes et sources officielles pour vérifier ce que l'IA a écrit.
- [Awesome IA na advocacia](https://go.mymarketing.click/nfe-lista-ia-advocacia) - IA pour les avocats : assistants, confidentialité, normes sur l'IA dans la profession et dans la justice, et sources officielles pour vérifier.
- [Awesome IA na contabilidade](https://go.mymarketing.click/nfe-lista-ia-contabilidade) - IA pour les comptables : assistants, confidentialité, normes du CFC et sources de la Receita, de l'eSocial et du Simples pour vérifier.
- [Awesome IA na sala de aula](https://go.mymarketing.click/nfe-lista-ia-sala-de-aula) - IA pour les enseignants : assistants, âge minimum et confidentialité de chacun, et normes de l'éducation pour vérifier.
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/nfe-lista-ia-atendimento-e-vendas) - IA pour ceux qui accueillent et vendent : assistants, confidentialité, droits du consommateur et règles du travail de ceux qui sont au comptoir, à la caisse et au téléphone.
- [Awesome IA no escritório](https://go.mymarketing.click/nfe-lista-ia-escritorio) - IA pour les secrétaires, assistants et auxiliaires administratifs : assistants, confidentialité, rédaction administrative et arnaques par e-mail.
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/nfe-lista-ia-pequeno-negocio) - IA pour le MEI et le petit entrepreneur : assistants, confidentialité, règles du MEI et du Simples, du consommateur et de la LGPD pour les petits acteurs.
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/nfe-lista-ia-primeiro-trabalho) - IA pour ceux qui commencent à travailler : assistants, confidentialité, où chercher un emploi, droits du premier emploi et arnaques aux fausses offres.
- [Awesome Pix](https://go.mymarketing.click/nfe-lista-pix) - Pix pour les intégrateurs : normes, API, SDK, fournisseurs et outils, vérifiés un par un.
- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - Serveurs MCP pour les services brésiliens : données publiques, CNPJ, fiscal, juridique, marché financier, commerce et paiements.
- [Awesome livros de IA](https://go.mymarketing.click/nfe-lista-livros-ia) - Livres sur l'intelligence artificielle en portugais : de la première utilisation à la profession, de ceux qui la construisent au débat.
- [Awesome ferramentas online](https://go.mymarketing.click/nfe-lista-ferramentas-online) - Outils gratuits qui s'ouvrent dans le navigateur, sans installation : image, PDF, texte, code, sites, e-mail, vidéo et ventes.
- [Awesome APIs Brasil](https://go.mymarketing.click/nfe-lista-apis-brasil) - API publiques brésiliennes : CEP, CNPJ, Banco Central, IBGE, Législatif, Judiciaire, jours fériés et données ouvertes.
- [Awesome Claude Code BR](https://go.mymarketing.click/nfe-lista-claude-code-br) - Claude Code en portugais : documentation, cours, skills, règles, plugins et serveurs MCP réalisés au Brésil.
- [Awesome pagamentos Brasil](https://go.mymarketing.click/nfe-lista-pagamentos-brasil) - Paiements au Brésil pour les intégrateurs : normes, passerelles, acquéreurs, boleto, abonnement, split et antifraude.
- [Awesome Open Finance Brasil](https://go.mymarketing.click/nfe-lista-open-finance-brasil) - Open Finance et Open Insurance au Brésil : normes, spécifications, données ouvertes, agrégateurs et code ouvert.
- [Awesome WhatsApp API](https://go.mymarketing.click/nfe-lista-whatsapp-api) - WhatsApp pour les intégrateurs : l'API officielle de Meta, les fournisseurs, les bibliothèques non officielles et le risque de chaque approche.
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/nfe-lista-empresa-de-uma-pessoa) - Ce qu'il faut à une personne pour faire tourner une entreprise entière avec des agents d'IA : mise en ligne, facturation, mesure, promotion et visibilité.

## Réalisé par Ciro Cesar Maciel

Utiliser ce que je fais est aussi une façon de soutenir ces listes.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-agents)

## Licence

Cette liste est sous CC0 1.0 : copiez, adaptez et redistribuez-la comme vous le souhaitez, sans demander la permission. Le code du générateur se trouve dans awesome-kit, sous licence MIT.

<sub>Mise à jour le 2026-11-10.</sub>
