# API Fatos de Gatos

<img src="https://catnets.com.au/cdn/shop/articles/Domestic-Shorthair.jpg?v=1663296992"  width=400 />

---

O **Cataas** (Cat as a Service) é um site divertido que oferece imagens aleatórias de gatos por meio de uma API. A ideia é bem simples e divertida: você faz uma solicitação para o site e ele retorna uma imagem de um gato, que pode ser personalizada com texto. A imagem é gerada com base nas solicitações feitas via API.

Note que no HTML temos uma function`onclick` nas imagens dos gatos, então ao clicar na imagem vamos conseguir utilizar outra API que está explicada abaixo.

---


A **CatFact API** (catfact.ninja) é uma API que fornece fatos interessantes sobre gatos. Você pode fazer uma solicitação HTTP para obter um fato aleatório sobre gatos em formato JSON. Isso é perfeito para adicionar curiosidades sobre gatos a seu site ou aplicativo!

---

A função **JavaScript fetch()** usa a função fetch para fazer uma requisição à API e obter um fato sobre gatos em formato JSON.Pegamos o arquivo JSON e extraimos seu dado com `.data`(o `.data` é onde o texto está no JSON,observer isso testando o link no navegador). 

Após isso o  fato é exibido no elemento `p` da página ao clicar nas imagens dos gatos.

---

[ryanoliveira466.github.io/apiGatos](https://ryanoliveira466.github.io/apiGatos/)


