# ToDoList responsível

## Sobre o projeto:
 Este é um projeto simples, com o intúito de fazer uma página HTML com lógica em JavaScript e estilização via Tailwind Play CND. O projeto não armazena nenhuma das tarefas, metas ou listas no armazenamento interno do seu dispositivo, apenas armazenamento in-memory storage.

## Motivações:

- ### Indagação principal:

    Durante uma aula de Programação de Aplicativos Mobile, nosso professor fez uma breve revisão sobre JavaScript, comentando sobre o básico da linguagem, e a importância das boas práticas, como o  "CleanCode", e em seguida, falou mais sobre a manipulação DOM (Document Object Model) e sobre propriedades e metodos.
    Foi então que descobri que existem muito mais formas e meios de interagir com o HTML usando DOM, e mais maneiras de usar as propridades.

- ### Ganhar aplitude sobre o tema:

    Pretendo ampliar meus próprios conhecimentos, estudando mais a fundo os meios possíveis de se manipular o HTML por meio do DOM e de propriedades do JS.

## Desafios para este projeto.

- ### Não usar IA para nada:

    A Inteligência Artificial é uma ferramenta,mas muitas vezes pode ser um problema no aprendizado. pois ela tira a capacidade de procurar erros no código, e de aprender a resolver os erros sozinho. Por este motivo, neste projeto serei totalmente aparte de IA para qualquer coisa.

- ### Consultar somente fontes renomadas.

    Usar somente documentação sobre o assunto, sem pesquisa otimizada com IA, ou vídeos curtos, buscando somente nas fontes como:
    - [MDN Web Docs - JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
    - [W3Schools - JavaScript](https://www.w3schools.com/js/)
    - [JavaScript.info](https://javascript.info/) 

- ### Responsividade.

    Usando o framework [TailwindCSS CDN](https://tailwindcss.com/docs/installation/play-cdn) por meio do Play CDN como estilização da página, neste projeto irei usar os Breakpoints para deixar esta página responsiva para todos os dispositivos,dês do mobile, tablets e desktops.

## Instalação e execução.

### Pré-requisitos.

- Git
- Um navegador web moderno 
- Um editor de código (Recomendado: Visual Studio Code)

### Passo a passo

1. Em seu dispositivo, crie uma pasta para que o projeto seja armazenado na mesma.
2. Abra o terminal GitBash.
3. Execute o comando abaixo para clonar o repositório.
```bash
git clone https://gitlab.com/dev.marcos.h.reis/2j-solo-todolist-2026-marcos.git 
```
4. acesse a pasta do repositório com o comando:
```bash
cd 2j-solo-todolist-2026-marcos
```
5. Abra o projeto no editor de código:
```bash
code .
```
6. Com o projeto aberto, procure pelo arquivo `index.html` e abra-o no navegador.


## Funcionalidades:

- CRUD

    - Create - O usuário pode criar:

        1. Tarefas. 
        2. listas.
        3. Itens das listas.
        4. Metas.
        5. Etapas para as metas.

    - Read - O usuário pode visualizar os itens criados, filtrando-os por:

        1. Todos.
        2. Concluidos.
        3. Pendentes.
        4. Listas.
        5. Metas.

    - Update - O usuário pode atualizar os itens criados, alternando:
        
        1. Nome das tarefas, metas ou listas.
        2. Alternar status de tarefas (pendente/concluído).
        3. Progresso das metas.
        4. Etapas das metas.
        5. Adicionar mais itens à lista.


    - Delete - O usuário pode deletar os itens criados, como:
        1. Tarefas.
        2. Listas. 
        3. Itens de lista
        4. Metas.
        5. Etapas das metas.

## Limitações do projeto:

- Os dados não têm permanência alguma em seu dispositívo.
- Toda e qualquer informação é armazenada in-memory storage.
- Quaisquer itens criados desaparecerão ao reregar a página.

## Melhorias futuras:

- Implementar armazenamento LocalStorage
- Implementar backend com API.
- Criar Dark Mode.


## Utilizados neste projeto:

 ### Ferramentas

- [Visual Studio Code](https://code.visualstudio.com/) editor de código.
- [GitLab](https://gitlab.com/) Plataforma de versionamento e hospedagem de código.
- [Git](https://git-scm.com/) Sistema de versionamento.

### Linguagens 

- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) como linguagem principal de programação
- [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML) como linguagem de estruturação de páginas web.

### Frameworks e bibliotecas

- [TailWindCSS](https://tailwindcss.com/) Framework CSS para esilização
- [Lucide](https://lucide.dev/) Para os ícones da página


## Autor

Marcos Henrique da Silva Reis

LinkedIn:
https://www.linkedin.com/in/dev-marcos-dev-reis

GitLab:
https://gitlab.com/dev.marcos.h.reis

GitHub:
https://github.com/devmarcoshreis-jpg

## Licença

Este projeto está sob a licença MIT.