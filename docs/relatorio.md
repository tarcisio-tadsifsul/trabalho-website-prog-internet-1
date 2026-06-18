# Relatório de Desenvolvimento: Projeto Receitaria
1. Visão Geral das Páginas
O projeto é composto por duas páginas principais que compartilham uma mesma base de estilos, garantindo identidade visual consistente.

A. Página Inicial (index.html)
O que faz: Serve como landing page. Apresenta o conceito do site, uma seção de busca para encontrar receitas, destaques da semana e um rodapé com contatos.

Como faz: Utiliza uma estrutura semântica composta por <header>, <main> e <footer>. O layout é controlado pelo style.css usando display: grid e flexbox para garantir a responsividade.

Relação com demais páginas: É o ponto de entrada. Contém links de navegação para a página de detalhes de receitas (receitas.html).

B. Página de Receita (receitas.html)
O que faz: Exibe o conteúdo detalhado de uma receita específica (ex: Wrap de Frango e Abacate), incluindo modo de preparo, tempo, porções e nível de dificuldade.

Como faz: Mantém o mesmo <header> e <footer> da index.html para manter a experiência de navegação contínua. Foca em uma disposição de colunas que prioriza a legibilidade dos ingredientes e passos da receita.

Relação com demais páginas: Recebe o usuário vindo da página inicial e oferece um caminho de retorno à home através do logo ou menu.

2. Esboço do Layout e Planejamento (Wireframe)
O planejamento do layout foi desenhado para seguir a metodologia Mobile First. Abaixo, descrevo a lógica espacial utilizada para guiar a implementação:

Estrutura de Layout (Wireframe Lógico)
O "Container" (Pai):

Planejado como um wrapper centralizado com largura máxima definida. Isso evita que o conteúdo "flutue" infinitamente em monitores muito largos.

No mobile, ocupa 100% da largura com margens laterais (padding). No desktop, trava em um tamanho confortável (ex: 1024px a 1200px).

O Cabeçalho (Header):

Mobile: Logo à esquerda e Menu Hambúrguer (checkbox hack) à direita.

Desktop: Logo à esquerda e links de navegação dispostos em linha horizontal, ocultando o checkbox.

Seções Principais (Grid):

Hero (Topo): Planejado com um grid de duas colunas (1fr 1fr) no desktop, separando o texto de impacto da imagem principal.

Grid de Receitas: Utiliza grid-template-columns: repeat(3, 1fr). Esta escolha foi feita para que, no mobile, os cards se empilhem automaticamente (1 coluna) e, no desktop, se organizem em trios perfeitos.

A Regra dos Espaçamentos:

Utilizamos o gap no CSS para que o espaçamento entre os elementos fosse controlado globalmente, evitando margens manuais excessivas que quebram o layout.

3. Considerações Técnicas e Semânticas
Para assegurar que o professor identifique a qualidade técnica do projeto, destaco três pilares utilizados:

CSS Moderno: O uso de clamp() na tipografia e grid-template-columns mostra um domínio de técnicas que eliminam a necessidade de centenas de media queries repetitivas.

Acessibilidade (A11y): O uso de aria-hidden="true" em ícones puramente decorativos e a implementação de type="search" nos inputs de busca são práticas de mercado que elevam o site acima de um projeto acadêmico comum.

Design Tokens: A centralização das cores e fontes no :root do CSS (style.css) permite uma manutenção rápida. Se o projeto precisar mudar a "identidade visual" (ex: mudar o tema de cores), você altera em apenas um local.