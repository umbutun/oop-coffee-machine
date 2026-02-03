# ☕ Coffee Machine (OOP Version)

A command-line coffee machine simulator demonstrating Object-Oriented Programming principles — with resource management, payment processing, and drink making.

---

## Features

- **Three Drinks:** Espresso, Latte, Cappuccino with different recipes
- **Resource Management:** Tracks water, milk, coffee, and money
- **Payment System:** Accepts coins, calculates change
- **Reports:** Check current resource levels
- **OOP Architecture:** Separate classes for Menu, CoffeeMaker, and MoneyMachine

---

## Menu

| Drink | Water | Milk | Coffee | Price |
|-------|-------|------|--------|-------|
| Espresso | 50ml | 0ml | 18g | $1.50 |
| Latte | 200ml | 150ml | 24g | $2.50 |
| Cappuccino | 250ml | 100ml | 24g | $3.00 |

---

## Commands

| Command | Action |
|---------|--------|
| `espresso` | Order an espresso |
| `latte` | Order a latte |
| `cappuccino` | Order a cappuccino |
| `report` | Show resource levels |
| `off` | Turn off machine |

---

## Sample Interaction

```
What would you like? (espresso/latte/cappuccino): latte
Please insert coins.
How many quarters?: 10
How many dimes?: 0
How many nickels?: 0
How many pennies?: 0
Here is $0.50 in change.
Here is your latte ☕. Enjoy!
```

---

## Project Structure

```
oop-coffee-machine/
├── main.py           # Main program loop
├── menu.py           # Menu and MenuItem classes
├── coffee_maker.py   # CoffeeMaker class (resources, making drinks)
└── money_machine.py  # MoneyMachine class (payments, profits)
```

---

## OOP Concepts Demonstrated

- **Encapsulation:** Each class manages its own data
- **Abstraction:** Simple interface hides complex logic
- **Classes & Objects:** Menu items, machines as objects
- **Methods:** Behaviors like `make_coffee()`, `process_coins()`

---

## Tech Stack

- **Python 3**
- **OOP Principles**

---

## Run Locally

```bash
git clone https://github.com/umbutun/oop-coffee-machine.git
cd oop-coffee-machine
python main.py
```

---

## What I Learned

- Refactoring procedural code to OOP
- Designing classes with single responsibilities
- Managing state across multiple objects
- Creating clean, reusable code architecture

---

## Related

Also see: [Coffee Machine (Procedural)](https://github.com/umbutun/coffee-machine) — Same project, procedural style

---

## Part Of

🐍 [100 Days of Code — Python Projects](https://github.com/umbutun/python-100-days-of-code)

---

## License

[MIT License](LICENSE)
