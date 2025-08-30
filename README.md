# Port-Mi: Um Implementador de Portfólio Gamificado

O **Port-Mi** é uma plataforma que transforma projetos de desenvolvimento em **missões de jogo**.  
Cada missão possui nível de dificuldade, tecnologias necessárias, recompensas em XP e habilidades desenvolvidas.  
A ideia é transformar o aprendizado e a construção de portfólio em uma **jornada divertida e progressiva**.

---

## 📌 Objetivo
- Organizar ideias de projetos como **fases de um jogo**.
- Estimular desenvolvedores a concluírem projetos com **progressão**.
- **Gamificar o aprendizado**: cada projeto concede **XP**, desbloqueia **níveis** e **badges**.

---

## 🏗️ Arquitetura

- **Frontend (React + Tailwind):**  
  Interface gamificada com dashboards e exibição dos projetos como missões.

- **Backend (Spring Boot):**  
  API REST responsável pela lógica de XP, progressão e CRUD de projetos/usuários.

- **Banco de Dados (PostgreSQL):**  
  Armazena informações de usuários, projetos, níveis e recompensas.

---

## 🔄 Fluxo de Funcionamento

1. Usuário acessa o **frontend** e visualiza as missões.
2. Ao iniciar uma missão, o **frontend** envia requisição para o **backend**.
3. O **backend** aplica as regras de XP e atualiza os dados no banco.
4. O **frontend** exibe o progresso do usuário (XP, badges, níveis).

---

## 🗺️ Roadmap (Níveis de Implementação)

- **Nível 1:**  
  CRUD de projetos (nome, descrição, XP, nível).

- **Nível 2:**  
  Sistema de usuários e progresso (XP, níveis, badges).

- **Nível 3:**  
  Dashboard gamificado com barras de progresso.

- **Boss Final:**  
  Integração com GitHub/Google para importar projetos reais.

---

## 🛠️ Tecnologias Utilizadas
- **Frontend:** React, Tailwind CSS
- **Backend:** Java, Spring Boot
- **Banco:** PostgreSQL
- **Integração:** API REST
