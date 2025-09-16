# 🗺️ Projeto de Cercas Interativas com Leaflet

Este projeto é uma aplicação web interativa para criação, edição e visualização de **cercas geográficas** em mapas. Ele foi desenvolvido com foco em simplicidade, usabilidade e flexibilidade, utilizando a biblioteca [Leaflet.js](https://leafletjs.com/) para renderização de mapas.

## 🚀 Funcionalidades

- Criação de múltiplos projetos com cercas internas (vermelhas) e externas (amarelas)
- Edição manual de pontos com marcadores arrastáveis
- Importação de arquivos `.kml` para cercas
- Medição de distâncias entre pontos no mapa
- Cálculo automático de área das cercas
- Verificação se um ponto está dentro de uma cerca
- Centralização automática do mapa ao importar dados
- Caixa de status dinâmica que exibe o estado atual do sistema

## 📦 Tecnologias utilizadas

- HTML, CSS, JavaScript
- [Leaflet.js](https://leafletjs.com/)
- [Leaflet.GeometryUtil](https://github.com/makinacorpus/Leaflet.GeometryUtil)
- [leaflet-pip](https://github.com/mapbox/leaflet-pip) *(opcional para verificação de ponto interno)*

## 🌐 Acesse o projeto online

Você pode visualizar e testar o projeto diretamente pelo GitHub Pages:

👉 [https://jcradavelli.github.io/virtualFenceMaker] (https://jcradavelli.github.io/virtualFenceMaker)


## 📁 Como usar

1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` em seu navegador
3. Crie um projeto e comece a desenhar cercas ou importar arquivos `.kml`
4. Use os botões para medir distâncias, limpar medições ou exportar dados

## 📌 Observações

- O sistema usa coordenadas em formato decimal (latitude/longitude)
- A escala interna do projeto pode multiplicar coordenadas por 1.000.000 para exportação
- O projeto é totalmente client-side e não requer servidor

## 🧑‍💻 Autor

Desenvolvido por Júlio

---
