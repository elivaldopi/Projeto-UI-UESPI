# Projeto-UI Neto.IA-UESPI
UI projeto Neto.IA -Projeto Integrador UESPI

# Neto.IA (Netinho.io)

## Sobre o Projeto
O Neto.IA é um projeto integrador projetado para ser o guia interativo definitivo do litoral do Estado do Piauí. O objetivo principal da aplicação é apresentar informações precisas e em tempo real sobre as condições climáticas, de vento e de marés das praias piauienses (como Barra Grande, Luís Correia, Macapá, entre outras). 

A interface moderna apresenta uma estética "liquid glass", enquanto a interatividade é enriquecida por um assistente virtual em formato de chatbot (o mascote Caju), o qual esclarece dúvidas sobre hospedagem, rotas, gastronomia e passeios locais, como a visitação ao Santuário dos Peixes-Boi e o Delta do Parnaíba.

## Stacks Utilizadas
- **HTML5:** Estruturação semântica e acessibilidade da página.
- **CSS3:** Efeitos visuais avançados, responsividade, paleta de cores customizada e custom properties (tokens).
- **JavaScript (Vanilla):** 
  - Consumo assíncrono e tratamento de dados de APIs externas (Open-Meteo).
  - Algoritmo harmônico estimativo para dados de maré.
  - Motor de processamento de linguagem natural simplificado para identificar as intenções do usuário no chat.
  - Manipulação de animações de canvas e SVGs dinâmicos de acordo com parâmetros ambientais reais (como força e direção do vento).

## Como Executar
Basta executar o arquivo `index.html` em um navegador web. Em um ambiente de produção, é recomendado utilizar um servidor web ou infraestrutura em nuvem para orquestrar as requisições às APIs com maior controle de segurança.
