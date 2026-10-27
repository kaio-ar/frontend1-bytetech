# ByteTech — Loja de Informática

## 1. Descrição do projeto

O ByteTech é um projeto acadêmico de desenvolvimento frontend de uma loja fictícia de informática, criado como parte da disciplina de Frontend 1.

O site apresenta produtos de informática e tecnologia, páginas de cadastro e login de clientes, edição de perfil, catálogo de produtos com carrinho de compras e uma área administrativa com relatórios de clientes e compras.

O projeto foi desenvolvido utilizando HTML5 e CSS3, sem JavaScript ou frameworks.

## 2. Integrantes

* Kaio Ramos — desenvolvimento do projeto.

## 3. Tecnologias utilizadas

* HTML5: estrutura e conteúdo das páginas.
* CSS3: estilização, layout, responsividade e acessibilidade básica.

## 4. Estrutura de pastas

```text
projeto_loja/
├── index.html
├── cadastro.html
├── login.html
├── perfil.html
├── loja.html
├── relatorios.html
├── README.md
├── css/
│   ├── base.css
│   ├── layout.css
│   ├── componentes.css
│   ├── responsivo.css
│   └── relatorios.css
└── img/
    ├── ambiente-informatica.png
    └── espaco-tecnologia.png
```

## 5. Páginas do projeto

* **index.html:** página inicial, apresentação da loja, produtos e informações de contato.
* **cadastro.html:** formulário de cadastro de clientes.
* **login.html:** formulário de acesso à conta.
* **perfil.html:** edição dos dados do cliente e tabela de pedidos.
* **loja.html:** catálogo de produtos, filtros visuais, carrinho de compras e confirmação de compra.
* **relatorios.html:** área administrativa com relatórios de clientes e compras.

## 6. Organização dos arquivos CSS

* **base.css:** variáveis de cores, configurações gerais e estilos básicos.
* **layout.css:** cabeçalho, navegação, conteúdo principal e rodapé.
* **componentes.css:** estilos de cartões de produtos, botões, formulários e componentes da interface.
* **responsivo.css:** ajustes de layout para diferentes tamanhos de tela e menu hambúrguer.
* **relatorios.css:** estilos específicos dos relatórios e regras de impressão.

## 7. Como visualizar a confirmação de compra

A página `loja.html` possui um bloco de confirmação de compra que começa oculto pelo atributo HTML `hidden`.

Para visualizar essa mensagem:

1. Abra o arquivo `loja.html` no editor de código.
2. Localize o elemento com o identificador `confirmacao-compra`.
3. Remova o atributo `hidden` da abertura do elemento.
4. Salve o arquivo e abra ou atualize a página no navegador.

A mensagem de confirmação ficará visível, apresentando os dados demonstrativos da compra e o número de pedido de exemplo, conforme definido no HTML.

Para ocultar novamente a mensagem, basta adicionar o atributo `hidden` ao elemento.

## 8. Responsividade e acessibilidade

O projeto utiliza CSS para adaptar a apresentação das páginas a diferentes tamanhos de tela. A navegação inclui um menu hambúrguer implementado somente com HTML e CSS.

Também são utilizados elementos semânticos do HTML, textos alternativos para imagens, formulários com rótulos e estados visuais de foco para auxiliar a navegação.

## 9. Observações

Este projeto possui finalidade acadêmica e apresenta dados e operações demonstrativos. Como não utiliza JavaScript nem backend, os formulários, filtros e controles de compra não realizam processamento real de dados.
