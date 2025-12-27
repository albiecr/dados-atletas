<div align="center">
  <img width="500" height="137" alt="Image" src="https://github.com/user-attachments/assets/9203cfa7-140c-45ea-bd53-217bdd1bd230" />
</div>


# 🏋️‍♂️ Projeto: Dados dos Atletas

Este projeto foi desenvolvido como parte do desafio de certificação de lógica de programação. O objetivo é aplicar conceitos de **Orientação a Objetos** em JavaScript para gerenciar dados de atletas em uma competição.

## 📋 Funcionalidades

A aplicação utiliza uma classe `Atleta` para:
1.  **Calcular a Categoria**: Baseada na idade do atleta (Infantil, Juvenil, Intermediário ou Adulto).
2.  **Calcular o IMC**: Índice de Massa Corporal baseada em peso e altura.
3.  **Calcular a Média Válida**: Utiliza a regra de eliminação da maior e menor nota (mesma lógica do projeto anterior).

## 🚀 Tecnologias Utilizadas

* JavaScript (Classes e Métodos)

## 💻 Estrutura do Código

A classe `Atleta` recebe os dados no construtor e possui métodos específicos para processar as informações:

```javascript
// Exemplo de Instância
const atleta = new Atleta("Cesar Abascal", 30, 80, 1.70, [10, 9.34, 8.42, 10, 7.88]);
```

### Regras de Categoria
* **Infantil**: 9 a 11 anos
* **Juvenil**: 12 e 13 anos
* **Intermediário**: 14 e 15 anos
* **Adulto**: 16 a 30 anos
* **Sem categoria**: Demais idades

## 🏃‍♂️ Como Executar

Você pode rodar este projeto de duas formas:

### 1. Pelo Terminal (Node.js)
Certifique-se de ter o Node.js instalado e execute:

```bash
node dados-atletas.js
```

### 2. Pelo Navegador
1. Copie o código do arquivo `dados-atletas.js`.
2. Abra o console do seu navegador (F12).
3. Cole o código e aperte **Enter**.

---
Desenvolvido por **[Albertina Rodrigues]** 🚀
