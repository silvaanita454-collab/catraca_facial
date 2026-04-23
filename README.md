# catraca_facial
# 🎓 Sistema de Controle de Acesso com Reconhecimento Facial

## 📌 Descrição

Este projeto consiste em um sistema de controle de entrada e saída de alunos utilizando reconhecimento facial.
O objetivo é automatizar o registro de presença e notificar responsáveis em tempo real.

Quando o aluno chega ou sai da instituição:

* Seu rosto é identificado pelo sistema
* O evento é registrado no banco de dados
* O responsável recebe uma notificação

---

## 🚀 Funcionalidades

* 📷 Reconhecimento facial em tempo real
* 🧑 Cadastro de alunos e responsáveis
* 📊 Registro automático de entrada e saída
* 🔔 Notificação para responsáveis
* 📈 Visualização de histórico de acessos

---

## 🏗️ Arquitetura do Sistema

O sistema é dividido em três partes principais:

* **Frontend:** Interface para administração e visualização
* **Backend:** API responsável pela lógica de negócio
* **Serviço de Reconhecimento Facial:** Processamento de imagens

```
[ Câmera ]
     ↓
[ Serviço Facial ]
     ↓
[ API Backend ]
     ↓
[ Banco de Dados ]
     ↓
[ Notificação + Frontend ]
```

---

## 🛠️ Tecnologias Utilizadas

### Backend

* Node.js / Django
* API REST

### Frontend

* React ou Vue.js

### Reconhecimento Facial

* OpenCV
* Biblioteca Face Recognition

### Banco de Dados

* PostgreSQL ou MongoDB

---

## 🔐 Segurança e Privacidade

Este sistema considera boas práticas de segurança:

* Armazenamento seguro de dados biométricos
* Controle de acesso por autenticação
* Criptografia de dados sensíveis
* Adequação à LGPD (Lei Geral de Proteção de Dados)

---

## 📦 Estrutura do Projeto

```
/project-root
 ├── backend/
 ├── frontend/
 ├── facial-service/
 ├── database/
 └── docs/
```

---

## ⚙️ Como Executar o Projeto

### 1. Clonar repositório

```
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### 2. Backend

```
cd backend
npm install
npm run dev
```

### 3. Frontend

```
cd frontend
npm install
npm start
```

### 4. Serviço de reconhecimento facial

```
cd facial-service
python main.py
```

---

## 📊 Fluxo do Sistema

1. Câmera captura imagem do aluno
2. Sistema realiza reconhecimento facial
3. Identifica o aluno no banco de dados
4. Registra entrada ou saída
5. Envia notificação ao responsável

---

## 📌 Possíveis Melhorias

* Aplicativo mobile para responsáveis
* Dashboard com relatórios de frequência
* Integração com catracas físicas
* Detecção de fraude (anti-spoofing)

---

## 👥 Equipe

* Backend
* Frontend
* Analista de Sistemas

---

## 📄 Licença

Este projeto é acadêmico e de uso educacional.
