# Protótipo Mobile - Organização de Estilos com BEM

## Identificação do Grupo
* Guilherme Diego Sanches

## Descrição da Aplicação
Este projeto contém a organização visual inicial de uma aplicação que será desenvolvida em React. O foco desta etapa é a construção das telas mobile em baixa fidelidade, a identificação dos elementos visuais recorrentes (componentes) e a estruturação inicial dos estilos CSS utilizando a metodologia BEM (Block, Element, Modifier).

## Relação das Telas Elaboradas
O projeto contempla as 14 telas previstas para o fluxo de navegação mobile, salvas como imagem no repositório:

- Tela 01: Início
- Tela 02: Categoria 
- Tela 03: Destaques 
- Tela 04: Assinar Newsletter 
- Tela 05: Administração de Categorias 
- Tela 06: Criar Post 
- Tela 07: Escolhas do Editor 
- Tela 08: Usuários 
- Tela 09: Fila de revisão 
- Tela 10: Fila de comentários 
- Tela 11: Resultados de Busca 
- Tela 12: Entrar / Login 
- Tela 13: Criar Conta 
- Tela 14: Perfil do Usuário

## Identificação de Componentes e Variações

| Componente | Onde aparece | Variações |
| :--- | :--- | :--- |
| **Card** | Início, Categoria, Destaques, Busca | padrão, compacto, destaque |
| **Button** | Login, Cadastro, Newsletter, Administração | primary, secondary, disabled |
| **Navigation** | Todas as telas da aplicação | principal |
| **Form** | Login, Cadastro, Newsletter, Criar Post | login, cadastro, newsletter |

## Organização dos Arquivos CSS
Os estilos foram isolados na pasta `/css` de acordo com a responsabilidade de cada componente para facilitar a futura componentização em React. A nomenclatura interna segue estritamente o padrão BEM:
* `variables.css`: Variáveis globais do projeto.
* `button.css`: Regras do bloco de botões e seus modificadores.
* `card.css`: Estrutura base dos cards e elementos internos.
* `form.css`: Estruturas de formulário e inputs.
* `navigation.css`: Estrutura de menus e barras de navegação.

## Referência das Telas Produzidas
As imagens das telas, criadas no FIGMA, encontram-se disponíveis no diretório `/wireframes` deste repositório.