# Laravel Real-Time Chat with Reverb and Vue 3

This project provides a foundation for building a real-time chat application using Laravel, Laravel Reverb (a Pusher alternative), and Vue 3. It enables users to connect, send messages, and receive updates in real-time, fostering a dynamic and engaging chat experience.

## Installation:

1. Clone the repository:
```
git clone https://github.com/programmertowheed/Chat-Application-With-Laravel-Reverb.git
```

2. Navigate to the project directory:
```
cd Chat-Application-With-Laravel-Reverb
```

3. Install dependencies:
```
composer install
npm install # or yarn install
```

4. Generate application key:
```
php artisan key:generate
```

5. Configure database connection:

Edit `.env` file according to your database credentials.

6. Migrate database tables
```
php artisan migrate
```

7. Start development server
```
php artisan serve
npm run dev:tailwind
php artisan reverb:start
```

Here we used `npm run dev:tailwind` instead of `npm run dev` because we created
a `tailwind` theme using the Laravel Themer package in this project.
