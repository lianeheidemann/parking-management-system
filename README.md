# Sistema de Estacionamento com Controle de Veículos e Tarifas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Projeto desenvolvido em **HTML, CSS e JavaScript puro**, simulando um sistema de estacionamento com cadastro de veículos, listagem, busca e cálculo automático de taxas com base no tempo estacionado.

---

## Funcionalidades

- Cadastro de veículos (placa, modelo e cor)
- Listagem de veículos estacionados
- Pesquisa de veículo por placa
- Cálculo automático de valor a pagar com base no tempo estacionado
- Sistema de taxas configuráveis:
  - Taxa por minuto
  - Taxa por hora
  - Taxa extra
- Atualização dinâmica das informações na tela

---

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

## Como o sistema funciona

O sistema armazena os veículos em um array JavaScript e registra automaticamente:
- Data de entrada
- Hora de entrada
- Minutos de entrada

Ao buscar um veículo, o sistema:
1. Calcula o tempo atual menos o tempo de entrada
2. Converte isso em horas e minutos
3. Aplica as taxas configuradas
4. Retorna o valor final a pagar

---

## Interface do Projeto

<img width="1438" height="1182" alt="1000312942" src="https://github.com/user-attachments/assets/b879099b-2346-4b4a-806f-15c776d21708" />
