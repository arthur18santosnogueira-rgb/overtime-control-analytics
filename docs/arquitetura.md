# Arquitetura do Sistema - Overtime Control Analytics

## 📌 Modelo Utilizado

O modelo de arquitetura adotado foi o C4 Model, que permite a visualização do sistema em diferentes níveis de abstração.

## 🧠 Diagrama de Contexto

O sistema Overtime Control Analytics é utilizado por gestores e analistas de PCP para monitoramento e análise de horas extras. O acesso é realizado via navegador web.

## 🧱 Diagrama de Containers

O sistema é composto por três principais containers:

- Frontend: desenvolvido em React, responsável pela interface do usuário.
- Backend: desenvolvido em Node.js, responsável pela lógica de negócio.
- Banco de Dados: PostgreSQL, responsável pelo armazenamento dos dados.

A comunicação ocorre via requisições HTTP entre frontend e backend.

---

## 🛠 Tecnologias Utilizadas

- React (Frontend)
- Node.js (Backend)
- PostgreSQL (Banco de Dados)
- GitHub (Versionamento)

---

## 🎯 Justificativa da Arquitetura

A arquitetura escolhida permite separação de responsabilidades, escalabilidade e facilidade de manutenção. O uso de tecnologias modernas possibilita rápida evolução do sistema e melhor experiência do usuário.
