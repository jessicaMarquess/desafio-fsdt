# Desafio inaugural - FSDT

Este projeto consiste em um formulário que envia um JSON contendo informações sobre os integrantes e a história da equipe. A implementação utiliza **HTML, CSS e JavaScript**.

## 👥 Integrantes
- **Giovane Ferreira da Silva** - RM361394  
- **Guilherme Mendes Carvalho** - RM363063  
- **Jessica Marques** - RM364114  
- **Lucas Gomes** - RM364231  
- **Thatyanne Corrêa Gomes** - RM363253  

---

## 📌 Endpoint: Criar Contato

### ➤ Método: `POST`
**URL:**  
`https://fsdt-contact.onrender.com/contact`

### 📤 Corpo da Requisição (JSON):
```json
{
    "names": [
        "Giovane",
        "Guilherme",
        "Jessica",
        "Lucas",
        "Thatyanne"
    ],
    "message": "Oi, somos os ganhadores do desafio hehe"
}
