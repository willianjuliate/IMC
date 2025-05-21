# 🧮 Calculadora de IMC (React)

Um projetinho simples em React que calcula o IMC (Índice de Massa Corporal) de uma pessoa com base no peso e altura informados. Ideal para estudos e para treinar os fundamentos de React com `useState`.


## 🚀 Funcionalidades

- Entrada de peso (kg)
- Entrada de altura (metros)
- Cálculo automático do IMC ao clicar em "Calcular"
- Exibição da categoria de IMC (Magreza, Normal, Sobrepeso, Obesidade...)

## 🛠️ Tecnologias Utilizadas

- [React](https://reactjs.org/)
- HTML + CSS
- Vite

## 📦 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/calculadora-imc-react.git
cd calculadora-imc-react
````

2. Instale as dependências:

```bash
npm install
```

3. Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

Abra `http://localhost:5173` no navegador.

## 🧠 Lógica do IMC

A fórmula usada é a clássica:

```
IMC = peso / (altura * altura)
```

### Tabela de Classificação (OMS):

| IMC            | Classificação   |
| -------------- | --------------- |
| Abaixo de 18.5 | Magreza         |
| 18.5 a 24.9    | Normal          |
| 25.0 a 29.9    | Sobrepeso       |
| 30.0 a 39.9    | Obesidade       |
| 40.0 ou mais   | Obesidade grave |

## 🧑‍💻 Autor

Feito com 💙 por Will

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

