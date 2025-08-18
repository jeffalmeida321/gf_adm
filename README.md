# Projeto de Redação Colaborativa da Ação Judicial – Concresul / Fetra

Este repositório é o **ambiente interno de trabalho** (uso exclusivo de Jefferson Almeida e dos advogados envolvidos) para a elaboração colaborativa da **minuta preliminar da ação judicial** que visa o afastamento do administrador Victor Bernardes por gestão abusiva e temerária.

⚠️ **Atenção:** nenhuma informação contida neste repositório deve ser compartilhada com terceiros. Somente a versão final gerada na pasta `_public` será destinada ao protocolo judicial e/ou envio a peritos, advogados externos e magistrados.

---

## 🎯 Objetivo do projeto

Estruturar, de forma colaborativa e documentada, **a primeira versão da minuta da ação**, reunindo:

- a descrição detalhada dos fatos relevantes;
- os rascunhos argumentativos e comentários internos;
- as referências aos documentos anexos e jurisprudências correspondentes.

Depois de finalizada e validada, esta minuta será refinada e formalizada na pasta `_public`, juntamente com a versão definitiva dos anexos utilizados para o protocolo.

---

## 📁 Estrutura do repositório

```
/
├── README.md
├── \_docs/
│   ├── \_minuta.md             → minuta preliminar da petição (texto base)
│   ├── \_minuta-notas.md       → anotações internas e pendências de revisão
│   ├── \_catalogo.md           → catálogo descritivo dos anexos armazenados em \_docs
│   └── arq00XX.ext            → anexos utilizados e referenciados na \_minuta.md
└── \_public/
└── (versão final para protocolo – minuta + anexos)

```

📌 **Importante:** A pasta `_docs` contém (i) o texto preliminar da petição (`_minuta.md`), (ii) um caderno de anotações e pendências (`_minuta-notas.md`) e (iii) todos os **anexos reais utilizados**, descritos em `_catalogo.md`.  
Os anexos são referenciados na minuta como: *“vide Anexo XX – …”*.

---

## 🛠️ Metodologia de trabalho

1. **Mapeamento de fatos** (concluído — ver arq0007.md no catálogo)
2. **Coleta de documentos e inserção em `_docs` seguindo a numeração do catálogo**
3. **Redação colaborativa da minuto em `_docs/_minuta.md`**, com:
   - descrição dos fatos;
   - referências aos anexos;
   - marcação das pendências adicionais no arquivo `_minuta-notas.md`.
4. **Consolidação final em `_public`**, contendo:
   - minuta jurídica definitiva (sem rascunhos ou comentários);
   - anexos reais organizados e numerados.

---

## 📦 Entregável final

A pasta `_public` conterá o **dossiê final para protocolo judicial**, composto por:

- minuta definitiva da ação;
- anexos reais e organizados conforme numeração de referência;
- fundamentação jurídica completa.
