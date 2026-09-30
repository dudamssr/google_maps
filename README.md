# Google Maps Flutter

Em aplicações que trabalham com localização, mapas interativos são recursos importantes para identificar pontos geográficos e facilitar a visualização de diferentes posições.

O Google Maps Flutter é uma aplicação demonstrativa desenvolvida em Flutter que integra o Google Maps à interface da aplicação, permitindo visualizar um ponto de origem e selecionar um ponto de destino diretamente no mapa.

---

## Situação-Problema

A aplicação apresenta um mapa interativo com uma localização inicial definida. A partir da interação do usuário com o mapa, é possível selecionar outro ponto e obter automaticamente suas coordenadas geográficas.

Dessa forma, o projeto demonstra como trabalhar com eventos de toque, latitude, longitude e marcadores utilizando o pacote `google_maps_flutter`.

### Principais Objetivos Alcançados:

- Integrar e renderizar o widget `GoogleMap`;
- Definir uma localização inicial no mapa;
- Exibir um marcador para o ponto de origem;
- Permitir a seleção de um novo ponto através do mapa;
- Capturar as coordenadas de latitude e longitude;
- Criar um marcador para o ponto selecionado;
- Atualizar as informações exibidas na tela em tempo real;
- Trabalhar com eventos de interação utilizando `onTap`;
- Utilizar `setState` para atualização dos dados da aplicação.

---

## Prints

<img width="1221" height="906" alt="Google Maps Flutter" src="COLOQUE_AQUI_O_LINK_DA_IMAGEM" />

---

## Tecnologias Utilizadas

- **Flutter SDK**
- **Dart**
- **`google_maps_flutter`**
- **Google Maps API**
- **Flutter Web**

---

## Funcionamento

Ao iniciar a aplicação, o mapa é carregado com uma localização inicial definida no código.

O ponto inicial é representado por um marcador e suas coordenadas são apresentadas na parte superior da tela.

Quando o usuário clica em qualquer local do mapa, a aplicação captura a posição selecionada e atualiza as informações exibidas.

O novo ponto passa a ser representado por um segundo marcador, indicando o destino escolhido.

---
