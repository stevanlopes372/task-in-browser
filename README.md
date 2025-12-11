# ✅ Task-in-Browser

> Um gerenciador de tarefas poderoso, persistente e sem servidor, contido em um único arquivo HTML.

O **Task-in-Browser** é uma ferramenta de produtividade minimalista projetada para quem precisa de foco e agilidade. Ele roda inteiramente no navegador do cliente (Client-Side), utilizando `localStorage` para persistir seus dados. Não requer instalação, backend ou login.

## 🚀 Funcionalidades (Features)

* **⚡ Ultraleve:** Um único arquivo HTML com menos de 20kb.
* **🗂️ Múltiplos Contextos (Projetos):** Crie listas separadas dinamicamente via URL (ex: `?id=trabalho`, `?id=pessoal`).
* **💾 Persistência Automática:** Seus dados são salvos no navegador. Feche a aba e abra novamente: tudo estará lá.
* **🖱️ Drag-and-Drop:** Reorganize suas prioridades arrastando e soltando as tarefas.
* **📝 Área de Contexto:** Um bloco de notas dedicado para cada lista (metas, observações, rascunhos).
* **📂 Dashboard de Projetos:** Um menu visual para navegar entre todas as suas listas ativas.
* **🔐 Privacidade Total:** Os dados ficam no seu dispositivo, nada é enviado para a nuvem.

## 🛠️ Como Usar

### 1. Acesso Rápido
Basta baixar o arquivo `index.html` e abri-lo em qualquer navegador moderno (Chrome, Edge, Firefox, Brave).

### 2. Gerenciando Múltiplas Listas
O Task-in-Browser utiliza parâmetros de URL para separar seus ambientes.

* **Lista Geral:** Abra o arquivo normalmente.
* **Nova Lista:** Adicione `?id=NOME_DA_LISTA` ao final da URL.
    * Exemplo: `.../index.html?id=bugs`
    * Exemplo: `.../index.html?id=roadmap`

### 3. Navegação
Use o botão **📂 Meus Projetos** no topo da página para ver todas as listas que você já criou e alternar entre elas rapidamente.

## 📦 Instalação (Opcional - GitHub Pages)

Para acessar suas tarefas de qualquer lugar (celular/desktop), recomenda-se hospedar este arquivo gratuitamente no **GitHub Pages**:

1.  Faça um fork ou clone deste repositório.
2.  Vá em **Settings** > **Pages**.
3.  Selecione a branch `main` e salve.
4.  Acesse via: `https://seu-usuario.github.io/task-in-browser/`

## 🤝 Contribuindo

Sinta-se à vontade para fazer um fork e submeter Pull Requests. Ideias para o futuro:
- [ ] Exportar dados para JSON/CSV.
- [ ] Modo escuro (Dark Mode).

---
*Desenvolvido com ❤️ e JavaScript Puro.*
