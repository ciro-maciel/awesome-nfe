# Awesome NF-e

> 브라질 전자 세금계산서(NF-e)를 연동하는 사람을 위한 자료: 공식 포털, 언어별 라이브러리, 발행 API, MCP 서버.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%EA%B5%AC%EB%8F%85-111111?style=flat-square)](https://go.mymarketing.click/nfe-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/nfe-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/ko.xml) ![35 항목](https://img.shields.io/badge/%ED%95%AD%EB%AA%A9-35-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-6b6b6b?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

시스템 안에서 전자 세금계산서(nota fiscal)를 발행, 수신 또는 확인해야 하는 사람을 위한 목록입니다. 매뉴얼과 스키마가 있는 공식 포털에서 시작해, 각 언어의 오픈소스 라이브러리를 거쳐, 대신 발행해 주는 API로 끝납니다. 모든 주소는 등록 전에 직접 열어 확인했습니다.

## 콘텐츠

- [공식 포털](#공식-포털)
- [PHP 라이브러리](#php-라이브러리)
- [Java 라이브러리](#java-라이브러리)
- [.NET 라이브러리](#net-라이브러리)
- [Python 라이브러리](#python-라이브러리)
- [JavaScript 및 TypeScript 라이브러리](#javascript-및-typescript-라이브러리)
- [Delphi 및 Lazarus](#delphi-및-lazarus)
- [발행 API](#발행-api)
- [MCP 서버](#mcp-서버)
- [다른 목록](#다른-목록)
- [태그](#태그)
- [기여 방법](#기여-방법)
- [다른 목록](#다른-목록)
- [Ciro Cesar Maciel 제작](#ciro-cesar-maciel-제작)
- [라이선스](#라이선스)

## 공식 포털

각 문서의 매뉴얼, 스키마, 기술 노트가 있는 곳.

- [Portal Nacional da NF-e](https://go.mymarketing.click/nfe-portal-nacional-da-nf-e) - 지침 매뉴얼, XML 스키마, 기술 노트, NF-e 조회. `공식` `무료`
- [NFS-e Nacional](https://go.mymarketing.click/nfe-nfs-e-nacional) - 공공 발급기관과 데이터 환경을 갖춘 전국 서비스 세금계산서(NFS-e) 표준. `공식` `무료`
- [NFS-e Nacional: documentação técnica](https://go.mymarketing.click/nfe-nfs-e-nacional-documentacao-tecnica) - 통합 개발자를 위한 NFS-e 국가 표준의 매뉴얼, 레이아웃, API. `공식` `무료` `API`
- [Portal da NFC-e](https://go.mymarketing.click/nfe-portal-da-nfc-e) - SVRS 포털의 소비자 영수증(NFC-e) 문서. 여러 주에서 사용. `공식` `무료`
- [Portal Nacional do CT-e](https://go.mymarketing.click/nfe-portal-nacional-do-ct-e) - 전자 운송 증서(CT-e)의 매뉴얼과 스키마. `공식` `무료`
- [Portal do MDF-e](https://go.mymarketing.click/nfe-portal-do-mdf-e) - 전자 세무 문서 매니페스트(MDF-e) 문서. `공식` `무료`
- [Portal do SPED](https://go.mymarketing.click/nfe-portal-do-sped) - 연방 세무청의 공공 전자 기장 시스템: EFD, ECD, ECF 및 검증 프로그램. `공식` `무료`

## PHP 라이브러리

오픈 소스이며 2026년에도 저장소 활동이 있음.

- [sped-nfe](https://go.mymarketing.click/nfe-sped-nfe) - NF-e 및 NFC-e를 생성, 서명, SEFAZ로 전송하는 데 가장 많이 쓰는 라이브러리. `오픈소스`
- [sped-common](https://go.mymarketing.click/nfe-sped-common) - NF-e, CT-e, MDF-e용 NFePHP 공통 클래스: 인증서, 서명, 통신. `오픈소스`
- [nfse-php](https://go.mymarketing.click/nfe-nfse-php) - NFS-e 국가 표준용 PHP SDK. `오픈소스` `SDK`
- [php-nfse](https://go.mymarketing.click/nfe-php-nfse) - 시청과 연동하여 NFS-e를 생성하고 통신. `오픈소스`
- [Cliente PHP da NFE.io](https://go.mymarketing.click/nfe-cliente-php-da-nfe-io) - NFE.io PHP SDK로 NFS-e 발행, 의존성 없음. `오픈소스` `SDK`

## Java 라이브러리

오픈 소스이며 2026년에도 저장소 활동이 있음.

- [Java_NFe](https://go.mymarketing.click/nfe-java-nfe) - Java로 NF-e 및 NFC-e 조회, 전송, 취소, 이벤트 처리. `오픈소스`
- [wmixvideo/nfe](https://go.mymarketing.click/nfe-wmixvideo-nfe) - Java용 전자 세금계산서, 전체 데이터 모델 포함. `오픈소스`

## .NET 라이브러리

오픈 소스이며 2026년에도 저장소 활동이 있음.

- [DFe.NET](https://go.mymarketing.click/nfe-dfe-net) - C#으로 NF-e, NFC-e 생성 및 SEFAZ 서비스 호출. `오픈소스`
- [ZeusFiscal](https://go.mymarketing.click/nfe-zeusfiscal) - C#으로 NF-e, NFC-e, MDF-e, CT-e 발행 및 인쇄. `오픈소스`
- [Unimake DFe](https://go.mymarketing.click/nfe-unimake-dfe) - ERP를 전자 세무 문서와 연동하기 위한 DLL. `오픈소스`
- [OpenAC.Net.NFSe](https://go.mymarketing.click/nfe-openac-net-nfse) - 여러 시 표준에 맞춘 NFS-e 발행 및 전송. `오픈소스`
- [OpenAC.Net.NFSe.Nacional](https://go.mymarketing.click/nfe-openac-net-nfse-nacional) - C#으로 NFS-e 국가 표준 발행. `오픈소스`

## Python 라이브러리

오픈 소스이며 2026년에도 저장소 활동이 있음.

- [PyNFe](https://go.mymarketing.click/nfe-pynfe) - Python으로 NF-e 및 NFC-e 웹서비스 연동. `오픈소스`
- [nfelib](https://go.mymarketing.click/nfe-nfelib) - NF-e, NFS-e 국가 표준, CT-e, MDF-e, BP-e의 XML을 읽고 생성하는 Python 바인딩. `오픈소스`
- [Localização brasileira do Odoo](https://go.mymarketing.click/nfe-localizacao-brasileira-do-odoo) - NF-e를 포함한 Odoo의 브라질 세무 모듈. `오픈소스`

## JavaScript 및 TypeScript 라이브러리

오픈 소스이며 2026년에도 저장소 활동이 있음.

- [NFeWizard](https://go.mymarketing.click/nfe-nfewizard) - SEFAZ 서비스용 Node.js 라이브러리: 발행, 조회, 이벤트, DANFE. `오픈소스`
- [node-sped-nfe](https://go.mymarketing.click/nfe-node-sped-nfe) - Node.js로 SEFAZ와 NF-e 발행 및 통신. `오픈소스`
- [Cliente Node.js da NFE.io](https://go.mymarketing.click/nfe-cliente-node-js-da-nfe-io) - NFE.io TypeScript SDK로 NFS-e 발행, 의존성 없음. `오픈소스` `SDK`

## Delphi 및 Lazarus

Delphi 및 Lazarus용 상업 자동화 컴포넌트.

- [Projeto ACBr](https://go.mymarketing.click/nfe-projeto-acbr) - Delphi 및 Lazarus용 상업 자동화 컴포넌트, NF-e, NFC-e, NFS-e, CT-e, SPED 지원. `오픈소스`
- [ACBr no GitHub](https://go.mymarketing.click/nfe-acbr-no-github) - ACBr 프로젝트 SVN 저장소의 미러. `오픈소스`

## 발행 API

자동으로 발행해 주는 서비스. 알파벳 순서.

- [eNotas](https://go.mymarketing.click/nfe-enotas) - 온라인으로 판매하는 사람을 위한 NFS-e 및 NF-e 자동 발행. `유료` `API`
- [Focus NFe](https://go.mymarketing.click/nfe-focus-nfe) - NF-e, NFC-e, NFS-e, CT-e 및 MDF-e용 API. `유료` `API`
- [NFE.io](https://go.mymarketing.click/nfe-nfe-io) - NFS-e 및 NF-e 발행과 세무 데이터 조회를 위한 API. `유료` `API`
- [PlugNotas](https://go.mymarketing.click/nfe-plugnotas) - Tecnospeed의 API, 수천 개 지자체의 NF-e, NFC-e 및 NFS-e 지원. `유료` `API`
- [Qive](https://go.mymarketing.click/nfe-qive) - 받은 전자세금계산서(노타 피스칼)를 수집하고 관리합니다. 이전 이름은 Arquivei. `유료` `API`
- [Webmania](https://go.mymarketing.click/nfe-webmania) - NF-e, NFC-e, NFS-e용 REST API. `유료` `API`

## MCP 서버

AI 에이전트가 세무 문서를 조회하고 확인하도록 돕습니다.

- [mcp-fiscal-brasil](https://go.mymarketing.click/nfe-mcp-fiscal-brasil) - 세무 MCP 서버: CNPJ, NF-e, NFS-e, CT-e, SPED, eSocial 및 Simples Nacional. `오픈소스`

## 다른 목록

오픈 소스이며 2026년에도 저장소 활동이 있음.

- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - 세무 서비스를 포함한 브라질 서비스용 MCP 서버. `무료`

## 태그

각 항목은 무엇인지 설명합니다. 옆의 태그가 고르는 데 도움을 줍니다. 표준을 정하는 곳에서 나온 것은 공식, 코드가 공개된 것은 오픈소스, 사용 방식에 따라 무료 또는 유료, 연동 방식에 따라 API와 SDK로 표시합니다. "작성자 제작" 태그가 붙은 항목은 Ciro Cesar Maciel이 만들었으며, 다른 모든 항목과 같은 기준을 따릅니다.

## 기여 방법

부족한 것, 바뀐 것, 사라진 것을 알고 계신가요? 새 항목 양식으로 이슈를 열거나 data/list.json을 수정하는 풀 리퀘스트를 보내 주세요. 각 언어의 README는 이 파일에서 자동으로 생성됩니다.

[CONTRIBUTING.md](CONTRIBUTING.md)

## 다른 목록

같은 형식으로 큐레이션한 목록으로, 포르투갈어와 다른 14개 언어로 제공됩니다.

- [Awesome IA no trabalho](https://go.mymarketing.click/nfe-lista-ia-no-trabalho) - 직업별 업무 AI: 어시스턴트, 개인정보 보호, 규정, 그리고 AI가 작성한 내용을 확인할 공식 자료.
- [Awesome IA na advocacia](https://go.mymarketing.click/nfe-lista-ia-advocacia) - 변호사를 위한 AI: 어시스턴트, 개인정보 보호, 변호 업무와 사법부의 AI 규정, 그리고 확인할 공식 자료.
- [Awesome IA na contabilidade](https://go.mymarketing.click/nfe-lista-ia-contabilidade) - 회계사를 위한 AI: 어시스턴트, 개인정보 보호, CFC 규정, 그리고 Receita, eSocial, Simples의 자료로 확인할 수 있는 내용.
- [Awesome IA na sala de aula](https://go.mymarketing.click/nfe-lista-ia-sala-de-aula) - 교사를 위한 AI: 어시스턴트별 최소 연령과 개인정보 보호, 그리고 확인할 교육 관련 규정.
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/nfe-lista-ia-atendimento-e-vendas) - 고객 응대와 판매를 하는 사람을 위한 AI: 어시스턴트, 개인정보 보호, 소비자 권리, 그리고 창구, 계산대, 전화 업무를 하는 사람의 노동 규정.
- [Awesome IA no escritório](https://go.mymarketing.click/nfe-lista-ia-escritorio) - 비서, 어시스턴트, 행정 보조를 위한 AI: 어시스턴트, 개인정보 보호, 공문서 작성, 이메일로 오는 사기.
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/nfe-lista-ia-pequeno-negocio) - MEI와 소규모 사업자를 위한 AI: 어시스턴트, 개인정보 보호, MEI와 Simples 규정, 소비자 보호법, 그리고 소규모 사업자를 위한 LGPD.
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/nfe-lista-ia-primeiro-trabalho) - 일을 막 시작한 사람을 위한 AI: 어시스턴트, 개인정보 보호, 채용 정보를 찾는 곳, 첫 직장의 권리, 가짜 채용 사기.
- [Awesome Pix](https://go.mymarketing.click/nfe-lista-pix) - Pix를 연동하는 사람을 위한 자료: 규정, API, SDK, 제공업체, 도구를 하나씩 확인했습니다.
- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - 브라질 공공 서비스를 위한 MCP 서버: 공공 데이터, CNPJ, 세무, 법률, 금융 시장, 상거래, 결제.
- [Awesome livros de IA](https://go.mymarketing.click/nfe-lista-livros-ia) - 인공지능에 관한 포르투갈어 도서: 첫 사용부터 직업, 만드는 사람과 토론까지.
- [Awesome ferramentas online](https://go.mymarketing.click/nfe-lista-ferramentas-online) - 설치 없이 브라우저에서 바로 여는 무료 도구: 이미지, PDF, 텍스트, 코드, 사이트, 이메일, 동영상, 판매.
- [Awesome APIs Brasil](https://go.mymarketing.click/nfe-lista-apis-brasil) - 브라질 공개 API: CEP, CNPJ, 중앙은행, IBGE, 입법부, 사법부, 공휴일, 공개 데이터.
- [Awesome Claude Code BR](https://go.mymarketing.click/nfe-lista-claude-code-br) - 포르투갈어 Claude Code: 브라질에서 만든 문서, 강좌, skills, 규칙, 플러그인, MCP 서버.
- [Awesome pagamentos Brasil](https://go.mymarketing.click/nfe-lista-pagamentos-brasil) - 브라질 결제를 연동하는 사람을 위한 자료: 규정, 게이트웨이, 매입사, boleto, 구독, split, 사기 방지.
- [Awesome Open Finance Brasil](https://go.mymarketing.click/nfe-lista-open-finance-brasil) - Open Finance 및 Open Insurance (브라질): 규정, 명세, 공개 데이터, 집계 서비스, 오픈 소스 코드.
- [Awesome WhatsApp API](https://go.mymarketing.click/nfe-lista-whatsapp-api) - WhatsApp 통합 개발자용: Meta 공식 API, 제공업체, 비공식 라이브러리, 각 방식의 위험.
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/nfe-lista-empresa-de-uma-pessoa) - AI 에이전트로 사업 전체를 운영하는 데 필요한 것: 서비스 출시, 결제, 측정, 홍보, 고객 발견.

## Ciro Cesar Maciel 제작

제가 만든 것을 사용해 주시는 것도 이 목록을 지원하는 방법입니다.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-agents)

## 라이선스

이 목록은 CC0 1.0 라이선스를 따릅니다. 허가를 구하지 않고 복사, 수정, 재배포해도 됩니다. 생성기 코드는 MIT 라이선스로 awesome-kit에 있습니다.

<sub>업데이트 날짜 2026-11-10.</sub>
