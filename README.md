<div align="center" style="background-color: #0d1117; padding: 40px 20px; border-radius: 12px; border: 1px solid #30363d; max-width: 900px; margin: 0 auto;">

  <h1 style="color: #c9d1d9; margin: 0; font-size: 3.2rem; letter-spacing: 1px;">
    TASMACODE<span style="color: #ff79c6;">-neo</span>
    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="#8b5cf6" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" style="vertical-align: middle; margin-left: 12px;">
      <path d="M17 3a2.828 2.828 0 1 1 4 4L7.5 20.5 2 22l1.5-5.5L17 3z"></path>
    </svg>
  </h1>

  <p style="color: #8b949e; font-size: 1.4rem; margin: 16px 0 32px;">
    Editor de código via terminal poderoso, leve e customizável — feito com <span style="color: #58a6ff;">paixão</span> para devs que vivem no terminal.
  </p>

  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Terminal-First-8B5CF6?style=for-the-badge&logo=linux&logoColor=white" alt="Terminal First" />
    <img src="https://img.shields.io/github/license/John-BrenoF/TASMACODE-neo?style=for-the-badge&color=8B5CF6" alt="License" />
    <img src="https://img.shields.io/github/stars/John-BrenoF/TASMACODE-neo?style=for-the-badge&color=ff79c6" alt="Stars" />
  </p>

  <hr style="border-color: #30363d; margin: 40px 0;" />

  ## 🔥 Por que esse é meu orgulho?

  TASMACODE-neo é um editor de código **full terminal** que eu construí do zero pra ser rápido, modular e cheio de features que eu sempre quis em um editor CLI:

  - Múltiplas abas (tabs) com gerenciamento inteligente
  - Syntax highlighting, linter integrado (flake8/async), auto-complete básico
  - Busca global, replace, tree view de arquivos
  - Sessões persistentes (abre exatamente onde parou)
  - Suporte a plugins (carregamento dinâmico)
  - Interface limpa, keybindings customizáveis
  - Leve pra caralho — roda suave até em máquina antiga

  Perfeito pra quem odeia IDE pesada e vive no **tmux + vim/neovim** mas queria algo mais "moderno" sem perder performance.

  <hr style="border-color: #30363d; margin: 40px 0;" />

  ## 🛠 Tecnologias & Ferramentas

  <p align="center">
    <img src="https://skillicons.dev/icons?i=python,git,linux,vscode,neovim&theme=dark" alt="Tech stack" />
  </p>

  <hr style="border-color: #30363d; margin: 40px 0;" />

  ## 📊 Estatísticas do Projeto

  <table align="center" style="border: none; background: transparent;">
    <tr>
      <td>
        <img src="https://github-readme-stats-fast.vercel.app/api?username=John-BrenoF&repo=TASMACODE-neo&show_icons=true&theme=dracula&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=ff79c6&text_color=c9d1d9&icon_color=8b5cf6" alt="Repo Stats" />
      </td>
      <td>
        <img src="https://github-readme-stats-fast.vercel.app/api/pin/?username=John-BrenoF&repo=TASMACODE-neo&theme=dracula&hide_border=true&bg_color=0d1117&title_color=ff79c6&text_color=c9d1d9" alt="Repo Pin" />
      </td>
    </tr>
  </table>

  <hr style="border-color: #30363d; margin: 40px 0;" />

  ## 🚀 Instalação Rápida

  ```bash
  # Clone o repo
  git clone https://github.com/John-BrenoF/TASMACODE-neo.git
  cd TASMACODE-neo

  # Instale dependências (recomendo virtualenv)
  python -m venv venv
  source venv/bin/activate
  pip install -r requirements.txt

  # Rode!
  python src/main.py
