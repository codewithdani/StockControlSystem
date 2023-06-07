# Stock Control System

The Stock Control System is a web application designed to manage stock items, purchases, and sales within a store or warehouse. 
It provides functionality to track and update stock levels, record purchase transactions, and manage sales activities.

## Features

- Stock Item Management: Add, update, and delete stock items. Each stock item includes details such as item ID, item name, price, quantity, and store.

- Purchase Management: Record purchase transactions by specifying the stock item, quantity, and purchase date. This helps in maintaining a purchase history 
- and tracking stock inventory changes.

- Sale Management: Manage sales activities by recording sale transactions, including the stock item, quantity, and sale date. 
- This allows for monitoring sales performance and tracking available stock.

- Reporting: Generate reports on stock items, purchases, and sales. These reports provide insights into stock levels, transaction history, and sales performance.

## Technologies Used

The Stock Control System is built using the following technologies:

- Django: A Python web framework used for backend development.

- HTML: Used for creating the web pages and user interface.

- CSS: Used for styling the web pages and enhancing the visual appearance.

- PostgreSQL: A relational database management system used for storing and managing data.

## Installation and Setup

1. Clone the repository:
git clone <repository-url>

2. Install the required dependencies:
pip install -r requirements.txt

3. Configure the database:
- Create a PostgreSQL database for the project.
- Update the database configuration in the `settings.py` file.

4. Apply database migrations:
python manage.py migrate

5. Start the development server:
python manage.py runserver

6. Access the Stock Control System:
Open a web browser and navigate to `http://localhost:8000/`.

## Usage

- Visit the web application using the provided URL.
- Use the user interface to navigate through the different sections: Stock Items, Purchases, Sales.
- Perform actions such as adding new stock items, recording purchases, and managing sales.
- Generate reports to obtain insights into the stock inventory and sales activities.

## Contributions

Contributions to the Stock Control System are welcome. If you have any suggestions, bug reports, or feature requests, 
  please create an issue or submit a pull request.

## License

The Stock Control System is released under the [MIT License](LICENSE).
