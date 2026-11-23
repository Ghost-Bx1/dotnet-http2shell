# dotnet-http2shell - .NET Brotli OOB Write Exploits

> Brotli OOB Write em .NET BrotliDecoder / BrotliStream. Decompressor escreve alem do buffer de saida quando MLEN excede o Span<byte> sem verificacao de bounds.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square)
![By Gh0st-Bx1](https://img.shields.io/badge/By-Gh0st--Bx1-black?style=flat-square&logo=github)

---

> **AVISO LEGAL:** Este repositorio foi criado exclusivamente para fins educacionais e de pesquisa em seguranca. O uso destas ferramentas contra sistemas sem autorizacao previa e expresso por escrito e ilegal. O autor nao se responsabiliza pelo uso indevido deste material.

---

## Vulnerabilidades

| CVE | Produto | CVSS | Tipo | Status |
|-----|---------|------|------|--------|
| [CVE-2026-111497](cve-2026-111497/) | .NET 8.0.0-8.0.32 / 9.0.0-9.0.21 / 10.0.0-10.0.13 / 11 RC3 | 9.2 Critical | Brotli OOB Write RCE | PoC + Exploit |

---

By Gh0st-Bx1 | https://github.com/Ghost-Bx1
