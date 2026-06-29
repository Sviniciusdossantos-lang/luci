# 🟣 Luci — Validação de Renda PJ via Open Finance

> **Protótipo de produto** que usa dados de Open Finance para validar a renda de clientes Pessoa Jurídica automaticamente, reduzindo a dependência de envio manual de extratos e documentos durante a análise de crédito.

---

## 🧩 O Problema

Hoje, a análise de crédito para empresas (PJ) exige que o cliente envie manualmente extratos bancários, balanços e outros documentos. Esse processo é:

- **Lento** — dias ou semanas de ida e volta de documentos
- **Propenso a erros** — documentos desatualizados, inconsistentes ou manipulados
- **Custoso** — alto volume de trabalho manual na equipe de crédito

---

## 💡 A Solução: Luci

O **Luci** conecta-se às contas bancárias PJ do cliente via **Open Finance** e, com consentimento, coleta e organiza automaticamente os dados financeiros necessários para a análise de crédito.

### O que o Luci faz:

| Funcionalidade | Descrição |
|---|---|
| 📊 **Organiza contas PJ** | Consolida todas as contas bancárias da empresa em uma visão única |
| 🔄 **Mapeia fluxo entre contas** | Mostra a comunicação e movimentações entre as contas da empresa |
| ✅ **Valida renda automaticamente** | Analisa extratos e transações para gerar um score de renda verificável |
| 📄 **Elimina envio manual** | Substitui o processo de coleta de documentos por dados estruturados em tempo real |
| 🔍 **Gera trilha auditável** | Toda análise é rastreável e pode ser revisada por analistas de crédito |

---

## 🏗️ Status do Projeto

Este repositório contém o **backlog e protótipo funcional** da versão inicial do Luci.

O objetivo é levar o produto do zero até uma **primeira versão funcional e auditável**.

Status atual: Em desenvolvimento — MVP

---

## 🗺️ Roadmap — Do Zero ao MVP

### Fase 1 — Fundação
- [ ] Configuração do ambiente e repositório
- [ ] Definição da arquitetura de dados (Open Finance)
- [ ] Prova de conceito de conexão via API Open Finance

### Fase 2 — Coleta de Dados
- [ ] Autenticação e consentimento do usuário PJ
- [ ] Integração com APIs de extrato e saldo
- [ ] Normalização e armazenamento dos dados financeiros

### Fase 3 — Processamento e Análise
- [ ] Motor de cálculo de renda média PJ
- [ ] Mapeamento de fluxo entre contas (comunicação entre contas)
- [ ] Geração de relatório estruturado de renda

### Fase 4 — Interface e Auditoria
- [ ] Dashboard de visão consolidada das contas
- [ ] Visualização do fluxo financeiro entre contas
- [ ] Trilha de auditoria para analistas de crédito
- [ ] Exportação do relatório de validação

---

## 🔐 Segurança e Privacidade

- Todos os dados são coletados mediante **consentimento explícito** do cliente
- Integração via **Open Finance Brasil** (regulamentado pelo Banco Central)
- Dados armazenados com criptografia e acesso controlado por papel (RBAC)

---

## 📁 Estrutura do Repositório

luci/
├── docs/           # Documentação, fluxos e requisitos
├── src/            # Código-fonte do protótipo
├── backlog/        # Histórias de usuário e critérios de aceite
└── README.md       # Este arquivo

---

## 🤝 Contribuindo

Este é um protótipo em fase de validação. Para contribuir ou tirar dúvidas, abra uma issue descrevendo sua sugestão ou problema encontrado.

---

*Luci é um protótipo de produto. Os dados utilizados em testes são fictícios ou gerados em ambiente sandbox.*
