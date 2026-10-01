# Guia rápido para defender o projeto

## Ideia geral

Este é um portfólio feito com **HTML e CSS**, sem JavaScript e sem bibliotecas externas. O HTML organiza o conteúdo e o CSS define cores, espaçamentos, colunas e adaptação para ecrãs pequenos.

## Perguntas que podem aparecer

### Por que usaste `header`, `main`, `section`, `article` e `footer`?

Usei elementos semânticos para deixar claro o papel de cada parte da página. Isso melhora a organização do código, a acessibilidade e a leitura por motores de busca.

### Para que serve o `id` das secções?

Cada `id` identifica uma secção. Os links do menu usam `href="#projects"`, por exemplo, para levar diretamente à secção de projetos.

### Por que usaste `class`?

A `class` permite aplicar o mesmo estilo a vários elementos ou identificar um tipo de elemento, como `.project-card` para os dois cartões de projetos.

### O que faz o `display: grid`?

O Grid organiza elementos em linhas e colunas. Foi usado para colocar, lado a lado, o texto e a fotografia, os interesses e os projetos.

### O que acontece no `@media`?

A regra `@media (max-width: 700px)` é usada quando o ecrã fica pequeno. As colunas passam para uma coluna única e o menu passa para várias linhas, tornando a página mais fácil de usar num telemóvel.

### Por que existe `box-sizing: border-box`?

Faz com que a largura e a altura incluam o `padding` e a borda. Assim é mais fácil controlar o tamanho dos elementos.

### O formulário envia mensagens de verdade?

Não. O formulário está montado visualmente e usa `action="#"`, mas ainda não tem um servidor para receber os dados. Para enviar mensagens seria necessário um back-end ou um serviço externo.

### Por que não usaste JavaScript?

O objetivo deste trabalho é praticar HTML e CSS básicos. A navegação por âncoras, a tabela, o formulário e a adaptação para telemóvel podem funcionar sem JavaScript.

## Decisões de simplificação

- Removi o menu baseado em `checkbox`, porque ele exigia uma técnica menos direta para uma disciplina introdutória.
- Removi classes que não eram usadas ou que repetiam regras existentes.
- Mantive a paleta de cores, os cartões, a tabela, o formulário e a adaptação para telemóvel.
- Mantive os links dos projetos e o conteúdo principal do portfólio.
- Agrupei as regras de responsividade numa estrutura menor e mais fácil de explicar.
