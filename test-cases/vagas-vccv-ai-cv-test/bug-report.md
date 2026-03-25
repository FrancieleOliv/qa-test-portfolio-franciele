# Bug Report – AI Resume Builder (Vagas.com)

This document contains the defects identified during exploratory testing of the AI Resume Builder from Vagas.com.

Application tested:
https://experimente-vccv.vagas.com.br/

---

## Bug 1 – Failure in PDF Data Extraction

**Severity:** High
**Priority:** High
**Impact:** The main functionality of the tool does not work correctly, forcing the user to manually enter resume information.

**Steps to reproduce**

1. Access the AI Resume Builder tool
2. Upload a resume in PDF format
3. Wait for the system to process the file

**Expected result**

The system should extract the information from the PDF and automatically populate the resume fields.

**Actual result**

The system reports that the file was received but asks the user to manually enter the information again.

**Evidence**

Available in the evidence folder:
`test-cases/vagas-vccv-ai-cv-test/evidence/pdf-upload/`

---

## Bug 2 – Partial OCR Processing on Image Upload

**Severity:** Medium
**Priority:** Medium
**Impact:** The tool recognizes only part of the resume information.

**Steps to reproduce**

1. Upload a resume as an image
2. Wait for the system to process the file

**Expected result**

The system should identify the information contained in the resume.

**Actual result**

The tool only recognizes the candidate’s name and ignores the remaining information.

**Evidence**

Available in the evidence folder:
`test-cases/vagas-vccv-ai-cv-test/evidence/image-upload/`

---

## Bug 3 – Insufficient Text Optimization by AI Engine

**Severity:** Low
**Priority:** Low
**Impact:** The AI does not significantly improve the resume content.

**Steps to reproduce**

1. Insert the full resume text manually
2. Submit the text for optimization

**Expected result**

The system should significantly improve and structure the resume content.

**Actual result**

The system only replaces some words with synonyms and slightly rearranges paragraphs.

**Observation:**

The AI response lacks significant enhancement, indicating limited optimization capability.

**Evidence**

Available in the evidence folder:
`test-cases/vagas-vccv-ai-cv-test/evidence/text-input/`

---

## Bug 4 – Language Inconsistency (UX Bug)

**Severity:** Low
**Priority:** Medium
**Impact:** Unexpected language switching can confuse the user experience.

**Steps to reproduce**

1. Interact with the tool in Portuguese
2. Continue the interaction until the system explains how the tool works

**Expected result**

The system should maintain the conversation in Portuguese.

**Actual result**

The system switches to English unexpectedly during the explanation.

**Evidence**

Available in the evidence folder:
`test-cases/vagas-vccv-ai-cv-test/evidence/ux-language/`

------------

## 🇧🇷 Português


# Relatório de Erro – Criador de Currículos com IA (Vagas.com)

Este documento contém os defeitos identificados durante os testes exploratórios do Criador de Currículos com IA da Vagas.com.

Aplicativo testado:
https://experimente-vccv.vagas.com.br/

---

## Erro 1 – Falha na Extração de Dados do PDF

**Gravidade:** Alta
**Prioridade:** Alta
**Impacto:** A funcionalidade principal da ferramenta não funciona corretamente, obrigando o usuário a inserir manualmente as informações do currículo.

**Passos para reproduzir**

1. Acesse a ferramenta Criador de Currículos com IA
2. Envie um currículo em formato PDF
3. Aguarde o processamento do arquivo pelo sistema

**Resultado esperado**

O sistema deve extrair as informações do PDF e preencher automaticamente os campos do currículo.

**Resultado obtido**

O sistema informa que o arquivo foi recebido, mas solicita que o usuário insira as informações manualmente novamente.

**Evidências**

Disponíveis na pasta de evidências:
`test-cases/vagas-vccv-ai-cv-test/evidence/pdf-upload/`

---

## Bug 2 – Processamento OCR Parcial no Upload da Imagem

**Gravidade:** Média
**Prioridade:** Média
**Impacto:** A ferramenta reconhece apenas parte das informações do currículo.

**Passos para reproduzir**

1. Envie um currículo como imagem.
2. Aguarde o processamento do arquivo pelo sistema.

**Resultado esperado**

O sistema deve identificar as informações contidas no currículo.

**Resultado obtido**

A ferramenta reconhece apenas o nome do candidato e ignora as demais informações.

**Evidências**

Disponíveis na pasta de evidências:
`test-cases/vagas-vccv-ai-cv-test/evidence/image-upload/`

---

## Bug 3 – Otimização de texto insuficiente pelo mecanismo de IA

**Gravidade:** Baixa
**Prioridade:** Baixa
**Impacto:** A IA não melhora significativamente o conteúdo do currículo.

**Passos para reproduzir**

1. Insira o texto completo do currículo manualmente.
2. Envie o texto para otimização.

**Resultado esperado**

O sistema deve melhorar e estruturar significativamente o conteúdo do currículo.

**Resultado atual**

O sistema apenas substitui algumas palavras por sinônimos e reorganiza ligeiramente os parágrafos.

**Observação:**

A resposta da IA ​​carece de aprimoramento significativo, indicando capacidade de otimização limitada.

**Evidências**

Disponíveis na pasta de evidências:
`test-cases/vagas-vccv-ai-cv-test/evidence/text-input/`

---

## Bug 4 – Inconsistência de idioma (Bug de UX)

**Gravidade:** Baixa
**Prioridade:** Média
**Impacto:** A troca inesperada de idioma pode confundir a experiência do usuário.

**Passos para reproduzir**

1. Interaja com a ferramenta em português.
2. Continue a interação até que o sistema explique como a ferramenta funciona.

**Resultado esperado**

O sistema deve manter a conversa em português.

**Resultado atual**

O sistema muda para o inglês inesperadamente durante a explicação.

**Evidências**

Disponíveis na pasta de evidências:
`test-cases/vagas-vccv-ai-cv-test/evidence/ux-language/`
