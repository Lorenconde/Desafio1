# 🧩 Desafio 1 – Classificador de Nível de Herói

Este projeto foi desenvolvido como parte de um desafio de **lógica de programação em JavaScript** da plataforma **Digital Innovation One (DIO)**.

O objetivo é criar um programa capaz de classificar o **nível de um herói** com base na quantidade de **XP (experiência)** informada.

---

## 🎯 Objetivo do Desafio

Criar uma aplicação simples que:

* Defina o nome do herói
* Defina a quantidade de XP
* Classifique o nível do herói
* Exiba o resultado no terminal

### 📌 Saída esperada

```bash
O Herói de nome Superman está no nível de Prata
```

---

## 🧠 Tabela de Classificação

| Faixa de XP     | Nível      |
| --------------- | ---------- |
| menor que 1000  | Ferro      |
| 1001 – 2000     | Bronze     |
| 2001 – 5000     | Prata      |
| 5001 – 7000     | Ouro       |
| 7001 – 8000     | Platina    |
| 8001 – 9000     | Ascendente |
| 9001 – 10000    | Imortal    |
| maior que 10000 | Radiante   |

---

## 💻 Código do Projeto

```javascript
const nome = "Superman";
const xp = 3500;

let nivel = "";

if (xp < 1000) {
    nivel = "Ferro";
} else if (xp <= 2000) {
    nivel = "Bronze";
} else if (xp <= 5000) {
    nivel = "Prata";
} else if (xp <= 7000) {
    nivel = "Ouro";
} else if (xp <= 8000) {
    nivel = "Platina";
} else if (xp <= 9000) {
    nivel = "Ascendente";
} else if (xp <= 10000) {
    nivel = "Imortal";
} else {
    nivel = "Radiante";
}

console.log(`O Herói de nome ${nome} está no nível de ${nivel}`);
```

---

## 🚀 Como executar o projeto

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/Lorenconde/nome-do-repositorio.git
```

### 2️⃣ Entre na pasta do projeto

```bash
cd nome-do-repositorio
```

### 3️⃣ Execute o arquivo

```bash
node index.js
```

---

## 🛠 Tecnologias utilizadas

* JavaScript
* Node.js

---

## 📚 Conceitos praticados

Durante este desafio foram utilizados:

✔ Variáveis (`const` e `let`)
✔ Estruturas condicionais (`if / else if`)
✔ Operadores relacionais
✔ Template String
✔ Organização lógica

---

## 📈 Melhorias futuras

Sugestões de evolução do projeto:

* Receber dados via input do usuário
* Criar versão com `switch`
* Criar interface web com HTML + CSS
* Transformar em função reutilizável
* Publicar versão interativa

---

## 👨‍💻 Autor

Desenvolvido por **Loren Conde**

Projeto educacional para prática de **JavaScript e lógica de programação**
