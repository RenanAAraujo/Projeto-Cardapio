# Projeto Cardápio

Este é um projeto de cardápio on-line estático que exibe um menu de hambúrgueres e bebidas, com funcionalidade de carrinho de compras, checagem de diário de funcionamento e notificações ao usuário.

---

## Pré-requisitos

Antes de virçar, certificado de ter instalado em sua mãe:

- [Não.js v14+](https://nodejs.org/) e npm (gerenciador de pacotes do Node)
- Navegador moderno (Chrome, Firefox, Edge, Safari)

---

## Instalação

1. Clone este repositório:

   `bash
 clone Git [https://seu-repositorio.com/Projeto-Cardapio-main.git](https://github.com/RenanAAraujo/Projeto-Cardapio.git)
 cd Projeto-Cardapio-main
   `

2. Instale as dependências para o Tailwind CSS:

   `bash
 npm instalar
   `

---

## Desenvolvimento

1. Gere o CSS do Tailwind em modo watch:

   `bash
 npx tailwindcss - i styles/style.css - o styles/output.css - relógio
   `

2. Abra o arquivo `índice.html` no seu navegador. Você pode usar uma extensão de serviço local, por exemplo:

   `bash
 npx http-servidor.
   `

 ou

   `bash
 servidor ao vivo.
   `

À medida que você modifica o CSS fonte (`estilos/estilo.css`), ó arquivo `estilos/saída.css` será atualizado automatizado.

---

## Estrutura de massas

`
Projeto-Cardapio-main/
│
├─.gitignore ← Arquivos e massas ignorados pelo Git
├─ index.html ← Página principal estática do cardápio
├─ package.json ← Dependências e scripts do projeto
├─ package-lock.json ← Versão fixa das dependências
├─ tailwind.config.js ← Configuração do Tailwind CSS
├─ script.js ← Lógica de carrinho e notificações
│
├─ ativos/ ← Imagens e logotipos usados sem site
│ ├─ Logo.png
│ ├─ bg.png
│ ├─ hamb-1.png... hamb-8.png
│ ├─ refri-1.png, refri-2.png
│
└─ styles/ ← Estilos CSS fonte e compilados
 ├─ style.css ← Configuração e classes do Tailwind
 └─ output.css ← CSS gerado (build)
`

---

## Funcionalidades

- **Listagem de itens**: Exibe hambúrgueres e bebidas com imagem, nome, descrição e preço.
- **Carrinho de compras**: Modal para adicionar itens, visualizar total e quantidade.
- **Validações**: Requer endereço completo e forma de pagamento.
- **Horário de funcionamento**: Disponível apenas entre 18h e 22h local.
- **Notificações**: Brindes informam sucesso ou erros (restaurante fechado, pedido ambiente, etc).

---

## Uso em produção

Para hospedar em produção:

1. Gere o CSS final:

 `bash
 npx tailwindcss - i styles/style.css - o styles/output.css --minify
   `

2. Faça implantar dos arquivos estáticos (`. .html`, `estilos/saída.css`, `script.js`, `, `, `ativos/`) em qualquer serviço de hospitalidade estática (Páginas GitHub, Netlify, Vercel, S3, etc).

---

## Contribuição

Contribuições são bem-vindas!

1. Fork este repositório
2. Filial Crie Uma: `git checkout - b feature/nova-funcionalidade`
3. Faça commit das mudanças: \`git commit - m "Adiciona nova funcionalidade"
4. Envie para o repositório remoto: `git push origin feature/nova-funcionalidade`
5. Abra um Pull Request.

---

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

