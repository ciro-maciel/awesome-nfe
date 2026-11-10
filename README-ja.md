# Awesome NF-e

> 電子インボイス（NF-e）を組み込む人向け：公式ポータル、言語別ライブラリ、発行API、MCPサーバー。

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%E7%BD%B2%E5%90%8D%E3%81%99%E3%82%8B-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgN2EyIDIgMCAwIDEgMiAtMmgxNGEyIDIgMCAwIDEgMiAydjEwYTIgMiAwIDAgMSAtMiAyaC0xNGEyIDIgMCAwIDEgLTIgLTJ2LTEwIiAvPiA8cGF0aCBkPSJNMyA3bDkgNmw5IC02IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/nfe-cartas) [![応援する](https://img.shields.io/badge/%E5%BF%9C%E6%8F%B4%E3%81%99%E3%82%8B-%E3%82%B3%E3%83%BC%E3%83%92%E3%83%BC1%E6%9D%AF%E3%81%AE%E6%94%AF%E6%8F%B4-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/nfe-apoie) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square&logo=youtube&logoColor=FF0000)](https://go.mymarketing.click/nfe-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square&logo=instagram&logoColor=E4405F)](https://go.mymarketing.click/nfe-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/nfe-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square&logo=rss&logoColor=FFA500)](feed/ja.xml) ![35 項目](https://img.shields.io/badge/%E9%A0%85%E7%9B%AE-35-555555?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMuNSA1LjVsMS41IDEuNWwyLjUgLTIuNSIgLz4gPHBhdGggZD0iTTMuNSAxMS41bDEuNSAxLjVsMi41IC0yLjUiIC8%2BIDxwYXRoIGQ9Ik0zLjUgMTcuNWwxLjUgMS41bDIuNSAtMi41IiAvPiA8cGF0aCBkPSJNMTEgNmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxMmw5IDAiIC8%2BIDxwYXRoIGQ9Ik0xMSAxOGw5IDAiIC8%2BIDwvc3ZnPg%3D%3D)

[![Português](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/pt.svg)](README.md) [![English](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/en.svg)](README-en.md) [![Español](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/es.svg)](README-es.md) [![Français](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/fr.svg)](README-fr.md) [![Deutsch](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/de.svg)](README-de.md) [![Italiano](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/it.svg)](README-it.md) [![Русский](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ru.svg)](README-ru.md) [![中文](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/zh.svg)](README-zh.md) [![日本語](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ja-on.svg)](README-ja.md) [![한국어](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ko.svg)](README-ko.md) [![हिन्दी](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/hi.svg)](README-hi.md) [![العربية](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/ar.svg)](README-ar.md) [![Bahasa Indonesia](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/id.svg)](README-id.md) [![Türkçe](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/tr.svg)](README-tr.md) [![Tiếng Việt](https://raw.githubusercontent.com/ciro-maciel/awesome-kit/main/badges/vi.svg)](README-vi.md)

社内システムで電子インボイスを発行・受領・確認する人向けです。まず仕様書とスキーマが載っている公式ポータルを挙げ、次に各言語のオープンなライブラリ、最後に代わりに発行するAPIへと進みます。どのURLも掲載前に実際に開いて確認しました。

## 目次

- [公式ポータル](#公式ポータル)
- [PHP ライブラリ](#php-ライブラリ)
- [Java ライブラリ](#java-ライブラリ)
- [NET ライブラリ](#net-ライブラリ)
- [Python ライブラリ](#python-ライブラリ)
- [JavaScript と TypeScript のライブラリ](#javascript-と-typescript-のライブラリ)
- [Delphi と Lazarus](#delphi-と-lazarus)
- [発行API](#発行api)
- [MCPサーバー](#mcpサーバー)
- [他のリスト](#他のリスト)
- [タグ](#タグ)
- [貢献方法](#貢献方法)
- [他のリスト](#他のリスト)
- [Ciro Cesar Macielが作成](#ciro-cesar-macielが作成)
- [ライセンス](#ライセンス)

## 公式ポータル

マニュアル、スキーマ、各文書の技術ノートがある場所。

- [Portal Nacional da NF-e](https://go.mymarketing.click/nfe-portal-nacional-da-nf-e) - ガイドライン、XML スキーマ、技術ノート、NF-e の照会。 `公式` `無料`
- [NFS-e Nacional](https://go.mymarketing.click/nfe-nfs-e-nacional) - NFS-e（サービス請求書）の全国標準。公的な発行機関とデータ環境を備える。 `公式` `無料`
- [NFS-e Nacional: documentação técnica](https://go.mymarketing.click/nfe-nfs-e-nacional-documentacao-tecnica) - 連携開発者向けの NFS-e Nacional のマニュアル、レイアウト、API。 `公式` `無料` `API`
- [Portal da NFC-e](https://go.mymarketing.click/nfe-portal-da-nfc-e) - 複数の州で使われる、SVRS ポータルの NFC-e（消費者向け請求書）のドキュメント。 `公式` `無料`
- [Portal Nacional do CT-e](https://go.mymarketing.click/nfe-portal-nacional-do-ct-e) - 電子輸送文書（CT-e）のマニュアルとスキーマ。 `公式` `無料`
- [Portal do MDF-e](https://go.mymarketing.click/nfe-portal-do-mdf-e) - 電子税務文書マニフェスト（MDF-e）のドキュメント。 `公式` `無料`
- [Portal do SPED](https://go.mymarketing.click/nfe-portal-do-sped) - 連邦税務局のデジタル帳簿システム SPED：EFD、ECD、ECF と検証プログラム。 `公式` `無料`

## PHP ライブラリ

オープンソース。リポジトリは 2026 年にも活発。

- [sped-nfe](https://go.mymarketing.click/nfe-sped-nfe) - NF-e と NFC-e を生成、署名し、SEFAZ へ送信するための最も使われているライブラリ。 `オープンソース`
- [sped-common](https://go.mymarketing.click/nfe-sped-common) - NF-e、CT-e、MDF-e 向けの NFePHP 共通クラス：証明書、署名、通信。 `オープンソース`
- [nfse-php](https://go.mymarketing.click/nfe-nfse-php) - NFS-e Nacional 用の PHP SDK。 `オープンソース` `SDK`
- [php-nfse](https://go.mymarketing.click/nfe-php-nfse) - NFS-e の生成と通信を市町村と行うためのライブラリ。 `オープンソース`
- [Cliente PHP da NFE.io](https://go.mymarketing.click/nfe-cliente-php-da-nfe-io) - NFE.io の PHP SDK。依存関係なしで NFS-e を発行。 `オープンソース` `SDK`

## Java ライブラリ

オープンソース。リポジトリは 2026 年にも活発。

- [Java_NFe](https://go.mymarketing.click/nfe-java-nfe) - Java での NF-e と NFC-e。照会、送信、取消、イベントに対応。 `オープンソース`
- [wmixvideo/nfe](https://go.mymarketing.click/nfe-wmixvideo-nfe) - Java で扱う電子請求書。完全なデータモデル付き。 `オープンソース`

## NET ライブラリ

オープンソース。リポジトリは 2026 年にも活発。

- [DFe.NET](https://go.mymarketing.click/nfe-dfe-net) - C# で NF-e と NFC-e を生成し、SEFAZ のサービスを利用。 `オープンソース`
- [ZeusFiscal](https://go.mymarketing.click/nfe-zeusfiscal) - C# で NF-e、NFC-e、MDF-e、CT-e を発行・印刷。 `オープンソース`
- [Unimake DFe](https://go.mymarketing.click/nfe-unimake-dfe) - ERP を電子税務文書に接続するための DLL。 `オープンソース`
- [OpenAC.Net.NFSe](https://go.mymarketing.click/nfe-openac-net-nfse) - 複数の市町村標準に対応した NFS-e の発行と送信。 `オープンソース`
- [OpenAC.Net.NFSe.Nacional](https://go.mymarketing.click/nfe-openac-net-nfse-nacional) - C# で全国標準の NFS-e を発行。 `オープンソース`

## Python ライブラリ

オープンソース。リポジトリは 2026 年にも活発。

- [PyNFe](https://go.mymarketing.click/nfe-pynfe) - Python から NF-e と NFC-e の webservice を利用するインターフェース。 `オープンソース`
- [nfelib](https://go.mymarketing.click/nfe-nfelib) - Python で NF-e、NFS-e Nacional、CT-e、MDF-e、BP-e の XML を読み書きするバインディング。 `オープンソース`
- [Localização brasileira do Odoo](https://go.mymarketing.click/nfe-localizacao-brasileira-do-odoo) - Odoo のブラジル向け税務モジュール（NF-e を含む）。 `オープンソース`

## JavaScript と TypeScript のライブラリ

オープンソース。リポジトリは 2026 年にも活発。

- [NFeWizard](https://go.mymarketing.click/nfe-nfewizard) - Node.js で SEFAZ のサービスを扱うライブラリ：発行、照会、イベント、DANFE。 `オープンソース`
- [node-sped-nfe](https://go.mymarketing.click/nfe-node-sped-nfe) - Node.js で SEFAZ と NF-e の発行・通信を行う。 `オープンソース`
- [Cliente Node.js da NFE.io](https://go.mymarketing.click/nfe-cliente-node-js-da-nfe-io) - NFE.io の TypeScript SDK。依存関係なしで NFS-e を発行。 `オープンソース` `SDK`

## Delphi と Lazarus

Delphi と Lazarus 向けの商用自動化コンポーネント。

- [Projeto ACBr](https://go.mymarketing.click/nfe-projeto-acbr) - Delphi と Lazarus 向けの商用自動化コンポーネント。NF-e、NFC-e、NFS-e、CT-e、SPED に対応。 `オープンソース`
- [ACBr no GitHub](https://go.mymarketing.click/nfe-acbr-no-github) - ACBr プロジェクトの SVN リポジトリのミラー。 `オープンソース`

## 発行API

発行を代行するサービス。アルファベット順。

- [eNotas](https://go.mymarketing.click/nfe-enotas) - オンラインで販売する人向けに、NFS-eとNF-eを自動発行します。 `有料` `API`
- [Focus NFe](https://go.mymarketing.click/nfe-focus-nfe) - NF-e、NFC-e、NFS-e、CT-e、MDF-eのためのAPI。 `有料` `API`
- [NFE.io](https://go.mymarketing.click/nfe-nfe-io) - NFS-eとNF-eの発行、および税務データの照会のためのAPI。 `有料` `API`
- [PlugNotas](https://go.mymarketing.click/nfe-plugnotas) - Tecnospeedによる、数千の市区町村に対応したNF-e、NFC-e、NFS-eのAPI。 `有料` `API`
- [Qive](https://go.mymarketing.click/nfe-qive) - 受け取った請求書の取得と管理。以前の名称はArquivei。 `有料` `API`
- [Webmania](https://go.mymarketing.click/nfe-webmania) - NF-e、NFC-e、NFS-e向けのREST API。 `有料` `API`

## MCPサーバー

AIエージェントが税務書類を照会・確認するため。

- [mcp-fiscal-brasil](https://go.mymarketing.click/nfe-mcp-fiscal-brasil) - 税務用MCPサーバー：CNPJ、NF-e、NFS-e、CT-e、SPED、eSocial、Simples Nacional。 `オープンソース`

## 他のリスト

オープンソース。リポジトリは 2026 年にも活発。

- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - 税務を含むブラジルのサービス向けMCPサーバー。 `無料`

## タグ

各項目の説明のあとにタグを付けています。選ぶ際の目安にしてください。公式は標準を定める側が提供するもの、オープンソースはコードが公開されているもの、無料と有料は利用形態によるもの、APIとSDKは連携の方法を示します。「作者の作品」タグの項目はCiro Cesar Macielが作成したもので、ほかの項目と同じ基準で掲載しています。

## 貢献方法

不足しているもの、変更されたもの、利用できなくなったものはありますか？新規追加フォームでissueを開くか、data/list.jsonを編集してpull requestを送ってください。各言語のREADMEはこのファイルから生成されます。

[CONTRIBUTING.md](CONTRIBUTING.md)

## 他のリスト

同じ形式のキュレーションリストを、ポルトガル語と他14言語で公開しています。

- [Awesome IA no trabalho](https://go.mymarketing.click/nfe-lista-ia-no-trabalho) - 職業別のAI活用：アシスタント、プライバシー、規範、そしてAIが書いた内容を確認するための公式情報源。
- [Awesome IA na advocacia](https://go.mymarketing.click/nfe-lista-ia-advocacia) - 弁護士のためのAI：アシスタント、プライバシー、法律事務および司法におけるAIの規範、確認用の公式情報源。
- [Awesome IA na contabilidade](https://go.mymarketing.click/nfe-lista-ia-contabilidade) - 会計士のためのAI：アシスタント、プライバシー、CFCの規範、そして確認用の国税庁、eSocial、Simples Nacionalの情報源。
- [Awesome IA na sala de aula](https://go.mymarketing.click/nfe-lista-ia-sala-de-aula) - 教師のためのAI：各アシスタントの利用年齢とプライバシー、確認用の教育に関する規範。
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/nfe-lista-ia-atendimento-e-vendas) - 接客・販売に携わる人のためのAI：アシスタント、プライバシー、消費者の権利、窓口・レジ・電話対応をする人の労働規則。
- [Awesome IA no escritório](https://go.mymarketing.click/nfe-lista-ia-escritorio) - 秘書、アシスタント、事務補助のためのAI：アシスタント、プライバシー、公文書の書き方、メールで届く詐欺。
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/nfe-lista-ia-pequeno-negocio) - MEIと小規模事業主のためのAI：アシスタント、プライバシー、MEIとSimples Nacionalの規則、消費者保護、小規模事業者向けのLGPD。
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/nfe-lista-ia-primeiro-trabalho) - 働き始める人のためのAI：アシスタント、プライバシー、求人の探し方、初めての就職の権利、偽の求人詐欺。
- [Awesome Pix](https://go.mymarketing.click/nfe-lista-pix) - Pixを組み込む人向け：規範、API、SDK、プロバイダー、ツールを一つずつ確認した一覧。
- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - ブラジルの公共サービス向けMCPサーバー：公開データ、CNPJ、税務、法務、金融市場、商業、決済。
- [Awesome livros de IA](https://go.mymarketing.click/nfe-lista-livros-ia) - ポルトガル語で読める人工知能の本：最初の利用から職業、作る人から議論まで。
- [Awesome ferramentas online](https://go.mymarketing.click/nfe-lista-ferramentas-online) - インストール不要でブラウザで開ける無料ツール：画像、PDF、テキスト、コード、サイト、メール、動画、販売。
- [Awesome APIs Brasil](https://go.mymarketing.click/nfe-lista-apis-brasil) - ブラジルの公開API：CEP、CNPJ、中央銀行、IBGE、立法、司法、祝日、オープンデータ。
- [Awesome Claude Code BR](https://go.mymarketing.click/nfe-lista-claude-code-br) - ポルトガル語のClaude Code：ドキュメント、コース、skills、ルール、プラグイン、ブラジル製のMCPサーバー。
- [Awesome pagamentos Brasil](https://go.mymarketing.click/nfe-lista-pagamentos-brasil) - ブラジルの決済を組み込む人向け：規範、ゲートウェイ、アクワイアラー、ボレト、定期払い、スプリット、不正対策。
- [Awesome Open Finance Brasil](https://go.mymarketing.click/nfe-lista-open-finance-brasil) - Open Finance と Open Insurance（ブラジル）：規格、仕様、オープンデータ、アグリゲーター、オープンソース。
- [Awesome WhatsApp API](https://go.mymarketing.click/nfe-lista-whatsapp-api) - WhatsApp 連携向け：Meta の公式 API、プロバイダー、非公式ライブラリ、それぞれの方法のリスク。
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/nfe-lista-empresa-de-uma-pessoa) - AI エージェントだけで事業全体を回すためのツール：公開、請求、計測、宣伝、顧客対応まで。

## Ciro Cesar Macielが作成

このリストを支えるには、私の作品を使っていただくのもひとつの方法です。

このリストであなたの時間が節約できたなら、コーヒー1杯の支援がリストの維持を助けます。寄付額はご自身で選べ、PixまたはカードでOKです。 [![応援する](https://img.shields.io/badge/%E5%BF%9C%E6%8F%B4%E3%81%99%E3%82%8B-%E3%82%B3%E3%83%BC%E3%83%92%E3%83%BC1%E6%9D%AF%E3%81%AE%E6%94%AF%E6%8F%B4-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNEOTc3MDYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTRjLjgzIC42NDIgMi4wNzcgMS4wMTcgMy41IDFjMS40MjMgLjAxNyAyLjY3IC0uMzU4IDMuNSAtMWMuODMgLS42NDIgMi4wNzcgLTEuMDE3IDMuNSAtMWMxLjQyMyAtLjAxNyAyLjY3IC4zNTggMy41IDEiIC8%2BIDxwYXRoIGQ9Ik04IDNhMi40IDIuNCAwIDAgMCAtMSAyYTIuNCAyLjQgMCAwIDAgMSAyIiAvPiA8cGF0aCBkPSJNMTIgM2EyLjQgMi40IDAgMCAwIC0xIDJhMi40IDIuNCAwIDAgMCAxIDIiIC8%2BIDxwYXRoIGQ9Ik0zIDEwaDE0djVhNiA2IDAgMCAxIC02IDZoLTJhNiA2IDAgMCAxIC02IC02di01IiAvPiA8cGF0aCBkPSJNMTYuNzQ2IDE2LjcyNmEzIDMgMCAxIDAgLjI1MiAtNS41NTUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/nfe-apoie)

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiM2MEE1RkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE2IDE4YTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybTAgLTEyYTIgMiAwIDAgMSAyIDJhMiAyIDAgMCAxIDIgLTJhMiAyIDAgMCAxIC0yIC0yYTIgMiAwIDAgMSAtMiAybS03IDEyYTYgNiAwIDAgMSA2IC02YTYgNiAwIDAgMSAtNiAtNmE2IDYgMCAwIDEgLTYgNmE2IDYgMCAwIDEgNiA2IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/nfe-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTlhMiAyIDAgMCAxIC0yIC0yIiAvPiA8cGF0aCBkPSJNNSAxM3YtMiIgLz4gPHBhdGggZD0iTTUgN2EyIDIgMCAwIDEgMiAtMiIgLz4gPHBhdGggZD0iTTExIDVoMiIgLz4gPHBhdGggZD0iTTE3IDVhMiAyIDAgMCAxIDIgMiIgLz4gPHBhdGggZD0iTTE5IDExdjIiIC8%2BIDxwYXRoIGQ9Ik0xOSAxN3Y0IiAvPiA8cGF0aCBkPSJNMjEgMTloLTQiIC8%2BIDxwYXRoIGQ9Ik0xMyAxOWgtMiIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/nfe-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGODcxNzEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTkgNWEzIDMgMCAwIDEgMyAtM2EzIDMgMCAwIDEgMyAzdjVhMyAzIDAgMCAxIC0zIDNhMyAzIDAgMCAxIC0zIC0zbDAgLTUiIC8%2BIDxwYXRoIGQ9Ik01IDEwYTcgNyAwIDAgMCAxNCAwIiAvPiA8cGF0aCBkPSJNOCAyMWw4IDAiIC8%2BIDxwYXRoIGQ9Ik0xMiAxN2wwIDQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/nfe-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzNEQzOTkiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE1IDhhNSA1IDAgMCAxIDAgOCIgLz4gPHBhdGggZD0iTTE3LjcgNWE5IDkgMCAwIDEgMCAxNCIgLz4gPHBhdGggZD0iTTYgMTVoLTJhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDJsMy41IC00LjVhLjggLjggMCAwIDEgMS41IC41djE0YS44IC44IDAgMCAxIC0xLjUgLjVsLTMuNSAtNC41IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/nfe-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBNzhCRkEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTQgNWExIDEgMCAwIDEgMSAtMWg0YTEgMSAwIDAgMSAxIDF2NGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtNCIgLz4gPHBhdGggZD0iTTE0IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE1YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXY0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC00IiAvPiA8cGF0aCBkPSJNMTQgMTVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjRhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/nfe-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQkJGMjQiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDRhMyAzIDAgMCAxIDMgM3Y4YTMgMyAwIDAgMSAtMyAzaC01bC01IDN2LTNoLTJhMyAzIDAgMCAxIC0zIC0zdi04YTMgMyAwIDAgMSAzIC0zaDEyIiAvPiA8cGF0aCBkPSJNOS41IDloLjAxIiAvPiA8cGF0aCBkPSJNMTQuNSA5aC4wMSIgLz4gPHBhdGggZD0iTTkuNSAxM2EzLjUgMy41IDAgMCAwIDUgMCIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/nfe-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMyMkQzRUUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEyIDRsLTggNGw4IDRsOCAtNGwtOCAtNCIgLz4gPHBhdGggZD0iTTQgMTJsOCA0bDggLTQiIC8%2BIDxwYXRoIGQ9Ik00IDE2bDggNGw4IC00IiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/nfe-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjkyM0MiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgNWExIDEgMCAwIDEgMSAtMWgyYTEgMSAwIDAgMSAxIDF2MTRhMSAxIDAgMCAxIC0xIDFoLTJhMSAxIDAgMCAxIC0xIC0xbDAgLTE0IiAvPiA8cGF0aCBkPSJNOSA1YTEgMSAwIDAgMSAxIC0xaDJhMSAxIDAgMCAxIDEgMXYxNGExIDEgMCAwIDEgLTEgMWgtMmExIDEgMCAwIDEgLTEgLTFsMCAtMTQiIC8%2BIDxwYXRoIGQ9Ik01IDhoNCIgLz4gPHBhdGggZD0iTTkgMTZoNCIgLz4gPHBhdGggZD0iTTEzLjgwMyA0LjU2bDIuMTg0IC0uNTNjLjU2MiAtLjEzNSAxLjEzMyAuMTkgMS4yODIgLjczMmwzLjY5NSAxMy40MThhMS4wMiAxLjAyIDAgMCAxIC0uNjM0IDEuMjE5bC0uMTMzIC4wNDFsLTIuMTg0IC41M2MtLjU2MiAuMTM1IC0xLjEzMyAtLjE5IC0xLjI4MiAtLjczMmwtMy42OTUgLTEzLjQxOGExLjAyIDEuMDIgMCAwIDEgLjYzNCAtMS4yMTlsLjEzMyAtLjA0MSIgLz4gPHBhdGggZD0iTTE0IDlsNCAtMSIgLz4gPHBhdGggZD0iTTE2IDE2bDMuOTIzIC0uOTgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/nfe-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNBM0U2MzUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTcgMTBoM3YtM2wtMy41IC0zLjVhNiA2IDAgMCAxIDggOGw2IDZhMiAyIDAgMCAxIC0zIDNsLTYgLTZhNiA2IDAgMCAxIC04IC04bDMuNSAzLjUiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/nfe-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQUNDMTUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTEzIDNsMCA3bDYgMGwtOCAxMWwwIC03bC02IDBsOCAtMTEiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/nfe-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMzOEJERjgiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTMgMTNhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjZhMSAxIDAgMCAxIC0xIDFoLTRhMSAxIDAgMCAxIC0xIC0xbDAgLTYiIC8%2BIDxwYXRoIGQ9Ik0xNSA5YTEgMSAwIDAgMSAxIC0xaDRhMSAxIDAgMCAxIDEgMXYxMGExIDEgMCAwIDEgLTEgMWgtNGExIDEgMCAwIDEgLTEgLTFsMCAtMTAiIC8%2BIDxwYXRoIGQ9Ik05IDVhMSAxIDAgMCAxIDEgLTFoNGExIDEgMCAwIDEgMSAxdjE0YTEgMSAwIDAgMSAtMSAxaC00YTEgMSAwIDAgMSAtMSAtMWwwIC0xNCIgLz4gPHBhdGggZD0iTTQgMjBoMTQiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/nfe-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGNDcyQjYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTUgN2E0IDQgMCAxIDAgOCAwYTQgNCAwIDEgMCAtOCAwIiAvPiA8cGF0aCBkPSJNMyAyMXYtMmE0IDQgMCAwIDEgNCAtNGg0YTQgNCAwIDAgMSA0IDR2MiIgLz4gPHBhdGggZD0iTTE2IDMuMTNhNCA0IDAgMCAxIDAgNy43NSIgLz4gPHBhdGggZD0iTTIxIDIxdi0yYTQgNCAwIDAgMCAtMyAtMy44NSIgLz4gPC9zdmc%2B)](https://go.mymarketing.click/nfe-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNGQjcxODUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTE4IDhhMyAzIDAgMCAxIDAgNiIgLz4gPHBhdGggZD0iTTEwIDh2MTFhMSAxIDAgMCAxIC0xIDFoLTFhMSAxIDAgMCAxIC0xIC0xdi01IiAvPiA8cGF0aCBkPSJNMTIgOGw0LjUyNCAtMy43N2EuOSAuOSAwIDAgMSAxLjQ3NiAuNjkydjEyLjE1NmEuOSAuOSAwIDAgMSAtMS40NzYgLjY5MmwtNC41MjQgLTMuNzdoLThhMSAxIDAgMCAxIC0xIC0xdi00YTEgMSAwIDAgMSAxIC0xaDgiIC8%2BIDwvc3ZnPg%3D%3D)](https://go.mymarketing.click/nfe-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNDMDg0RkMiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIiA%2BIDxwYXRoIHN0cm9rZT0ibm9uZSIgZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIgLz4gPHBhdGggZD0iTTYgNmEyIDIgMCAwIDEgMiAtMmg4YTIgMiAwIDAgMSAyIDJ2NGEyIDIgMCAwIDEgLTIgMmgtOGEyIDIgMCAwIDEgLTIgLTJsMCAtNCIgLz4gPHBhdGggZD0iTTEyIDJ2MiIgLz4gPHBhdGggZD0iTTkgMTJ2OSIgLz4gPHBhdGggZD0iTTE1IDEydjkiIC8%2BIDxwYXRoIGQ9Ik01IDE2bDQgLTIiIC8%2BIDxwYXRoIGQ9Ik0xNSAxNGw0IDIiIC8%2BIDxwYXRoIGQ9Ik05IDE4aDYiIC8%2BIDxwYXRoIGQ9Ik0xMCA4di4wMSIgLz4gPHBhdGggZD0iTTE0IDh2LjAxIiAvPiA8L3N2Zz4%3D)](https://go.mymarketing.click/nfe-por-agents)

## ライセンス

このリストはCC0 1.0の下にあります。許可を求めることなく、自由にコピー、改変、再配布できます。生成器のコードはawesome-kitにあり、MITライセンスです。

<sub>最終更新 2026-11-10.</sub>
