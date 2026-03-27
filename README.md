# 🌱 Raiz Digital (P.I Sementes)

O **Raiz Digital** é um sistema web desenvolvido para o gerenciamento completo da logística e distribuição de sementes. Com uma interface moderna e intuitiva, a aplicação permite controlar desde o cadastro de fornecedores e armazéns até a entrega final aos agricultores, com forte ênfase na rastreabilidade e na transparência de dados públicos.

## 🚀 Funcionalidades

O sistema é dividido em módulos para facilitar a administração:

* **Painel de Controle (Início):** Dashboard central com indicadores de estoque total, sementes distribuídas, agricultores atendidos e entregas pendentes.
* **Cadastro:** Módulo para registro e gerenciamento de espécies de sementes, fornecedores parceiros, armazéns, municípios e dados dos agricultores.
* **Gestão de Estoque:** Controle detalhado dos lotes armazenados, acompanhamento de movimentações e alertas para lotes próximos ao vencimento.
* **Logística e Entregas:** Gestão das ordens de expedição (status pendente, em trânsito, entregue ou cancelada) e registro oficial de entregas realizadas.
* **Rastreabilidade:** Ferramenta de busca para consultar a origem e o histórico de um lote específico através de código.
* **Relatórios e Análises:** Segmentação de dados através de filtros de data, espécie e município, permitindo a visualização da distribuição temporal, entradas x saídas de estoque e relatórios de divergências.
* **Portal de Transparência:** Uma página dedicada a exibir o compromisso do programa, mostrando de forma pública o total distribuído, famílias beneficiadas e municípios alcançados.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído focando na leveza e no desempenho do frontend:

* **HTML5:** Estruturação semântica das páginas.
* **CSS3:** Estilização personalizada sem o uso de frameworks externos, utilizando variáveis (`:root`), Flexbox e animações (`@keyframes`).
* **JavaScript (Vanilla):** Scripts puros para gerenciar a interatividade, como a navegação fluida entre os links das abas dinâmicas (`.tab-link` e `.sub-tab-link`).
* **FontAwesome:** Utilização de biblioteca de ícones vetoriais para aprimoramento da interface gráfica.
* **Google Fonts:** Utilização da família tipográfica "Poppins".

## 📁 Estrutura de Arquivos

* `index.html` - Dashboard principal.
* `cadastro.html` - Módulo de gestão de pessoas, espécies e locais.
* `estoque.html` - Visão de lotes e movimentação de inventário.
* `logistica.html` - Status das ordens de transporte.
* `entregas.html` - Detalhamento das finalizações das ordens.
* `rastreabilidade.html` - Módulo de pesquisa aprofundada via lote.
* `relatorios.html` - Gráficos e dados analíticos customizáveis.
* `transparencia.html` - Painel de acesso público a estatísticas de entrega.
* `style.css` - Toda a folha de estilos contendo o tema "Raiz Digital" (cores predominantes verdes).
* `script.js` - Lógica de apresentação de componentes (Tabs e conteúdos ocultos).
* `logo.png` - Identidade visual do projeto.

## ⚙️ Como Executar o Projeto

Como o projeto é construído estritamente no frontend com tecnologias web padrão, não é necessária nenhuma instalação complexa:

1. Clone este repositório na sua máquina local:
   ```bash
   git clone [https://github.com/SEU_USUARIO/nome-do-repositorio.git](https://github.com/SEU_USUARIO/nome-do-repositorio.git)
