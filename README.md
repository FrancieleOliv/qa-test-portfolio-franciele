# QA Test Portfolio

Portfolio project created for QA practice and learning purposes.

## 🇺🇸 English

This repository contains real software testing cases performed on public web applications.  
The goal is to demonstrate practical **Quality Assurance (QA)** skills such as:

- functional analysis
- exploratory testing
- identification of inconsistencies
- system behavior analysis
- bug documentation
- manual testing evidence

---

## Test Cases

### 1️⃣ AI Resume Builder Test (Vagas.com)

Test performed on the experimental AI-powered resume creation tool from the Vagas.com platform.

Application tested: https://experimente-vccv.vagas.com.br/

#### Scenarios tested

- Upload resume as **PDF**
- Upload resume as **image**
- Manual text insertion
- Interaction with the tool's chatbot

---

### Problems identified

#### 1️⃣ Failure to extract data from PDF
The tool reports that it received the PDF, but then prompts the user to manually enter the information again.

**Severity:** High  
**Impact:** The tool's main feature does not function correctly, forcing the user to manually enter resume information.

---

#### 2️⃣ Image reading failure (limited OCR)

When sending the resume as an image, the AI could only identify the candidate's name, ignoring other information present on the page.

The AI tool only allows a single image upload, so it's limited to concise, single-page resumes.

**Severity:** Medium  
**Impact:** The tool only recognizes part of the resume information, reducing the usefulness of uploading images.

---

#### 3️⃣ Poor Text Optimization

When the complete resume text was manually entered, the tool only:
- replaced some words with synonyms
- rearranged the order of some paragraphs

**Severity:** Low  
**Impact:** The AI does not significantly improve the resume content, limiting the value of the functionality.

---

#### 4️⃣ Language Inconsistency (UX Bug)

A language inconsistency was identified during exploratory testing. Even with the entire conversation in Portuguese, the tool responded in English during the explanation of its operation.

**Severity:** Low  
**Impact:** Unexpected language switching can cause confusion in the user experience.

---

## Type of Test Performed

Manual exploratory testing.

---

## Evidence

Screenshots and interaction logs are available in the test directory.

---

## Project Structure

qa-test-portfolio  
│  
├── test-cases  
│ └── vagas-vccv-ai-cv-test  
│ ├── test-report.md  
│ ├── screenshots  
│ └── evidence  
│  
└── README.md  

------------

## 🇧🇷 Português

Este repositório reúne casos reais de testes de software realizados em aplicações web públicas.  
O objetivo é demonstrar habilidades práticas em **Quality Assurance (QA)**, incluindo:

- análise funcional
- testes exploratórios
- identificação de inconsistências
- análise de comportamento do sistema
- documentação de bugs
- evidências de testes manuais

---

## Casos de teste

### 1️⃣ Teste do Criador de Currículos com IA (Vagas.com)

Teste realizado na ferramenta experimental de criação de currículo com IA da plataforma Vagas.com.

Aplicativo testado: https://experimente-vccv.vagas.com.br/

#### Cenários testados

- Carregar currículo em **PDF**
- Carregar currículo em **imagem**
- Inserção de **texto manual**
- Interação com o chatbot da ferramenta

---

### Problemas identificados

#### 1️⃣ Falha na extração de dados do PDF
A ferramenta informa que recebeu o PDF, porém solicita novamente que o usuário digite as informações manualmente.

**Gravidade:** Alta  
**Impacto:** O recurso principal da ferramenta não funciona corretamente, obrigando o usuário a inserir manualmente as informações do currículo.

---

#### 2️⃣ Falha na leitura de imagem (OCR limitado)

Ao enviar o currículo em imagem, a IA conseguiu identificar apenas o nome do candidato, ignorando outras informações presentes na página.

A IA só permite o carregamento de uma imagem, então fica limitado a currículos enxutos de uma única página.

**Gravidade:** Média  
**Impacto:** A ferramenta reconhece apenas parte das informações do currículo, reduzindo a utilidade do upload de imagem.

---

#### 3️⃣ Baixa otimização de texto

Quando o texto completo do currículo foi inserido manualmente, a ferramenta apenas:
- substituiu algumas palavras por sinônimos
- reorganizou a ordem de alguns parágrafos

**Gravidade:** Baixa  
**Impacto:** A IA não gera melhoria significativa no conteúdo do currículo, limitando o valor da funcionalidade.

---

#### 4️⃣ Inconsistência de idioma (UX Bug)

Identificação de inconsistência de idioma durante o teste exploratório. Mesmo com toda a conversa em português, a ferramenta respondeu em inglês durante a explicação de funcionamento.

**Gravidade:** Baixa  
**Impacto:** A alternância inesperada de idioma pode causar confusão na experiência do usuário.

---

## Tipo de teste realizado

Testes exploratórios manuais.

---

## Evidências

Capturas de tela e registros de interações estão disponíveis na pasta do teste.

---

## Estrutura do projeto

qa-test-portfolio  
│  
├── test-cases  
│ └── vagas-vccv-ai-cv-test  
│ ├── test-report.md  
│ ├── screenshots  
│ └── evidence  
│  
└── README.md
