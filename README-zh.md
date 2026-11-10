# Awesome NF-e

> 面向集成开发者的电子发票指南：官方门户、各语言的开源库、开票 API 和 MCP 服务器。

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%E8%AE%A2%E9%98%85-111111?style=flat-square)](https://go.mymarketing.click/nfe-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/nfe-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/zh.xml) ![35 项](https://img.shields.io/badge/%E9%A1%B9-35-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-6b6b6b?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

供需要在系统内开具、接收或核验发票的人使用。先从能查到手册和 schema 的官方门户开始，再到各语言的开源库，最后是替你开票的 API。每个地址在收录前都已打开确认。

## 内容

- [官方门户](#官方门户)
- [PHP 库](#php-库)
- [Java 库](#java-库)
- [.NET 库](#net-库)
- [Python 库](#python-库)
- [JavaScript 和 TypeScript 库](#javascript-和-typescript-库)
- [Delphi 和 Lazarus](#delphi-和-lazarus)
- [发票开具 API](#发票开具-api)
- [MCP 服务器](#mcp-服务器)
- [其他列表](#其他列表)
- [标签](#标签)
- [如何贡献](#如何贡献)
- [其他列表](#其他列表)
- [由 Ciro Cesar Maciel 制作](#由-ciro-cesar-maciel-制作)
- [许可证](#许可证)

## 官方门户

各类文件的手册、schema 和技术说明都在这里。

- [Portal Nacional da NF-e](https://go.mymarketing.click/nfe-portal-nacional-da-nf-e) - 指导手册、XML schema、技术说明，以及 NF-e 查询。 `官方` `免费`
- [NFS-e Nacional](https://go.mymarketing.click/nfe-nfs-e-nacional) - 全国统一的服务发票标准，包括公共开票方和数据环境。 `官方` `免费`
- [NFS-e Nacional: documentação técnica](https://go.mymarketing.click/nfe-nfs-e-nacional-documentacao-tecnica) - NFS-e 国家版的手册、布局和 API，供集成者使用。 `官方` `免费` `API`
- [Portal da NFC-e](https://go.mymarketing.click/nfe-portal-da-nfc-e) - SVRS 门户上的消费者发票文档，多个州都在使用。 `官方` `免费`
- [Portal Nacional do CT-e](https://go.mymarketing.click/nfe-portal-nacional-do-ct-e) - 电子运输凭证的手册和 schema。 `官方` `免费`
- [Portal do MDF-e](https://go.mymarketing.click/nfe-portal-do-mdf-e) - 电子税务文件清单的文档。 `官方` `免费`
- [Portal do SPED](https://go.mymarketing.click/nfe-portal-do-sped) - 联邦税务局的公共电子簿记系统：EFD、ECD、ECF 及验证程序。 `官方` `免费`

## PHP 库

开源，代码仓库在 2026 年仍有更新。

- [sped-nfe](https://go.mymarketing.click/nfe-sped-nfe) - 用于生成、签名并向 SEFAZ 传输 NF-e 和 NFC-e 的最常用库。 `开源`
- [sped-common](https://go.mymarketing.click/nfe-sped-common) - NFePHP 的通用类，用于 NF-e、CT-e 和 MDF-e：证书、签名和通信。 `开源`
- [nfse-php](https://go.mymarketing.click/nfe-nfse-php) - NFS-e 国家版的 PHP SDK。 `开源` `SDK`
- [php-nfse](https://go.mymarketing.click/nfe-php-nfse) - 与市政府通信并生成 NFS-e。 `开源`
- [Cliente PHP da NFE.io](https://go.mymarketing.click/nfe-cliente-php-da-nfe-io) - NFE.io 的 PHP SDK，用于开具 NFS-e，无依赖。 `开源` `SDK`

## Java 库

开源，代码仓库在 2026 年仍有更新。

- [Java_NFe](https://go.mymarketing.click/nfe-java-nfe) - Java 版 NF-e 和 NFC-e，支持查询、发送、作废和事件。 `开源`
- [wmixvideo/nfe](https://go.mymarketing.click/nfe-wmixvideo-nfe) - Java 电子发票，包含完整数据模型。 `开源`

## .NET 库

开源，代码仓库在 2026 年仍有更新。

- [DFe.NET](https://go.mymarketing.click/nfe-dfe-net) - 用 C# 生成 NF-e 和 NFC-e，并调用 SEFAZ 服务。 `开源`
- [ZeusFiscal](https://go.mymarketing.click/nfe-zeusfiscal) - 用 C# 开具和打印 NF-e、NFC-e、MDF-e 和 CT-e。 `开源`
- [Unimake DFe](https://go.mymarketing.click/nfe-unimake-dfe) - 用于将 ERP 与电子税务文件集成的 DLL。 `开源`
- [OpenAC.Net.NFSe](https://go.mymarketing.click/nfe-openac-net-nfse) - 支持多种市政标准的 NFS-e 开具和传输。 `开源`
- [OpenAC.Net.NFSe.Nacional](https://go.mymarketing.click/nfe-openac-net-nfse-nacional) - 用 C# 开具国家标准的 NFS-e。 `开源`

## Python 库

开源，代码仓库在 2026 年仍有更新。

- [PyNFe](https://go.mymarketing.click/nfe-pynfe) - 用 Python 对接 NF-e 和 NFC-e 的 webservice。 `开源`
- [nfelib](https://go.mymarketing.click/nfe-nfelib) - 用于读取和生成 NF-e、NFS-e 国家版、CT-e、MDF-e 和 BP-e 的 XML 的 Python 绑定。 `开源`
- [Localização brasileira do Odoo](https://go.mymarketing.click/nfe-localizacao-brasileira-do-odoo) - Odoo 的巴西税务模块，包括 NF-e。 `开源`

## JavaScript 和 TypeScript 库

开源，代码仓库在 2026 年仍有更新。

- [NFeWizard](https://go.mymarketing.click/nfe-nfewizard) - 用于 SEFAZ 服务的 Node.js 库：开具、查询、事件和 DANFE。 `开源`
- [node-sped-nfe](https://go.mymarketing.click/nfe-node-sped-nfe) - 用 Node.js 开具 NF-e 并与 SEFAZ 通信。 `开源`
- [Cliente Node.js da NFE.io](https://go.mymarketing.click/nfe-cliente-node-js-da-nfe-io) - NFE.io 的 TypeScript SDK，用于开具 NFS-e，无依赖。 `开源` `SDK`

## Delphi 和 Lazarus

Delphi 和 Lazarus 的商业自动化组件。

- [Projeto ACBr](https://go.mymarketing.click/nfe-projeto-acbr) - 适用于 Delphi 和 Lazarus 的商业自动化组件，支持 NF-e、NFC-e、NFS-e、CT-e 和 SPED。 `开源`
- [ACBr no GitHub](https://go.mymarketing.click/nfe-acbr-no-github) - ACBr 项目 SVN 仓库的镜像。 `开源`

## 发票开具 API

按字母顺序排列的代开发票服务。

- [eNotas](https://go.mymarketing.click/nfe-enotas) - 为网上卖家自动开具 NFS-e 和 NF-e。 `付费` `API`
- [Focus NFe](https://go.mymarketing.click/nfe-focus-nfe) - 用于 NF-e、NFC-e、NFS-e、CT-e 和 MDF-e 的 API。 `付费` `API`
- [NFE.io](https://go.mymarketing.click/nfe-nfe-io) - 用于开具 NFS-e 和 NF-e 并查询税务数据的 API。 `付费` `API`
- [PlugNotas](https://go.mymarketing.click/nfe-plugnotas) - Tecnospeed 的 API，支持数千个市的 NF-e、NFC-e 和 NFS-e。 `付费` `API`
- [Qive](https://go.mymarketing.click/nfe-qive) - 收取并管理收到的发票，原名 Arquivei。 `付费` `API`
- [Webmania](https://go.mymarketing.click/nfe-webmania) - 用于 NF-e、NFC-e 和 NFS-e 的 REST API。 `付费` `API`

## MCP 服务器

供 AI 代理查询和核对税务文件。

- [mcp-fiscal-brasil](https://go.mymarketing.click/nfe-mcp-fiscal-brasil) - 税务 MCP 服务器：CNPJ、NF-e、NFS-e、CT-e、SPED、eSocial 和 Simples Nacional。 `开源`

## 其他列表

开源，代码仓库在 2026 年仍有更新。

- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - 面向巴西服务的 MCP 服务器，包括税务类。 `免费`

## 标签

每项都说明了它是什么。旁边的标签有助于选择：官方表示来自制定标准的一方，开源表示代码已公开，免费或付费按使用模式区分，API 和 SDK 表示集成方式。带有“作者自制”标签的条目由 Ciro Cesar Maciel 制作，并遵循与其他条目相同的规则。

## 如何贡献

发现缺少的内容、有变动或已失效的条目？请使用新增表单提交 issue，或通过编辑 data/list.json 提交 pull request。每种语言的 README 都由该文件生成。

[CONTRIBUTING.md](CONTRIBUTING.md)

## 其他列表

同一格式的精选列表，有葡萄牙语版本以及另外 14 种语言的版本。

- [Awesome IA no trabalho](https://go.mymarketing.click/nfe-lista-ia-no-trabalho) - 按职业划分的工作中 AI：助手、隐私、规范，以及用于核查 AI 写作内容的官方来源。
- [Awesome IA na advocacia](https://go.mymarketing.click/nfe-lista-ia-advocacia) - 律师的 AI：助手、隐私、律师业和司法系统中有关 AI 的规范，以及用于核查的官方来源。
- [Awesome IA na contabilidade](https://go.mymarketing.click/nfe-lista-ia-contabilidade) - 会计的 AI：助手、隐私、CFC 规范，以及用于核查的税务局、eSocial 和 Simples 来源。
- [Awesome IA na sala de aula](https://go.mymarketing.click/nfe-lista-ia-sala-de-aula) - 教师的 AI：助手、各工具的最低使用年龄和隐私政策，以及用于核查的教育规范。
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/nfe-lista-ia-atendimento-e-vendas) - 面向服务和销售人员的 AI：助手、隐私、消费者权益，以及柜台、收银和电话岗位的工作规则。
- [Awesome IA no escritório](https://go.mymarketing.click/nfe-lista-ia-escritorio) - 秘书、助理和行政人员的 AI：助手、隐私、公文写作规范，以及通过电子邮件传来的诈骗。
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/nfe-lista-ia-pequeno-negocio) - MEI 和小企业主的 AI：助手、隐私、MEI 和 Simples 规则、消费者规则，以及适用于小企业的 LGPD。
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/nfe-lista-ia-primeiro-trabalho) - 刚开始工作的人的 AI：助手、隐私、求职渠道、初入职场的权益，以及虚假招聘诈骗。
- [Awesome Pix](https://go.mymarketing.click/nfe-lista-pix) - 面向集成开发者的 Pix：规范、API、SDK、服务提供商和工具，逐一核实。
- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - 面向巴西公共服务的 MCP 服务器：公共数据、CNPJ、税务、法律、金融市场、商务和支付。
- [Awesome livros de IA](https://go.mymarketing.click/nfe-lista-livros-ia) - 葡萄牙语的人工智能书籍：从入门使用到职业，从构建者到讨论。
- [Awesome ferramentas online](https://go.mymarketing.click/nfe-lista-ferramentas-online) - 无需安装、在浏览器中打开的免费工具：图片、PDF、文本、代码、网站、电子邮件、视频和销售。
- [Awesome APIs Brasil](https://go.mymarketing.click/nfe-lista-apis-brasil) - 巴西公共 API：CEP、CNPJ、中央银行、IBGE、立法、司法、节假日和开放数据。
- [Awesome Claude Code BR](https://go.mymarketing.click/nfe-lista-claude-code-br) - 葡萄牙语版 Claude Code：文档、课程、skills、规则、插件，以及在巴西开发的 MCP 服务器。
- [Awesome pagamentos Brasil](https://go.mymarketing.click/nfe-lista-pagamentos-brasil) - 面向集成开发者的巴西支付：规范、网关、收单机构、boleto、订阅、split 和反欺诈。
- [Awesome Open Finance Brasil](https://go.mymarketing.click/nfe-lista-open-finance-brasil) - 巴西 Open Finance 和 Open Insurance：规范、技术说明、开放数据、聚合器和开源代码。
- [Awesome WhatsApp API](https://go.mymarketing.click/nfe-lista-whatsapp-api) - WhatsApp 集成指南：Meta 官方 API、服务提供商、非官方库，以及每种方式的风险。
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/nfe-lista-empresa-de-uma-pessoa) - 用 AI 代理经营整个业务的工具：上线、收款、衡量、推广和获客。

## 由 Ciro Cesar Maciel 制作

使用我的作品，也是支持这些列表的一种方式。

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-agents)

## 许可证

本列表采用 CC0 1.0 协议：可以随意复制、改编和再分发，无需征得许可。生成器代码位于 awesome-kit 中，采用 MIT 协议。

<sub>更新于 2026-11-10.</sub>
