# 💰 Simple Finance System

## 📚 About the Project

This is a **Simple Finance System** developed to **calculate incomes and expenses**, **categorize transactions**, and **analyze spending patterns** to understand where the most money is being spent.

The main goal of this project is to **practice Object-Oriented Programming (OOP)** in **Python**, with a special focus on using **Dataclasses** to simplify:

- Class constructors
- Attributes and methods
- Class instantiation
- Value calculations

This project is a personal study initiative and is not intended for production use.

## 🛠 Technologies Used

- [Python](https://www.python.org/) 3.x
- Dataclasses (Standard library module)

✏️ Key Features
Register and categorize incomes and expenses

Calculate total incomes, expenses, and balance

Identify where most money is being spent

Simple and clean object-oriented design using @dataclass

## 🎯 System Goals

- Add my incomes
- Add my expenses
- Categorize my incomes and expenses to understand where I spend the most
- Display my total balance
  
## 🧩 Classes

- **categoria.py**
  - Defines a `Categoria` class that represents a category for a transaction.
  - Each category simply stores a `name` (`nome`) to help organize transactions (e.g., salary, groceries, rent).

- **main.py**
  - Initializes predefined categories (such as Income, Fixed Bills, Travel, and Leisure).
  - Registers a few example transactions (both incomes and expenses) using these categories.
  - Calculates the total balance based on all transactions.
  - Displays the total balance.
 
- **transacao.py**
  - Defines the `Transacao` class, which represents a financial transaction (either an income or an expense).
  - Each transaction has:
    - A `descricao` (description) — describing the transaction.
    - A `valor` (amount) — positive for incomes, negative for expenses.
    - A `categoria` (category) — an instance of the `Categoria` class that groups the transaction.
  - The class includes an `exibir` method that prints the transaction details in a formatted way.

- **utilitarios.py**
  - Provides utility functions to manage categories and transactions.
  - **Global Lists**:
    - `LISTA_CATEGORIAS` — stores all created categories.
    - `LISTA_TRANSACOES` — stores all registered transactions.
  - **Functions**:
    - `cadastrar_categoria(nome)` — creates a new `Categoria` object, adds it to the category list, and returns it.
    - `cadastrar_transacao(descricao, valor, categoria)` — creates a new `Transacao` object, adds it to the transaction list, and returns it.
    - `saldo_total()` — calculates and returns the total balance by summing all transaction values.

  📬 If you need to get in touch, please reach out to: [contato.eduardo96@gmail.com](mailto:contato.eduardo96@gmail.com)
