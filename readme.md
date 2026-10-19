☕ Grão & Arte - Torrefação e Café Especial

Bem-vindo(a) ao repositório do projeto Grão & Arte!

Esta é uma página web (landing page) desenvolvida como projeto avaliativo para o curso do SENAI Henrique Lupo. O objetivo é simular o desenvolvimento front-end profissional para um cliente fictício do ramo de cafés especiais, focando em boas práticas de código, acessibilidade, organização e navegação fluida.

🎯 Objetivo do Projeto

O site da Grão & Arte foi criado para apresentar a marca, seus cafés de altíssima qualidade (pontuação acima de 85 pontos SCA), o processo de torra artesanal e seu clube de assinatura mensal.

A ideia é entregar uma experiência visual agradável, responsiva (que funciona bem no celular, tablet e computador) e simples de navegar.

🛠️ Tecnologias e Conceitos Aplicados

Para construir esta página, utilizei as seguintes tecnologias e técnicas:

HTML5 Semântico: Estruturação correta da página usando tags adequadas (como <header>, <main>, <section>, <details>, <footer>), garantindo melhor acessibilidade e SEO.

CSS3 Puro: Estilização organizada sem o uso de bibliotecas externas.

Metodologia BEM (Block Element Modifier): Padrão de organização para criar classes CSS limpas, fáceis de ler e sem conflitos.

Design Responsivo: Uso de Flexbox, Media Queries e unidades de medida relativas (rem, %, vh, vw) para que a página se adapte perfeitamente a qualquer tamanho de tela.

Google Fonts: Importação das famílias de fontes Merriweather (títulos) e Open Sans (textos gerais).

Interatividade e Recursos:

Menu superior fixo no topo da página.

Botão flutuante para contato direto via WhatsApp (integrado ao número oficial do SENAI Henrique Lupo).

Seção de Perguntas Frequentes (FAQ) interativa com as tags <details> e <summary>.

Animações leves e efeitos visuais ao passar o mouse (:hover).

📁 Organização de Arquivos (Arquitetura)

O projeto foi estruturado seguindo o princípio de separação de responsabilidades:

grao-e-arte/
├── index.html          # Estrutura principal da página (HTML5)
├── css/
│   └── style.css       # Estilos da aplicação e variáveis do Design System
├── assets/
│   └── images/         # Imagens e ícones utilizados no projeto
└── README.md           # Documentação do projeto


🚀 Como Visualizar/Executar o Projeto

Como este é um projeto estático (HTML e CSS), você não precisa instalar nenhuma dependência complexa para rodá-lo:

Clone o repositório:

git clone https://github.com//https://github.com/joaopneto310/GraoeArte.git


Abra o arquivo no navegador:

Basta navegar até a pasta do projeto e dar um duplo clique no arquivo index.html.

Ou utilize a extensão Live Server no editor VS Code para abrir o projeto em um servidor local.

💡 Principais Desafios Técnicos e Aprendizados

Durante o desenvolvimento deste projeto, os principais aprendizados e desafios foram:

Uso Rigoroso da Escala REM e Variáveis CSS: Ajustar a escala base no elemento raiz (html) e garantir que todos os espaçamentos e fontes fossem dinâmicos usando rem.

Arquitetura CSS com BEM: Manter a disciplina na criação dos nomes das classes CSS para evitar repetição de código e manter a organização.

Compensação do Header Fixo: Ajustar o alinhamento da rolagem da página para que o menu superior fixo não cobrisse o título das seções ao clicar nos links de navegação.

Responsividade Fluida: Criar pontos de quebra (breakpoints) eficientes para que os cards do catálogo e do clube de assinatura fiquem bem apresentáveis em telas pequenas.

📩 Contato

Desenvolvido por João Paulo Mendonça Neto como atividade avaliativa do SENAI.

Fique à vontade para explorar o código, enviar sugestões ou entrar em contato!
