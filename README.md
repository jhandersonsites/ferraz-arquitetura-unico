# Ferraz Arquitetura — site modelo para escritórios de arquitetura

Site de portfólio e captação por WhatsApp para escritórios de arquitetura e interiores, apresentado com uma marca **fictícia** (Ferraz Arquitetura, Campinas/SP). Nome, endereço, telefone, e-mail, números, depoimentos e projetos são demonstrativos e devem ser trocados pelos dados reais de cada escritório.

## Como ver

Abra `index.html` (o mesmo conteúdo também está em `ferraz-arquitetura.dc.html`, mantido para links antigos) em um navegador atual, com internet. O arquivo é único: já inclui o motor que monta a página e o componente de imagens. A página busca o React, as fontes do Google e as fotos do Unsplash pela internet.

## O que tem

- Topo com foto que reage ao mouse (WebGL), título que se escreve e relógio solar com a posição real do sol.
- Fundo de luz natural animada nas seções claras, parágrafos que acendem palavra por palavra, linhas que se desenham ao rolar e fotos que derivam dentro dos quadros.
- Filtro de projetos, ficha técnica de cada obra, processo, depoimentos, dúvidas e formulário que monta a mensagem e abre o WhatsApp.
- Adaptado para celular, tablet e desktop. Respeita "reduzir movimento" e economia de dados; os efeitos mais pesados só ligam em computador com mouse.

## Créditos

As fotos são do Unsplash e levam crédito dentro da própria página.
## Leitura sem JavaScript

O texto do site (seções, projetos, serviços, etapas, depoimentos e dúvidas) também está dentro de `<noscript>`, e o título, a descrição e a foto de prévia (Open Graph) ficam no `<head>`, para leitores automáticos, buscadores simples e prévias de link no WhatsApp.
