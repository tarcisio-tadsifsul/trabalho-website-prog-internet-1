## Fluxo de Trabalho / Planejamento

1. **Definição de Escopo e Requisitos**

Antes de desenhar telas, você precisa definir o "o que" e o "para quem". Você já tem ótimas opções de temas mapeadas nos seus arquivos de ideias.

[✓] **Escolha um tema definitivo que facilite a criação de no mínimo 5 páginas com sentido lógico.**

- _Tema escolhido: Website de Receitas_
- _Motivo: nesse tema é possível criar 5 páginas simples com todos o requisitos exigidos, como a tabela de informações nutricionais e o formulário de envio de receitas._

[✓] **Defina qual será a principal funcionalidade de cada página para não perder o foco do projeto individual.**

- _Página Inicial (Home): com destaque da semana, visão geral de categorias, barra de busca e categorias populares._
- _Página Receitas (Listagem): lista completa do catálogo de receitas._
- _Página Receita (Interna): apresenta a receita com foto do prato, video de preparo, áudio descrição, lista de ingredientes, Modo de preparo passo a passo e a tabela nutricional._
- _Página Sobre: conteúdo em texto e foto do autor_
- _Página Contato / Envie sua Receita: possui o formulário para os usuários enviarem receitas ou contato/dúvidas._

[✓] **Planeje em qual página fará sentido encaixar o formulário exigido.**

- _Formulário: adicionado na página de Contato / Envie sua Receita, com vários tipos de inputs: text (Nome da receita), file (Upload da foto do prato), number (Tempo de preparo), select (Categoria: Doce, Salgado) e textarea (Modo de preparo)_.

[✓] **Planeje em qual página a tabela obrigatória se encaixará de forma natural, como uma tabela de preços, cronograma ou lista de ingredientes.**

- _Tabelas: será desenvolvida na página Receita (Interna), como uma Tabela de Informação Nutricional (Calorias, Carboidratos, Proteínas) e uma tabela de Conversão de Medidas (Xícaras para Gramas)._

[✓] **Planeje como fará o menu de navegação exigido.**

- _Menu Sticky: menu de navegação fixo no topo com os links para as páginas usando a propriedade sticky. No mobile, menu hamburguer com aba lateral._

---

2. **Arquitetura de Informação**

Esta é a fase de listar o conteúdo antes de pensar na estética.

[] Crie um mapa do site listando as 5 páginas exatas que você estruturou (Home, Listagem, Interna, Sobre, Contato).
[] Liste quais informações em texto e quais imagens estarão em cada uma dessas páginas.
[] Defina a hierarquia de navegação e como o usuário vai transitar entre os links.

---

3. **Prototipação e Design (Wireframes)**

Aqui você traz a arquitetura para o visual usando o Figma, como você planejou no seu rascunho.

[✓] Desenhe a versão Mobile primeiro.
[✓] Desenhe a versão Desktop depois, adaptando o layout para aproveitar melhor o espaço.
[] Planeje visualmente onde fará sentido aplicar o CSS Grid e o Flexbox no layout.
[] Esboce o comportamento e o design do menu "Sticky" para a navegação.
[✓] Salve as imagens desses esboços (wireframes), pois elas serão muito úteis para compor uma seção dedicada a eles no seu relatório final.

---

4. **Preparação do Ambiente e Estrutura Inicial**

Agora começa a transição para a parte técnica, mas ainda sem estilizar e aplicando os conceitos básicos de HTML e CSS estudados.

[✓] Crie a estrutura de pastas do projeto para manter os arquivos organizados.
[✓] Crie os 5 arquivos HTML em branco, já linkando os arquivos CSS de estilo.
[] Escreva toda a estrutura HTML respeitando a semântica antes de aplicar qualquer classe visual.
[] Use tags semânticas como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` para organizar o conteúdo de cada página.
[] Adicione os elementos obrigatórios (menu de navegação, formulário, tabela) na estrutura HTML, mesmo que ainda estejam sem estilo.

---

5. **Estratégia de Desenvolvimento**

[] Com a estrutura semântica pronta, aplica-se a "tinta" no projeto.

[] Defina as variáveis CSS (cores, tipografia) se optar por usá-las, o que facilita muito a manutenção.

Lembrar: css/
style.css
reset.css

[] Construa o layout base de cada página utilizando Grid e Flexbox.
[] Aplique as media queries para garantir que o site se adapte corretamente à tela do celular e do desktop.

---

6. **Validação, Documentação e Entrega**

A etapa final de revisão de qualidade e preparação para a nota.

[] Revise o código para garantir que você entende toda a lógica, pois o uso de IA sem capacidade de explicação resultará em nota zero na apresentação.
[] Redija o relatório em formato ".pdf" descrevendo cada página da aplicação, o que faz, como faz e sua relação com as demais.
[] Estruture o documento com capa, sumário e elementos textuais.
[] Compacte a pasta do projeto ou prepare o link sem restrições de acesso e senhas no Github/Drive.

---
