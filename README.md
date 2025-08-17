# Projeto de Levantamento Probatório – Concresul Ltda. / Fetra Ltda.

Este repositório contém o **ambiente de trabalho interno** do projeto de levantamento de provas relativas à gestão abusiva e temerária praticada pelo administrador Victor Bernardes, visando embasar judicialmente a **assunção da administração das sociedades pelo sócio minoritário Jefferson Almeida**.

> ⚠️ **Atenção:** este repositório _não_ deve ser compartilhado diretamente com terceiros.  
> O **dossiê público** (destinado a peritos, advogados ou magistrados) será gerado posteriormente a partir da pasta `/public`.

---

## 🎯 Objetivo do projeto

Estruturar de forma sistemática e documentada todas as evidências (documentos, comunicações, registros e análises) referentes aos atos de gestão abusiva identificados, de modo a:

- comprovar juridicamente a violação dos deveres fiduciários do administrador;
- demonstrar o risco concreto de dilapidação patrimonial;
- sustentar o pedido judicial de afastamento e assunção da administração pelo sócio minoritário (art. 1.011 do Código Civil).

---

## 📁 Estrutura do repositório

```

/
├── README.md                → este documento
├── docs/                    → documentos brutos (contratos, certidões, emails, etc.)
├── facts/                   → fatos identificados (cada fato em uma subpasta)
│   ├── fact-1/
│   │     └── fact.md        → descrição do fato + notas internas + rascunhos
│   ├── fact-2/
│   │     └── fact.md
│   ├── fact-3/
│   │     └── fact.md
│   ├── fact-4/
│   │     └── fact.md
│   └── fact-5/
│         └── fact.md
├── public/                  → versão “limpa” do dossiê final (para terceiros)
└── jurisprudence/           → jurisprudência, estudos técnicos e templates de peças

```

> 📌 **Nota:**  
> Os documentos brutos não são duplicados dentro das pastas dos fatos — permanecem centralizados na pasta `/docs` e são apenas **referenciados** dentro do respectivo `fact.md`.  
> Arquivos auxiliares (planilhas, cronogramas, pareceres técnicos etc.) podem ser incluídos dentro da pasta do fato **apenas quando necessário**, desde que também sejam referenciados no `fact.md`.

---

## 🛠️ Metodologia de trabalho

1. **Mapeamento dos fatos** (✅ concluído – ver relatório inicial em `/docs`)
2. **Coleta de documentos e inserção na pasta `/docs`**
3. **Criação/atualização dos arquivos `facts/<fact-n>/fact.md`, com referência aos documentos relevantes e anotações internas**
4. **Desenvolvimento das análises e rascunhos argumentativos diretamente no `fact.md`**
5. **Consolidação das peças processuais e evidências selecionadas em `/public`**

---

## 📦 Entregável final

A pasta `/public` será utilizada para gerar um **repositório independente**, contendo:

- resumo dos fatos relevantes;
- evidências organizadas (cada fato com seus documentos vinculados);
- fundamentação jurídica e pedidos.

Esse repositório será redigido em linguagem adequada para **apresentação a terceiros (peritos, tribunal, advogados)**.
