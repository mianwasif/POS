# POS
Point of Sale Using Laravel

1. Clone the Repository
To get started, clone or download the repository:
git clone https://github.com/mianwasif/POS.git

2. Set Up the Project
Once you’ve cloned the repository, navigate to the project directory and install dependencies:

cd laravel-point-of-sale
composer install
Open the project in your preferred code editor:

code .
3. Configure the Environment
Rename the .env.example file to .env:

cp .env.example .env
Generate the application key:

php artisan key:generate
4. Set Faker Locale (Optional)
To set the Faker locale (for example, to Indonesian), add the following line at the end of your .env file:

FAKER_LOCALE="id_ID"
5. Set Up the Database
Configure your database credentials in the .env file.

6. Seed the Database
Run the following command to migrate and seed the database:

php artisan migrate:fresh --seed
Note: If you encounter any errors, try rerunning the command.

7. Create Storage Link
Create a symbolic link for storage:

php artisan storage:link
8. Start the Server
To run the application locally, start the Laravel development server:

php artisan serve
9. Log In
Use the following credentials to log in:

Username: admin
Password: password
🚀 Configuration
1. Configure Cart Settings
Open the ./config/cart.php file to configure settings like tax rates, number formats, and more.

For more details, check out the hardevine/shoppingcart documentation.

2. Storage Link
If you haven't already, run this command to create the storage link:

php artisan storage:link
3. Start the Server
Run the development server:

php artisan serve
4. Log In
Try logging in with:

Username: admin
Password: password
