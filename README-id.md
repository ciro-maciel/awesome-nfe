# Awesome NF-e

> Nota fiscal elektronik untuk integrator: portal resmi, library per bahasa pemrograman, API penerbitan, dan server MCP.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-tanda%20tangan-111111?style=flat-square)](https://go.mymarketing.click/nfe-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/nfe-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/nfe-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/id.xml) ![35 item](https://img.shields.io/badge/item-35-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-6b6b6b?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Untuk yang perlu menerbitkan, menerima, atau memeriksa nota fiscal di dalam sistem. Dimulai dari portal tempat manual dan schema berada, lalu library terbuka untuk tiap bahasa, dan diakhiri dengan API yang menerbitkan atas nama Anda. Setiap alamat sudah dibuka sebelum dimasukkan.

## Konten

- [Portal resmi](#portal-resmi)
- [Pustaka PHP](#pustaka-php)
- [Pustaka Java](#pustaka-java)
- [Pustaka .NET](#pustaka-net)
- [Pustaka Python](#pustaka-python)
- [Pustaka JavaScript dan TypeScript](#pustaka-javascript-dan-typescript)
- [Delphi dan Lazarus](#delphi-dan-lazarus)
- [API penerbitan](#api-penerbitan)
- [Server MCP](#server-mcp)
- [Daftar lainnya](#daftar-lainnya)
- [Label](#label)
- [Cara berkontribusi](#cara-berkontribusi)
- [Daftar lainnya](#daftar-lainnya)
- [Dibuat oleh Ciro Cesar Maciel](#dibuat-oleh-ciro-cesar-maciel)
- [Lisensi](#lisensi)

## Portal resmi

Tempat manual, skema, dan nota teknis tiap dokumen.

- [Portal Nacional da NF-e](https://go.mymarketing.click/nfe-portal-nacional-da-nf-e) - Panduan, skema XML, nota teknis, dan layanan konsultasi NF-e. `resmi` `gratis`
- [NFS-e Nacional](https://go.mymarketing.click/nfe-nfs-e-nacional) - Standar nasional nota fiskal jasa, dengan penerbit publik dan lingkungan data. `resmi` `gratis`
- [NFS-e Nacional: documentação técnica](https://go.mymarketing.click/nfe-nfs-e-nacional-documentacao-tecnica) - Manual, layout, dan API NFS-e Nasional untuk integrator. `resmi` `gratis` `API`
- [Portal da NFC-e](https://go.mymarketing.click/nfe-portal-da-nfc-e) - Dokumentasi nota fiskal konsumen di portal SVRS, dipakai oleh beberapa negara bagian. `resmi` `gratis`
- [Portal Nacional do CT-e](https://go.mymarketing.click/nfe-portal-nacional-do-ct-e) - Manual dan skema conhecimento de transporte eletrônico (CT-e). `resmi` `gratis`
- [Portal do MDF-e](https://go.mymarketing.click/nfe-portal-do-mdf-e) - Dokumentasi manifesto elektronik dokumen fiskal. `resmi` `gratis`
- [Portal do SPED](https://go.mymarketing.click/nfe-portal-do-sped) - Sistem Pembukuan Digital Publik Receita Federal: EFD, ECD, ECF, dan program validator. `resmi` `gratis`

## Pustaka PHP

Terbuka, dengan aktivitas di repositori pada 2026.

- [sped-nfe](https://go.mymarketing.click/nfe-sped-nfe) - Pustaka paling banyak dipakai untuk membuat, menandatangani, dan mengirim NF-e dan NFC-e ke SEFAZ. `open source`
- [sped-common](https://go.mymarketing.click/nfe-sped-common) - Kelas umum NFePHP untuk NF-e, CT-e, dan MDF-e: sertifikat, tanda tangan, dan komunikasi. `open source`
- [nfse-php](https://go.mymarketing.click/nfe-nfse-php) - SDK PHP untuk NFS-e Nasional. `open source` `SDK`
- [php-nfse](https://go.mymarketing.click/nfe-php-nfse) - Pembuatan dan komunikasi NFS-e dengan pemerintah kota. `open source`
- [Cliente PHP da NFE.io](https://go.mymarketing.click/nfe-cliente-php-da-nfe-io) - SDK PHP NFE.io untuk menerbitkan NFS-e, tanpa dependensi. `open source` `SDK`

## Pustaka Java

Terbuka, dengan aktivitas di repositori pada 2026.

- [Java_NFe](https://go.mymarketing.click/nfe-java-nfe) - NF-e dan NFC-e di Java, dengan konsultasi, pengiriman, pembatalan, dan event. `open source`
- [wmixvideo/nfe](https://go.mymarketing.click/nfe-wmixvideo-nfe) - Nota fiskal elektronik di Java, dengan model data lengkap. `open source`

## Pustaka .NET

Terbuka, dengan aktivitas di repositori pada 2026.

- [DFe.NET](https://go.mymarketing.click/nfe-dfe-net) - Pembuatan NF-e dan NFC-e serta penggunaan layanan SEFAZ di C#. `open source`
- [ZeusFiscal](https://go.mymarketing.click/nfe-zeusfiscal) - Penerbitan dan pencetakan NF-e, NFC-e, MDF-e, dan CT-e di C#. `open source`
- [Unimake DFe](https://go.mymarketing.click/nfe-unimake-dfe) - DLL untuk mengintegrasikan ERP dengan dokumen fiskal elektronik. `open source`
- [OpenAC.Net.NFSe](https://go.mymarketing.click/nfe-openac-net-nfse) - Penerbitan dan pengiriman NFS-e untuk berbagai standar kota. `open source`
- [OpenAC.Net.NFSe.Nacional](https://go.mymarketing.click/nfe-openac-net-nfse-nacional) - Penerbitan NFS-e standar nasional di C#. `open source`

## Pustaka Python

Terbuka, dengan aktivitas di repositori pada 2026.

- [PyNFe](https://go.mymarketing.click/nfe-pynfe) - Antarmuka dengan webservice NF-e dan NFC-e di Python. `open source`
- [nfelib](https://go.mymarketing.click/nfe-nfelib) - Binding Python untuk membaca dan membuat XML NF-e, NFS-e Nasional, CT-e, MDF-e, dan BP-e. `open source`
- [Localização brasileira do Odoo](https://go.mymarketing.click/nfe-localizacao-brasileira-do-odoo) - Modul fiskal Brasil untuk Odoo, termasuk NF-e. `open source`

## Pustaka JavaScript dan TypeScript

Terbuka, dengan aktivitas di repositori pada 2026.

- [NFeWizard](https://go.mymarketing.click/nfe-nfewizard) - Pustaka Node.js untuk layanan SEFAZ: penerbitan, konsultasi, event, dan DANFE. `open source`
- [node-sped-nfe](https://go.mymarketing.click/nfe-node-sped-nfe) - Penerbitan dan komunikasi NF-e dengan SEFAZ di Node.js. `open source`
- [Cliente Node.js da NFE.io](https://go.mymarketing.click/nfe-cliente-node-js-da-nfe-io) - SDK TypeScript NFE.io untuk menerbitkan NFS-e, tanpa dependensi. `open source` `SDK`

## Delphi dan Lazarus

Komponen otomasi komersial untuk Delphi dan Lazarus.

- [Projeto ACBr](https://go.mymarketing.click/nfe-projeto-acbr) - Komponen otomasi komersial untuk Delphi dan Lazarus, dengan NF-e, NFC-e, NFS-e, CT-e, dan SPED. `open source`
- [ACBr no GitHub](https://go.mymarketing.click/nfe-acbr-no-github) - Cermin repositori SVN Proyek ACBr. `open source`

## API penerbitan

Layanan yang menerbitkan dokumen untuk Anda. Urutan abjad.

- [eNotas](https://go.mymarketing.click/nfe-enotas) - Penerbitan NFS-e dan NF-e otomatis untuk yang berjualan online. `berbayar` `API`
- [Focus NFe](https://go.mymarketing.click/nfe-focus-nfe) - API untuk NF-e, NFC-e, NFS-e, CT-e dan MDF-e. `berbayar` `API`
- [NFE.io](https://go.mymarketing.click/nfe-nfe-io) - API untuk penerbitan NFS-e dan NF-e serta konsultasi data pajak. `berbayar` `API`
- [PlugNotas](https://go.mymarketing.click/nfe-plugnotas) - API Tecnospeed untuk NF-e, NFC-e dan NFS-e di ribuan kota. `berbayar` `API`
- [Qive](https://go.mymarketing.click/nfe-qive) - Penangkapan dan pengelolaan faktur pajak yang diterima, sebelumnya disebut Arquivei. `berbayar` `API`
- [Webmania](https://go.mymarketing.click/nfe-webmania) - API REST untuk NF-e, NFC-e dan NFS-e. `berbayar` `API`

## Server MCP

Untuk agen AI memeriksa dan memverifikasi dokumen pajak.

- [mcp-fiscal-brasil](https://go.mymarketing.click/nfe-mcp-fiscal-brasil) - Server MCP pajak: CNPJ, NF-e, NFS-e, CT-e, SPED, eSocial dan Simples Nacional. `open source`

## Daftar lainnya

Terbuka, dengan aktivitas di repositori pada 2026.

- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - Server MCP untuk layanan Brasil, termasuk pajak. `gratis`

## Label

Setiap item menjelaskan apa itu. Label di sampingnya membantu memilih: resmi jika berasal dari pihak yang menetapkan standar, open source jika kodenya dipublikasikan, gratis atau berbayar menurut model penggunaannya, serta API dan SDK menurut cara integrasinya. Item dengan label "buatan penulis" dibuat oleh Ciro Cesar Maciel dan mengikuti aturan yang sama dengan item lainnya.

## Cara berkontribusi

Tahu ada yang kurang, berubah, atau sudah tidak aktif? Buka issue dengan formulir penambahan baru atau kirim pull request dengan mengedit data/list.json. README tiap bahasa dibuat dari berkas ini.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Daftar lainnya

Daftar kurasi dengan format yang sama, dalam bahasa Portugis dan 14 bahasa lainnya.

- [Awesome IA no trabalho](https://go.mymarketing.click/nfe-lista-ia-no-trabalho) - AI di tempat kerja, per profesi: asisten, privasi, regulasi, dan sumber resmi untuk memeriksa hasil tulisan AI.
- [Awesome IA na advocacia](https://go.mymarketing.click/nfe-lista-ia-advocacia) - AI untuk pengacara: asisten, privasi, regulasi AI di bidang hukum dan peradilan, serta sumber resmi untuk diperiksa.
- [Awesome IA na contabilidade](https://go.mymarketing.click/nfe-lista-ia-contabilidade) - AI untuk akuntan: asisten, privasi, regulasi CFC, dan sumber dari Receita, eSocial, dan Simples untuk diperiksa.
- [Awesome IA na sala de aula](https://go.mymarketing.click/nfe-lista-ia-sala-de-aula) - AI untuk guru: asisten, usia minimum dan privasi masing-masing, serta regulasi pendidikan untuk diperiksa.
- [Awesome IA no atendimento e nas vendas](https://go.mymarketing.click/nfe-lista-ia-atendimento-e-vendas) - AI untuk layanan dan penjualan: asisten, privasi, hak konsumen, dan aturan kerja bagi yang berada di konter, kasir, dan telepon.
- [Awesome IA no escritório](https://go.mymarketing.click/nfe-lista-ia-escritorio) - AI untuk sekretaris, asisten, dan staf administrasi: asisten, privasi, tata tulis resmi, dan penipuan yang datang lewat email.
- [Awesome IA no pequeno negócio](https://go.mymarketing.click/nfe-lista-ia-pequeno-negocio) - AI untuk MEI dan pengusaha kecil: asisten, privasi, aturan MEI dan Simples, konsumen, dan LGPD bagi usaha kecil.
- [Awesome IA no primeiro trabalho](https://go.mymarketing.click/nfe-lista-ia-primeiro-trabalho) - AI untuk yang baru mulai bekerja: asisten, privasi, tempat mencari lowongan, hak kerja pertama, dan penipuan lowongan palsu.
- [Awesome Pix](https://go.mymarketing.click/nfe-lista-pix) - Pix untuk integrator: regulasi, API, SDK, penyedia layanan, dan alat, diperiksa satu per satu.
- [Awesome MCP Brasil](https://go.mymarketing.click/nfe-awesome-mcp-brasil) - Server MCP untuk layanan Brasil: data publik, CNPJ, fiskal, hukum, pasar keuangan, perdagangan, dan pembayaran.
- [Awesome livros de IA](https://go.mymarketing.click/nfe-lista-livros-ia) - Buku tentang kecerdasan buatan dalam bahasa Portugis: dari penggunaan pertama hingga profesi, dari pembangun hingga perdebatan.
- [Awesome ferramentas online](https://go.mymarketing.click/nfe-lista-ferramentas-online) - Alat gratis yang berjalan di browser tanpa instalasi: gambar, PDF, teks, kode, situs, email, video, dan penjualan.
- [Awesome APIs Brasil](https://go.mymarketing.click/nfe-lista-apis-brasil) - API publik Brasil: CEP, CNPJ, Banco Central, IBGE, Legislativo, Judiciário, hari libur, dan data terbuka.
- [Awesome Claude Code BR](https://go.mymarketing.click/nfe-lista-claude-code-br) - Claude Code dalam bahasa Portugis: dokumentasi, kursus, skills, aturan, plugin, dan server MCP buatan Brasil.
- [Awesome pagamentos Brasil](https://go.mymarketing.click/nfe-lista-pagamentos-brasil) - Pembayaran di Brasil untuk integrator: regulasi, gateway, acquirer, boleto, langganan, split, dan antifraud.
- [Awesome Open Finance Brasil](https://go.mymarketing.click/nfe-lista-open-finance-brasil) - Open Finance dan Open Insurance di Brasil: regulasi, spesifikasi, data terbuka, agregator, dan open source.
- [Awesome WhatsApp API](https://go.mymarketing.click/nfe-lista-whatsapp-api) - WhatsApp untuk integrator: API resmi Meta, penyedia layanan, pustaka tidak resmi, dan risiko tiap jalur.
- [Awesome empresa de uma pessoa](https://go.mymarketing.click/nfe-lista-empresa-de-uma-pessoa) - Apa yang dipakai orang untuk menjalankan bisnis penuh dengan agen AI: membuka layanan, menagih, mengukur, mempromosikan, dan ditemukan.

## Dibuat oleh Ciro Cesar Maciel

Menggunakan hasil karya saya juga cara untuk mendukung daftar ini.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/nfe-por-agents)

## Lisensi

Daftar ini berlisensi CC0 1.0: salin, adaptasi, dan sebarkan sesuka Anda tanpa izin. Kode generatornya ada di awesome-kit, berlisensi MIT.

<sub>Diperbarui pada 2026-11-10.</sub>
