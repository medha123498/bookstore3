Screenshots

<p align="center">
  <img src= ![WhatsApp Image 2025-05-26 at 06 51 55_52b81b04](https://github.com/user-attachments/assets/96a61160-6756-4557-bf6c-ef221877257f)

<img src=![WhatsApp Image 2025-05-26 at 06 52 48_f1d7b1d9](https://github.com/user-attachments/assets/862a491b-c524-43f4-bbc6-0aba47b9077d)

<img src=![WhatsApp Image 2025-05-26 at 06 53 36_a06bbc10](https://github.com/user-attachments/assets/0c9a41ac-91f6-4d78-8bfe-10e3fa709541)

</p>

<p align="center">
  <img src=![WhatsApp Image 2025-05-26 at 06 53 37_73d9e940](https://github.com/user-attachments/assets/83ff0ac8-da71-4de4-823f-9e36652def29)

  <img src=![WhatsApp Image 2025-05-26 at 06 53 37_722ee224](https://github.com/user-attachments/assets/da4b43f7-9898-427f-9200-50364c197352)

  <img src=![WhatsApp Image 2025-05-26 at 06 51 55_52b81b04](https://github.com/user-attachments/assets/ff22348e-d9e6-428c-bf99-04486df29baf)

      </p>

Bookstore Management System

About Laravel
Laravel is a popular open-source PHP framework used for web application development. It follows the MVC (Model-View-Controller) architecture and emphasizes elegant syntax and developer productivity. Laravel provides built-in tools like routing, authentication, and ORM (Eloquent) to simplify complex tasks. It also supports features like Blade templating, RESTful APIs, and robust security mechanisms.



Features:

Book CRUD Operations (Create, Read, Update, Delete)
Advanced Search (by title or author)
Pagination (50 books per page)
Responsive Design (Works on all devices)
Modern UI (Bootstrap 5)

🛠 Technologies Used

Backend: Laravel 10
Frontend: Bootstrap 5
Database: MySQL
Pagination: Laravel Paginator


 Installation:

Clone the repository

git clone https://github.com/username/bookstore.git
cd bookstore
Install dependencies

composer install
npm install
Setup environment

cp .env.example .env
php artisan key:generate
Configure database
Edit .env file:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=bookstore
DB_USERNAME=root
DB_PASSWORD=


php artisan migrate --seed
Start development server

php artisan serve

📂 Project Structure

bookstore-management/
├── app/               # Core application logic
│   ├── Models/        # Database models
│   └── Http/          # Controllers
├── database/          # Migrations and seeders
├── public/            # Publicly accessible files
├── resources/         # Views and assets
├── routes/            # Application routes
└── vendor/            # Composer dependencies

 Usage:
Access the application at http://localhost:8000
Default routes:
/ - Book listing
/books/create - Add new book
/books/{id}/edit - Edit book


📝 License
This project is open-source and available under the MIT License
