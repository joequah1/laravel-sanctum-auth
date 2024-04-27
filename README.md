# **Laravel Sanctum Authentication API Guide**

Unlock the full potential of your Laravel API with Sanctum! Simplify user authentication processes by creating API endpoints for user registration, login, and logout. Follow these straightforward steps to implement secure authentication in your Laravel project.

For detailed instructions and explanations, please refer to the following guides:

- [Supercharge Your Laravel API: Easy User Authentication with Sanctum](https://www.fastdt.app/2024/04/26/supercharge-your-laravel-api-easy-user-authentication-with-sanctum/)

## **Installation and Setup**

### **Prerequisites**

Make sure you have the following tools installed:

- Basic understanding of the Laravel framework
- Composer installed on your system
- Environment ready to set up Laravel project and ready to integrate Sanctum

### **Quick Start**

1. **Clone the Repository:**
    
    ```bash
    git clone https://github.com/joequah1/laravel-sanctum-auth.git
    cd laravel-sanctum-auth
    ```
    
2. **Set Up Environment Variables:**
    
    Create a **`.env`** file in the project root with your database configurations and secret key:
    
    ```bash
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your_database_name
    DB_USERNAME=your_database_username
    DB_PASSWORD=your_database_password
    ```
    
3. **Install Dependencies:**
    
    ```bash
    composer install
    ```
    
4. **Run Migrations:**
    
    ```bash
    php artisan migrate
    ```
    
5. **Start the Development Server:**
    
    ```bash
    php artisan serve
    ```
    

Your Laravel Sanctum Authentication API is now up and running!

### 

With this comprehensive guide, you'll be equipped to set up Laravel Sanctum authentication quickly and securely in your Laravel project, ensuring a seamless user experience.