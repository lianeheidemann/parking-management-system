# Sistema de Estacionamento com Controle de Veículos e Tarifas

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
