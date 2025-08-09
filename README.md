🛒 Lista de Compras
Aplicação web interativa para gerenciar uma lista de compras, construída com React, Tailwind CSS e armazenamento no LocalStorage.

📜 Sobre o Projeto
Este projeto permite ao usuário adicionar, editar e remover itens da sua lista de compras, classificá-los por categorias e manter os dados salvos mesmo após fechar o navegador.
A interface é simples, responsiva e otimizada para uso em qualquer dispositivo.

🚀 Tecnologias Utilizadas
React 18 — Gerenciamento de componentes e estado

Tailwind CSS — Estilização rápida e responsiva

LocalStorage — Persistência dos dados no navegador

Babel Standalone (modo prototipagem) — Permite uso de JSX direto no HTML

✨ Funcionalidades
Adicionar itens com nome e categoria

Marcar itens como concluídos ou pendentes

Ajustar quantidade dos itens

Filtrar por status (Todos / Ativos / Concluídos)

Buscar por nome

Contagem de itens por categoria

Limpar somente concluídos ou limpar toda a lista

Dados salvos no LocalStorage

Layout responsivo para mobile e desktop

📂 Estrutura de Pastas (modo simples)
bash
Copiar
Editar
shopping-list/
├─ index.html        # Página principal com React + JSX via Babel
├─ assets/           # (opcional) imagens, ícones
└─ README.md         # Documentação do projeto
Se usar Vite para produção, a estrutura muda para src/ com componentes separados.

⚙️ Como Usar (versão simples)
Baixe ou clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/shopping-list.git
Abra o arquivo index.html no seu navegador.

Não é necessário instalar nada para a versão simples.

🌐 Publicação no GitHub Pages
Envie os arquivos para um repositório no GitHub.

Vá em Settings → Pages e configure:

Source: Deploy from a branch

Branch: main e / (root)

Acesse o link gerado pelo GitHub Pages.

📌 Melhorias Futuras
Converter para estrutura Vite para melhor performance

Adicionar PWA para uso offline no celular

Implementar sistema de login para salvar listas diferentes

📄 Licença
Este projeto está sob a licença MIT — sinta-se livre para usar e modificar.
