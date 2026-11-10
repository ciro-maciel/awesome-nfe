# Awesome NF-e

> Nota fiscal eletrônica para quem integra: portais oficiais, bibliotecas por linguagem, APIs de emissão e servidores MCP.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-assinar-111111?style=flat-square)](https://go.mymarketing.click/nfe-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/nfe-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/pt.xml) ![35 itens](https://img.shields.io/badge/itens-35-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-6b6b6b?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Para quem precisa emitir, receber ou conferir nota fiscal dentro de um sistema. Começa pelos portais onde estão os manuais e os schemas, passa pelas bibliotecas abertas de cada linguagem e termina nas APIs que emitem por você. Cada endereço foi aberto antes de entrar.

## Conteúdo

- [Portais oficiais](#portais-oficiais)
- [Bibliotecas PHP](#bibliotecas-php)
- [Bibliotecas Java](#bibliotecas-java)
- [Bibliotecas .NET](#bibliotecas-net)
- [Bibliotecas Python](#bibliotecas-python)
- [Bibliotecas JavaScript e TypeScript](#bibliotecas-javascript-e-typescript)
- [Delphi e Lazarus](#delphi-e-lazarus)
- [APIs de emissão](#apis-de-emissão)
- [Servidores MCP](#servidores-mcp)
- [Outras listas](#outras-listas)
- [Etiquetas](#etiquetas)
- [Como contribuir](#como-contribuir)
- [Outras listas](#outras-listas)
- [Feito por Ciro Cesar Maciel](#feito-por-ciro-cesar-maciel)
- [Licença](#licença)

## Portais oficiais

Onde estão os manuais, os schemas e as notas técnicas de cada documento.

- [Portal Nacional da NF-e](https://go.mymarketing.click/nfe-portal-nacional-da-nf-e) - Manuais de orientação, schemas XML, notas técnicas e a consulta de NF-e. `oficial` `grátis`
- [NFS-e Nacional](https://go.mymarketing.click/nfe-nfs-e-nacional) - O padrão nacional da nota fiscal de serviço, com o emissor público e o ambiente de dados. `oficial` `grátis`
- [NFS-e Nacional: documentação técnica](https://go.mymarketing.click/nfe-nfs-e-nacional-documentacao-tecnica) - Os manuais, leiautes e APIs da NFS-e Nacional para quem integra. `oficial` `grátis` `API`
- [Portal da NFC-e](https://go.mymarketing.click/nfe-portal-da-nfc-e) - Documentação da nota fiscal de consumidor no portal da SVRS, usado por vários estados. `oficial` `grátis`
- [Portal Nacional do CT-e](https://go.mymarketing.click/nfe-portal-nacional-do-ct-e) - Manuais e schemas do conhecimento de transporte eletrônico. `oficial` `grátis`
- [Portal do MDF-e](https://go.mymarketing.click/nfe-portal-do-mdf-e) - Documentação do manifesto eletrônico de documentos fiscais. `oficial` `grátis`
- [Portal do SPED](https://go.mymarketing.click/nfe-portal-do-sped) - O Sistema Público de Escrituração Digital da Receita Federal: EFD, ECD, ECF e programas validadores. `oficial` `grátis`

## Bibliotecas PHP

Abertas, com atividade no repositório em 2026.

- [sped-nfe](https://go.mymarketing.click/nfe-sped-nfe) - A biblioteca mais usada para gerar, assinar e transmitir NF-e e NFC-e às SEFAZ. `código aberto`
- [sped-common](https://go.mymarketing.click/nfe-sped-common) - As classes comuns do NFePHP para NF-e, CT-e e MDF-e: certificado, assinatura e comunicação. `código aberto`
- [nfse-php](https://go.mymarketing.click/nfe-nfse-php) - SDK PHP para a NFS-e Nacional. `código aberto` `SDK`
- [php-nfse](https://go.mymarketing.click/nfe-php-nfse) - Geração e comunicação de NFS-e com as prefeituras. `código aberto`
- [Cliente PHP da NFE.io](https://go.mymarketing.click/nfe-cliente-php-da-nfe-io) - SDK PHP da NFE.io para emitir NFS-e, sem dependências. `código aberto` `SDK`

## Bibliotecas Java

Abertas, com atividade no repositório em 2026.

- [Java_NFe](https://go.mymarketing.click/nfe-java-nfe) - NF-e e NFC-e em Java, com consulta, envio, cancelamento e eventos. `código aberto`
- [wmixvideo/nfe](https://go.mymarketing.click/nfe-wmixvideo-nfe) - Nota fiscal eletrônica em Java, com o modelo de dados completo. `código aberto`

## Bibliotecas .NET

Abertas, com atividade no repositório em 2026.

- [DFe.NET](https://go.mymarketing.click/nfe-dfe-net) - Geração de NF-e e NFC-e e consumo dos serviços da SEFAZ em C#. `código aberto`
- [ZeusFiscal](https://go.mymarketing.click/nfe-zeusfiscal) - Emissão e impressão de NF-e, NFC-e, MDF-e e CT-e em C#. `código aberto`
- [Unimake DFe](https://go.mymarketing.click/nfe-unimake-dfe) - DLL para integrar ERPs aos documentos fiscais eletrônicos. `código aberto`
- [OpenAC.Net.NFSe](https://go.mymarketing.click/nfe-openac-net-nfse) - Emissão e transmissão de NFS-e para vários padrões municipais. `código aberto`
- [OpenAC.Net.NFSe.Nacional](https://go.mymarketing.click/nfe-openac-net-nfse-nacional) - Emissão de NFS-e no padrão nacional em C#. `código aberto`

## Bibliotecas Python

Abertas, com atividade no repositório em 2026.

- [PyNFe](https://go.mymarketing.click/nfe-pynfe) - Interface com o webservice da NF-e e da NFC-e em Python. `código aberto`
- [nfelib](https://go.mymarketing.click/nfe-nfelib) - Bindings Python para ler e gerar o XML de NF-e, NFS-e Nacional, CT-e, MDF-e e BP-e. `código aberto`
- [Localização brasileira do Odoo](https://go.mymarketing.click/nfe-localizacao-brasileira-do-odoo) - Os módulos fiscais brasileiros do Odoo, inclusive NF-e. `código aberto`

## Bibliotecas JavaScript e TypeScript

Abertas, com atividade no repositório em 2026.

- [NFeWizard](https://go.mymarketing.click/nfe-nfewizard) - Biblioteca Node.js para os serviços da SEFAZ: emissão, consulta, eventos e DANFE. `código aberto`
- [node-sped-nfe](https://go.mymarketing.click/nfe-node-sped-nfe) - Emissão e comunicação de NF-e com as SEFAZ em Node.js. `código aberto`
- [Cliente Node.js da NFE.io](https://go.mymarketing.click/nfe-cliente-node-js-da-nfe-io) - SDK TypeScript da NFE.io para emitir NFS-e, sem dependências. `código aberto` `SDK`

## Delphi e Lazarus

Componentes de automação comercial para Delphi e Lazarus.

- [Projeto ACBr](https://go.mymarketing.click/nfe-projeto-acbr) - Componentes para automação comercial em Delphi e Lazarus, com NF-e, NFC-e, NFS-e, CT-e e SPED. `código aberto`
- [ACBr no GitHub](https://go.mymarketing.click/nfe-acbr-no-github) - Espelho do repositório SVN do Projeto ACBr. `código aberto`

## APIs de emissão

Serviços que emitem por você. Em ordem alfabética.

- [eNotas](https://go.mymarketing.click/nfe-enotas) - Emissão automática de NFS-e e NF-e para quem vende online. `pago` `API`
- [Focus NFe](https://go.mymarketing.click/nfe-focus-nfe) - API para NF-e, NFC-e, NFS-e, CT-e e MDF-e. `pago` `API`
- [NFE.io](https://go.mymarketing.click/nfe-nfe-io) - API para emissão de NFS-e e NF-e e consulta de dados fiscais. `pago` `API`
- [PlugNotas](https://go.mymarketing.click/nfe-plugnotas) - API da Tecnospeed para NF-e, NFC-e e NFS-e em milhares de municípios. `pago` `API`
- [Qive](https://go.mymarketing.click/nfe-qive) - Captura e gestão das notas fiscais recebidas, antes chamada Arquivei. `pago` `API`
- [Webmania](https://go.mymarketing.click/nfe-webmania) - API REST para NF-e, NFC-e e NFS-e. `pago` `API`

## Servidores MCP

Para o agente de IA consultar e conferir documentos fiscais.

- [mcp-fiscal-brasil](https://go.mymarketing.click/nfe-mcp-fiscal-brasil) - Servidor MCP fiscal: CNPJ, NF-e, NFS-e, CT-e, SPED, eSocial e Simples Nacional. `código aberto`

## Outras listas

Abertas, com atividade no repositório em 2026.

- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - Servidores MCP para serviços brasileiros, inclusive fiscais. `grátis`

## Etiquetas

Cada item diz o que é. As etiquetas ao lado ajudam a escolher: oficial quando vem de quem define o padrão, código aberto quando o código está publicado, grátis ou pago pelo modelo de uso, API e SDK pelo jeito de integrar. Os itens com a etiqueta "do autor" são feitos por Ciro Cesar Maciel e seguem as mesmas regras de todos os outros.

## Como contribuir

Conhece algo que falta, mudou ou saiu do ar? Abra uma issue com o formulário de nova inclusão ou mande um pull request editando data/list.json. O README de cada língua é gerado a partir desse arquivo.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Outras listas

Listas curadas no mesmo formato, em português e em mais 14 línguas.

- [Awesome IA no trabalho](https://go.mymarketing.click/nfe-lista-ia-no-trabalho) - IA no trabalho, por profissão: assistentes, privacidade, normas e fontes oficiais para conferir o que a IA escreveu.
- [Awesome IA na advocacia](https://go.mymarketing.click/nfe-lista-ia-advocacia) - IA para advogados: assistentes, privacidade, normas sobre IA na advocacia e no Judiciário, e as fontes oficiais para conferir.
- [Awesome IA na contabilidade](https://go.mymarketing.click/nfe-lista-ia-contabilidade) - IA para contadores: assistentes, privacidade, normas do CFC e as fontes da Receita, do eSocial e do Simples para conferir.
- [Awesome IA na sala de aula](https://go.mymarketing.click/nfe-lista-ia-sala-de-aula) - IA para professores: assistentes, idade mínima e privacidade de cada um, e as normas da educação para conferir.
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/nfe-lista-ia-atendimento-e-vendas) - IA para quem atende e vende: assistentes, privacidade, direitos do consumidor e as regras do trabalho de quem está no balcão, no caixa e no telefone.
- [Awesome IA no escritório](https://go.mymarketing.click/nfe-lista-ia-escritorio) - IA para secretárias, assistentes e auxiliares administrativos: assistentes, privacidade, redação oficial e golpes que chegam por e-mail.
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/nfe-lista-ia-pequeno-negocio) - IA para o MEI e o pequeno empresário: assistentes, privacidade, as regras do MEI e do Simples, do consumidor e da LGPD para quem é pequeno.
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/nfe-lista-ia-primeiro-trabalho) - IA para quem está começando a trabalhar: assistentes, privacidade, onde procurar vaga, os direitos do primeiro emprego e os golpes da vaga falsa.
- [Awesome Pix](https://go.mymarketing.click/nfe-lista-pix) - Pix para quem integra: normas, APIs, SDKs, provedores e ferramentas, conferidos um a um.
- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - Servidores MCP para serviços brasileiros: dados públicos, CNPJ, fiscal, jurídico, mercado financeiro, comércio e pagamentos.
- [Awesome livros de IA](https://go.mymarketing.click/nfe-lista-livros-ia) - Livros sobre inteligência artificial em português: do primeiro uso à profissão, de quem constrói ao debate.
- [Awesome ferramentas online](https://go.mymarketing.click/nfe-lista-ferramentas-online) - Ferramentas grátis que abrem no navegador, sem instalar: imagem, PDF, texto, código, sites, e-mail, vídeo e vendas.
- [Awesome APIs Brasil](https://go.mymarketing.click/nfe-lista-apis-brasil) - APIs públicas brasileiras: CEP, CNPJ, Banco Central, IBGE, Legislativo, Judiciário, feriados e dados abertos.
- [Awesome Claude Code BR](https://go.mymarketing.click/nfe-lista-claude-code-br) - Claude Code em português: documentação, cursos, skills, regras, plugins e servidores MCP feitos no Brasil.
- [Awesome pagamentos Brasil](https://go.mymarketing.click/nfe-lista-pagamentos-brasil) - Pagamentos no Brasil para quem integra: normas, gateways, adquirentes, boleto, assinatura, split e antifraude.
- [Awesome Open Finance Brasil](https://go.mymarketing.click/nfe-lista-open-finance-brasil) - Open Finance e Open Insurance no Brasil: normas, especificações, dados abertos, agregadores e código aberto.
- [Awesome WhatsApp API](https://go.mymarketing.click/nfe-lista-whatsapp-api) - WhatsApp para quem integra: a API oficial da Meta, os provedores, as bibliotecas não oficiais e o risco de cada caminho.
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/nfe-lista-empresa-de-uma-pessoa) - O que uma pessoa usa para tocar um negócio inteiro com agentes de IA: pôr no ar, cobrar, medir, divulgar e ser encontrada.

## Feito por Ciro Cesar Maciel

Usar o que eu faço também é um jeito de apoiar estas listas.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-agents)

## Licença

Esta lista está sob CC0 1.0: copie, adapte e redistribua como quiser, sem pedir permissão. O código do gerador está no awesome-kit, sob MIT.

<sub>Atualizada em 2026-11-10.</sub>
