#  Conversor de Moedas em Java

##  Autor
Murillo Freire Espírito Santo  

---

##  Descrição do Projeto

Este projeto consiste em um Conversor de Moedas desenvolvido em Java, que permite ao usuário converter valores entre diferentes moedas utilizando dados atualizados em tempo real por meio de uma API externa.

O sistema funciona via terminal e realiza requisições HTTP para buscar as taxas de câmbio mais recentes, realizando o cálculo automaticamente com base na moeda escolhida.

---

##  Funcionalidades

O programa permite as seguintes conversões:

1. Dólar → Iene Japonês   
2. Iene Japonês → Dólar  
3. Dólar → Dólar Australiano
4. Dólar Australiano → Dólar  
5. Dólar  → Euro  
6. Euro  → Real Brasileiro  
7. Sair do programa  

---

##  Tecnologias Utilizadas

- Java 17+
- IntelliJ IDEA
- Biblioteca Gson (para manipulação de JSON)
- HttpClient (java.net.http)
- ExchangeRate API

---

##  API Utilizada

O projeto utiliza a API pública ExchangeRate API:

https://www.exchangerate-api.com/

---

## 🔎 Funcionamento do Sistema

1. O usuário escolhe uma opção no menu.
2. O sistema solicita o valor a ser convertido.
3. A classe `ConsultaMoeda` realiza uma requisição HTTP para a API.
4. O retorno da API (em formato JSON) é convertido em objeto utilizando a biblioteca Gson.
5. A taxa correspondente à moeda de destino é extraída.
6. O valor convertido é calculado e exibido na tela.

---


