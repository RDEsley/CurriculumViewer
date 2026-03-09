<div align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Ghost.png" width="50" alt="Ghost Logo"/>
  
  # 👻 Curriculum Viewer
  
  **Visualize e gerencie currículos de forma simples e eficiente**
  
  [![React](https://img.shields.io/badge/React-Frontend-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
  [![Flask](https://img.shields.io/badge/Flask-Backend-000000?style=for-the-badge&logo=python&logoColor=white)](https://flask.palletsprojects.com/)
  [![SQLite](https://img.shields.io/badge/DB-SQLite%20%2F%20MySQL-2F2F2F?style=for-the-badge&logo=sqlite&logoColor=white)]()
  [![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
  
</div>

---

## 📌 Sobre o Projeto
**Curriculum Viewer** é uma aplicação web para **exibição e gerenciamento de currículos**. Usuários podem navegar e visualizar currículos cadastrados; administradores têm acesso a um painel seguro para **adicionar, editar e remover** currículos.

> 🎯 Projeto ideal para treinar um CRUD completo (Front + Back) e autenticação simples para área administrativa.

---

## ✨ Funcionalidades

- 📄 **Visualização de Currículos** — lista e visualização em detalhe de currículos cadastrados.
- 🔐 **Área Administrativa** — área protegida por autenticação para gerenciar currículos.
  - ➕ Adicionar novos currículos.
  - ✏️ Editar currículos existentes.
  - 🗑️ Remover currículos.
- 📁 **Pesquisa / Filtro** (se implementado) — filtrar currículos por nome, tecnologia ou tag.
- 📸 **Suporte a Fotos / Avatares** — exibir foto do candidato no currículo (se disponível).

---

## 🛠️ Tecnologias & Ferramentas

<div align="left">

| Frontend | React, HTML, CSS, JavaScript |<br>
| Backend | Python, Flask |<br>
| Banco de Dados | SQLite (padrão) / MySQL |<br>
| Autenticação | Sessões do Flask / login simples |<br>
| Versionamento | Git & GitHub |<br>

</div>

---

## 🚀 Como Executar (localmente)

### Pré-requisitos
- Python 3.8+ instalado
- Node.js (se quiser rodar o frontend separadamente)
- Git

### Passo a passo (modo simples)
```bash
# 1. Clone o repositório
git clone https://github.com/RDEsley/CurriculumViewer.git
cd CurriculumViewer

# 2. (Opcional) Crie e ative um ambiente virtual
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate

# 3. Instale dependências do backend
pip install -r requirements.txt

# 4. Configure (se necessário) variáveis de ambiente
# Exemplo:
# export FLASK_APP=main.py
# export FLASK_ENV=development

# 5. Rode a aplicação
python main.py

# 6. Abra no navegador
# http://localhost:5000
```

> OBS: Se o projeto tiver frontend separado com React, abra a pasta `frontend/` e rode `npm install` e `npm start` conforme a estrutura do repositório.

---

## 📂 Estrutura do Projeto (exemplo)
```
CurriculumViewer/
├── backend/
│   ├── main.py
│   ├── app.py
│   ├── controllers/
│   ├── models/
│   ├── templates/
│   └── requirements.txt
├── frontend/           # (opcional)
│   ├── package.json
│   └── src/
├── database/           # arquivos SQLite ou scripts de migração
├── .env.example
└── README.md
```

---

## 📖 Aprendizados & Boas Práticas
- Organização de projeto full‑stack (separação frontend/backend).  
- Implementação de autenticação simples para área administrativa.  
- Modelagem de dados para currículos (experiência, formação, skills).  
- Boas práticas de Git e documentação (README, LICENSE).

---

## 🤝 Como Contribuir

1. Faça um fork do projeto.  
2. Crie uma branch para sua feature: `git checkout -b feature/nome-da-feature`  
3. Faça commits pequenos e descritivos: `git commit -m "feat: adicionar filtro por tecnologia"`  
4. Envie para seu fork: `git push origin feature/nome-da-feature`  
5. Abra um Pull Request explicando as mudanças.  

---

## 🪪 Licença
Este projeto está sob a licença **MIT** — veja o arquivo `LICENSE` para detalhes.

---

## 👥 Desenvolvedores

<div align="center">
Richard Esley, Fernanda Kikuchi


---

<div align="center">
⭐ Se este projeto te ajudou, deixe uma estrela! ⭐  <br>
Feito com 💚 e muito código
</div>

