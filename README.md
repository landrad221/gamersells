<div align="center">

# 🎮 GamerSell

### Eleve o nível do seu setup.

**Loja virtual de periféricos, acessórios e produtos para gamers.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)](https://www.php.net/)
[![MySQL opcional](https://img.shields.io/badge/MySQL-Opcional-4479A1?logo=mysql&logoColor=white)](https://www.mysql.com/)

[Repositório](https://github.com/landrad221/gamersells) · [Issues](https://github.com/landrad221/gamersells/issues)

</div>

## 📖 Sobre o projeto

A **GamerSell** é um projeto de loja virtual voltada à venda de periféricos e produtos relacionados ao universo gamer. Seu objetivo é oferecer uma experiência de compra simples, intuitiva e responsiva para quem deseja montar ou melhorar seu setup.

O projeto utiliza uma stack web enxuta: **HTML5, CSS3, JavaScript puro e PHP**, com possibilidade de integração ao **MySQL** para armazenamento de dados.

> **Status:** projeto em fase inicial. Os recursos descritos a seguir são funcionalidades planejadas, não necessariamente já implementadas.

## 🛍️ Categorias de produtos

- **Teclados:** modelos mecânicos, keycaps e acessórios.
- **Mouses:** mouses gamers, mousepads e acessórios.
- **Áudio:** headsets, microfones e caixas de som.
- **Monitores:** telas gamers e acessórios relacionados.
- **Controles:** gamepads e outros dispositivos de entrada.
- **Acessórios para setup:** iluminação RGB, suportes e organizadores.
- **Outros produtos gamers:** itens complementares para computadores e consoles.

## ✨ Funcionalidades planejadas

- [ ] Página inicial responsiva com produtos em destaque.
- [ ] Catálogo de produtos organizado por categorias.
- [ ] Páginas de produtos com imagens, descrições e preços.
- [ ] Busca, filtros e ordenação de produtos.
- [ ] Carrinho de compras com cálculo de quantidades e subtotais.
- [ ] Finalização de compra e resumo do pedido.
- [ ] Cadastro e autenticação de clientes.
- [ ] Backend em PHP para gerenciamento de produtos e pedidos.
- [ ] Integração opcional com MySQL para persistência de dados.
- [ ] Painel administrativo para gerenciamento de estoque.

## 🧰 Tecnologias utilizadas e permitidas

| Tecnologia | Finalidade | Situação |
| --- | --- | --- |
| HTML5 | Estrutura semântica das páginas | Permitida |
| CSS3 | Estilização, animações e responsividade | Permitida |
| JavaScript (puro) | Interações e funcionalidades no navegador | Permitida |
| PHP | Lógica no servidor, validações e endpoints | Permitida |
| MySQL | Armazenamento persistente de dados | Opcional |

A proposta é desenvolver a aplicação sem depender de frameworks de frontend ou de outras linguagens de backend.

## 🗂️ Estrutura de diretórios sugerida

```text
gamersells/
├── index.php               # Página inicial da loja
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── app.js
│   └── images/
├── includes/               # Componentes PHP compartilhados
├── pages/                  # Catálogo, carrinho e finalização de compra
├── api/                    # Endpoints PHP, se necessários
├── config/                 # Configurações sem credenciais versionadas
├── database/               # Esquemas e migrações opcionais
└── README.md
```

*Essa organização é apenas uma sugestão para o desenvolvimento e não representa necessariamente a estrutura atual do repositório.*

## 🚀 Como começar

Clone o repositório e acesse a pasta do projeto:

```bash
git clone https://github.com/landrad221/gamersells.git
cd gamersells
```

Para páginas estáticas feitas com HTML, CSS e JavaScript, é possível utilizar um navegador. Quando houver páginas em PHP, instale o PHP e inicie o servidor de desenvolvimento na raiz do projeto:

```bash
php -S localhost:8000
```

Acesse **http://localhost:8000** no navegador.

> O servidor embutido do PHP é indicado para desenvolvimento local, não para produção. A execução da loja dependerá da implementação dos arquivos da aplicação.

### Integração opcional com MySQL

Caso seja necessário armazenar produtos, clientes e pedidos:

1. Instale e configure um servidor MySQL.
2. Crie um banco de dados e um usuário específico para a aplicação, com permissões adequadas.
3. Mantenha credenciais em variáveis de ambiente ou arquivos locais não versionados.
4. Utilize **PDO** e consultas preparadas para acessar o banco pelo PHP.
5. Versione o esquema do banco de dados no diretório `database/`.

O MySQL **não é obrigatório** para um protótipo inicial com páginas estáticas.

## 🗺️ Planejamento do desenvolvimento

| Etapa | Objetivo |
| --- | --- |
| 1 — Interface | Layout, navegação, cards de produtos e responsividade |
| 2 — Compras | Páginas de produtos, busca, filtros e carrinho |
| 3 — Backend | Endpoints PHP, validações e regras de negócio |
| 4 — Persistência | Integração opcional com MySQL, contas e pedidos |
| 5 — Finalização | Acessibilidade, segurança, testes e publicação |

## 🤝 Como contribuir

Contribuições, sugestões e correções são bem-vindas!

1. Abra uma [issue](https://github.com/landrad221/gamersells/issues) para descrever a melhoria ou o problema.
2. Faça um fork do repositório e crie uma branch com um nome descritivo.
3. Implemente e teste suas alterações utilizando as tecnologias permitidas.
4. Envie um pull request explicando as mudanças realizadas.

**Importante:** não inclua senhas, chaves de API ou dados de clientes nos commits.

## 📄 Licença

Ainda não foi definida uma licença para o projeto. A disponibilidade pública do repositório não significa, por si só, autorização para reutilizar ou redistribuir seu código. Consulte a [documentação do GitHub sobre licenças](https://docs.github.com/pt/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository).

---

<div align="center">

**GamerSell — Eleve o nível do seu setup. 🎮**

Desenvolvido com HTML5, CSS3, JavaScript e PHP.

</div>
