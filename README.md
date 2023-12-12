# Inventory Management System

The Inventory Management System is a Java-based application that provides a user-friendly interface for managing products, categories, purchases, and sales.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Key Components](#key-components)
- [Visual Representation](#visual-representation)
- [Contributing](#contributing)
- [License](#license)

## Features

1. **Product Management:** Add new products and assign them to categories.
2. **Purchase:** Record product purchases, updating the inventory accordingly.
3. **Sales:** Sell products, generate bills, and receive alerts for low product quantities.
4. **Category Management:** Add, delete, and assign categories to products.
5. **Visual Representation:** View the quantity of items remaining in the inventory through a bar chart.

## Getting Started

### Prerequisites

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Eclipse IDE](https://www.eclipse.org/downloads/) or any Java-compatible IDE

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>

2. Open the project in your preferred Java IDE.
3. Build and run the application.

## Usage

1. Launch the application.
2. Use the tabs to navigate through different sections (e.g., Purchase, Inventory & Sales).
3. Add, delete, or modify products and categories as needed.
4. Make purchases, sell products, and generate bills.

## Key Components

- **DatabaseConnection.java:** Handles database operations, including creating the schema, inserting products and categories, and retrieving data.

- **InventoryManagement.java:** Main class for the GUI, which includes tabs for Purchase, Inventory & Sales. Provides functionalities for purchasing, selling, and managing products.

- **AddProductWindow.java:** A separate window for adding new products.

## Visual Representation

The system includes a bar chart to visually represent the quantity of items remaining in the inventory.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

