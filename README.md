# CESAE Digital Lisboa — Grupo 2

## Sobre o projeto

Este website foi desenvolvido pelo Grupo 2, no âmbito do módulo de Programação Web Client-Side do curso de Software Developer do CESAE Digital Lisboa.

O objetivo foi criar um site responsivo, inspirado no CESAE Digital, para pôr em prática o que aprendemos nas aulas de HTML, CSS, Bootstrap e Git/GitHub.

O projeto foi realizado em grupo e utilizámos branches e Pull Requests para juntar e rever as alterações.

## Páginas do website

- **Início (`index.html`)** — Página inicial com secções de impacto institucional, cursos em destaque (sendo 
    a totalidade dos   mesmo apresentada na respectiva pagina), listagem de parceiros-chave e chamada para acção, respectivamente.

- **Cursos (`pages/cursos.html`)** — mostra cartões com informações sobre cursos e opções de filtros (modalidade, 
    preço e área  de formação), ordenação e listagem de formaç~oes.

- **Parceiros (`pages/parceiros.html`)** — apresenta entidades parceiras e certificações (Sage, AEP, Pearson VUE,
     Cisco, AWS, Autodesk, entre outros).

- **Contactos (`pages/contactos.html`)** — reúne os contactos, a localização e um formulário de mensagem.
- **Área Reservada (`pages/login.html`)** — informa que o acesso por login ainda não está disponível nesta versão do projeto.
- **Design Responsivo** - as paginas apresentam design totalmente responsivo.
-**Acessibilidade** - acessibilidade basica(aria-labels, foco visivel, etc.)

## Tecnologias utilizadas

- **HTML5** — estrutura das páginas.
- **CSS3** — estilos e apresentação visual.
- **Bootstrap 5** — layout responsivo e alguns componentes.
- **Bootstrap Icons e Google Fonts (Inter)** — ícones e tipografia.
- **Git e GitHub** — controlo de versões e trabalho em equipa.
- **GitHub Pages** — publicação do website.

## Organização dos ficheiros

- `index.html` — página inicial.
- `pages/` — páginas de Cursos, Parceiros, Contactos e Área Reservada.
- `css/` — estilos gerais e estilos específicos das páginas.
- `images/` — imagens dos cursos, logótipos, ícones e imagens do rodapé.
- `README.md` — informações sobre o projeto.

## Estrutura do Projecto

/
|- index.html
|-- pages/
|   |--cursos.html    
|   |--parceiros.htm
|   |--contactos.html
|   |--login.html
|
|-- css/
|   |--style.css                      *# Estilos globais*
|   |--index.css                      
|   |-- cursos.css
|   |--parceiros.css
|   |--contactos.css
|
|-- images/
|   |--icons/
|   |-- cursos/
|   |--parceiros/
|   |--footer/


## Como Visualizar o Projecto

O website pode ser consultado através do GitHub Pages:

**[Ver website](https://danielatorresalmeida.github.io/cesae-lisboa-grupo2/)**

**Visualizaçao por Servidor Local** - Para o abrir localmente, basta descarregar ou clonar o repositório, abrir a pasta no Visual Studio Code e visualizar o ficheiro `index.html` no navegador, por exemplo com a extensão Live Server.

## Funcionalidades ainda não implementadas

Este é um projeto académico e algumas funcionalidades são apenas demonstrativas:

- Os filtros e a ordenação dos cursos aparecem na página, mas ainda não filtram nem ordenam os resultados (não foram
     implementadas lógicas JavaScript de filtragem real).
- Os botões «Ver curso» e «Carregar mais cursos» ainda não têm as respetivas funcionalidades.
- O formulário de Contactos utiliza `mailto:`, pelo que depende da aplicação de email configurada no dispositivo.
- A Área Reservada apresenta uma mensagem informativa; não existe autenticação de utilizadores.

## Elementos do grupo

- Abacelar
- Daniela
- Lucas
- Roberta

---

### CESAE Digital Lisboa | Software Developer | Grupo 2 | 2026

*Este é um projeto académico e não o website oficial do CESAE Digital. Todos os direitos relacionados com a marca e conteúdos oficiais do CESAE Digital pertencem à respectiva entidade.
