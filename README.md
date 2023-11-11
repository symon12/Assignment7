# Assignment7

## Installation

- Step 1: Create a new Laravel project
```bash
composer create-project --prefer-dist laravel/laravel your-project-name
```
- Step 2: Generate UserController
```
cd your-project-name
```
- Generate a new controller named 'UserController':
```
php artisan make:controller UserController
```
- Open the routes/web.php file and add a route to the UserController:
```
use App\Http\Controllers\UserController;

Route::get('/user', [UserController::class, 'index']);
```
## Creating UserController Function

- Open app/Http/Controllers/UserController.php and add the following method:
```
public function index()
{
    return 'Hello, Laravel!';
}
```

## Testing the Route

- Start the Laravel development server:
```
php artisan serve
```

